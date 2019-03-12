# <a name="how-to-run-the-completed-project"></a>Cómo ejecutar el proyecto completado

## <a name="prerequisites"></a>Requisitos previos

Para ejecutar el proyecto completado en esta carpeta, necesita lo siguiente:

- [Ruby](https://www.ruby-lang.org/en/downloads/) instalado en el equipo de desarrollo. Si no tiene Ruby, visite el vínculo anterior para las opciones de descarga. (**Nota:** este tutorial se ha escrito con la versión 2.4.4 de Ruby. Los pasos de esta guía pueden funcionar con otras versiones, pero no se han probado.
- Una cuenta de Microsoft personal con un buzón de correo en Outlook.com o una cuenta profesional o educativa de Microsoft.

Si no tiene una cuenta de Microsoft, hay un par de opciones para obtener una cuenta gratuita:

- Puede [registrarse para obtener una nueva cuenta Microsoft personal](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).
- Puede [registrarse para el programa de desarrolladores de office 365](https://developer.microsoft.com/office/dev-program) para obtener una suscripción gratuita a Office 365.

## <a name="register-a-web-application-with-the-application-registration-portal"></a>Registro de una aplicación web con el portal de registro de aplicaciones

1. Abra un explorador y vaya al [Portal del registro de aplicaciones](https://apps.dev.microsoft.com). Inicie sesión con una **cuenta personal** (también conocido como Microsoft Account) o una **cuenta profesional o educativa**.

1. Seleccione **Agregar una aplicación** en la parte superior de la página.

    > **Nota:** Si ve más de un botón **Agregar una aplicación** en la página, seleccione el que corresponda a la lista de **aplicaciones convergentes** .

1. En la página **registrar la aplicación** , establezca el tutorial **nombre** de la aplicación para el **gráfico Ruby on Rails** y seleccione **crear**.

    ![Captura de pantalla de la creación de una nueva aplicación en el sitio web del portal de registro de aplicaciones](/Images/arp-create-app-01.png)

1. En la página de **registro del tutorial de gráficos Ruby on Rails** , en la sección **propiedades** , copie el identificador de la **aplicación** ya que lo necesitará más adelante.

    ![Captura de pantalla del identificador de la aplicación recién creada](/Images/arp-create-app-02.png)

1. Desplácese hacia abajo hasta la sección secretos de la **aplicación** .

    1. Seleccione **generar nueva contraseña**.
    1. En el cuadro de diálogo **nueva contraseña generada** , copie el contenido del cuadro tal y como lo necesitará más adelante.

        > **Importante:** Esta contraseña no se vuelve a mostrar nunca, por lo que debe asegurarse de que la copia ahora.

    ![Captura de pantalla de la contraseña de la aplicación recién creada](/Images/arp-create-app-03.png)

1. Desplácese hacia abajo hasta la sección **plataformas** .

    1. Seleccione **Agregar plataforma**.
    1. En el cuadro de diálogo **Agregar plataforma** , seleccione **Web**.

        ![Captura de pantalla que crea una plataforma para la aplicación](/Images/arp-create-app-04.png)

    1. En el cuadro plataforma **Web** , escriba la dirección `http://localhost:3000/auth/microsoft_graph_auth/callback` URL de las **direcciones URL**de redireccionamiento.

        ![Captura de pantalla de la plataforma web recién agregada para la aplicación](/Images/arp-create-app-05.png)

1. Desplácese hasta la parte inferior de la página y seleccione **Guardar**.

## <a name="configure-the-sample"></a>Configuración del ejemplo

1. Cambie el nombre `./config/oauth_environment_variables.rb.example` del archivo `oauth_environment_variables.rb`a.
1. Edite `oauth_environment_variables.rb` el archivo y realice los cambios siguientes.
    1. Reemplace `YOUR_APP_ID_HERE` por el **identificador de aplicación** que obtuvo desde el portal de registro de aplicaciones.
    1. Reemplace `YOUR APP PASSWORD HERE` por la contraseña que obtuvo en el portal de registro de aplicaciones.
1. En la interfaz de línea de comandos (CLI), navegue a este directorio y ejecute el siguiente comando para instalar los requisitos.

    ```Shell
    bundle install
    ```

1. En la CLI, ejecute el siguiente comando para inicializar la base de datos de la aplicación.

    ```Shell
    rake db:migrate
    ```

## <a name="run-the-sample"></a>Ejecutar el ejemplo

1. Ejecute el siguiente comando en su CLI para iniciar la aplicación.

    ```Shell
    rails server
    ```

1. Abra un explorador y vaya a `http://localhost:3000`.