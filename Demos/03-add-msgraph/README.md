# <a name="how-to-run-the-completed-project"></a><span data-ttu-id="5ef0f-101">Cómo ejecutar el proyecto completado</span><span class="sxs-lookup"><span data-stu-id="5ef0f-101">How to run the completed project</span></span>

## <a name="prerequisites"></a><span data-ttu-id="5ef0f-102">Requisitos previos</span><span class="sxs-lookup"><span data-stu-id="5ef0f-102">Prerequisites</span></span>

<span data-ttu-id="5ef0f-103">Para ejecutar el proyecto completado en esta carpeta, necesita lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="5ef0f-103">To run the completed project in this folder, you need the following:</span></span>

- <span data-ttu-id="5ef0f-104">[Ruby](https://www.ruby-lang.org/en/downloads/) instalado en el equipo de desarrollo.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-104">[Ruby](https://www.ruby-lang.org/en/downloads/) installed on your development machine.</span></span> <span data-ttu-id="5ef0f-105">Si no tiene Ruby, visite el vínculo anterior para las opciones de descarga.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-105">If you do not have Ruby, visit the previous link for download options.</span></span> <span data-ttu-id="5ef0f-106">(**Nota:** este tutorial se ha escrito con la versión 2.4.4 de Ruby.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-106">(**Note:** This tutorial was written with Ruby version 2.4.4.</span></span> <span data-ttu-id="5ef0f-107">Los pasos de esta guía pueden funcionar con otras versiones, pero no se han probado.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-107">The steps in this guide may work with other versions, but that has not been tested.)</span></span>
- <span data-ttu-id="5ef0f-108">Una cuenta de Microsoft personal con un buzón de correo en Outlook.com o una cuenta profesional o educativa de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-108">Either a personal Microsoft account with a mailbox on Outlook.com, or a Microsoft work or school account.</span></span>

<span data-ttu-id="5ef0f-109">Si no tiene una cuenta de Microsoft, hay un par de opciones para obtener una cuenta gratuita:</span><span class="sxs-lookup"><span data-stu-id="5ef0f-109">If you don't have a Microsoft account, there are a couple of options to get a free account:</span></span>

- <span data-ttu-id="5ef0f-110">Puede [registrarse para obtener una nueva cuenta Microsoft personal](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).</span><span class="sxs-lookup"><span data-stu-id="5ef0f-110">You can [sign up for a new personal Microsoft account](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).</span></span>
- <span data-ttu-id="5ef0f-111">Puede [registrarse para el programa de desarrolladores de office 365](https://developer.microsoft.com/office/dev-program) para obtener una suscripción gratuita a Office 365.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-111">You can [sign up for the Office 365 Developer Program](https://developer.microsoft.com/office/dev-program) to get a free Office 365 subscription.</span></span>

## <a name="register-a-web-application-with-the-application-registration-portal"></a><span data-ttu-id="5ef0f-112">Registro de una aplicación web con el portal de registro de aplicaciones</span><span class="sxs-lookup"><span data-stu-id="5ef0f-112">Register a web application with the Application Registration Portal</span></span>

1. <span data-ttu-id="5ef0f-113">Abra un explorador y vaya al [Portal del registro de aplicaciones](https://apps.dev.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="5ef0f-113">Open a browser and navigate to the [Application Registry Portal](https://apps.dev.microsoft.com).</span></span> <span data-ttu-id="5ef0f-114">Inicie sesión con una **cuenta personal** (también conocido como Microsoft Account) o una **cuenta profesional o educativa**.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-114">Login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="5ef0f-115">Seleccione **Agregar una aplicación** en la parte superior de la página.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-115">Select **Add an app** at the top of the page.</span></span>

    > <span data-ttu-id="5ef0f-116">**Nota:** Si ve más de un botón **Agregar una aplicación** en la página, seleccione el que corresponda a la lista de **aplicaciones convergentes** .</span><span class="sxs-lookup"><span data-stu-id="5ef0f-116">**Note:** If you see more than one **Add an app** button on the page, select the one that corresponds to the **Converged apps** list.</span></span>

1. <span data-ttu-id="5ef0f-117">En la página **registrar la aplicación** , establezca el tutorial **nombre** de la aplicación para el **gráfico Ruby on Rails** y seleccione **crear**.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-117">On the **Register your application** page, set the **Application Name** to **Ruby on Rails Graph Tutorial** and select **Create**.</span></span>

    ![Captura de pantalla de la creación de una nueva aplicación en el sitio web del portal de registro de aplicaciones](/Images/arp-create-app-01.png)

1. <span data-ttu-id="5ef0f-119">En la página de **registro del tutorial de gráficos Ruby on Rails** , en la sección **propiedades** , copie el identificador de la **aplicación** ya que lo necesitará más adelante.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-119">On the **Ruby on Rails Graph Tutorial Registration** page, under the **Properties** section, copy the **Application Id** as you will need it later.</span></span>

    ![Captura de pantalla del identificador de la aplicación recién creada](/Images/arp-create-app-02.png)

1. <span data-ttu-id="5ef0f-121">Desplácese hacia abajo hasta la sección secretos de la **aplicación** .</span><span class="sxs-lookup"><span data-stu-id="5ef0f-121">Scroll down to the **Application Secrets** section.</span></span>

    1. <span data-ttu-id="5ef0f-122">Seleccione **generar nueva contraseña**.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-122">Select **Generate New Password**.</span></span>
    1. <span data-ttu-id="5ef0f-123">En el cuadro de diálogo **nueva contraseña generada** , copie el contenido del cuadro tal y como lo necesitará más adelante.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-123">In the **New password generated** dialog, copy the contents of the box as you will need it later.</span></span>

        > <span data-ttu-id="5ef0f-124">**Importante:** Esta contraseña no se vuelve a mostrar nunca, por lo que debe asegurarse de que la copia ahora.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-124">**Important:** This password is never shown again, so make sure you copy it now.</span></span>

    ![Captura de pantalla de la contraseña de la aplicación recién creada](/Images/arp-create-app-03.png)

1. <span data-ttu-id="5ef0f-126">Desplácese hacia abajo hasta la sección **plataformas** .</span><span class="sxs-lookup"><span data-stu-id="5ef0f-126">Scroll down to the **Platforms** section.</span></span>

    1. <span data-ttu-id="5ef0f-127">Seleccione **Agregar plataforma**.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-127">Select **Add Platform**.</span></span>
    1. <span data-ttu-id="5ef0f-128">En el cuadro de diálogo **Agregar plataforma** , seleccione **Web**.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-128">In the **Add Platform** dialog, select **Web**.</span></span>

        ![Captura de pantalla que crea una plataforma para la aplicación](/Images/arp-create-app-04.png)

    1. <span data-ttu-id="5ef0f-130">En el cuadro plataforma **Web** , escriba la dirección `http://localhost:3000/auth/microsoft_graph_auth/callback` URL de las **direcciones URL**de redireccionamiento.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-130">In the **Web** platform box, enter the URL `http://localhost:3000/auth/microsoft_graph_auth/callback` for the **Redirect URLs**.</span></span>

        ![Captura de pantalla de la plataforma web recién agregada para la aplicación](/Images/arp-create-app-05.png)

1. <span data-ttu-id="5ef0f-132">Desplácese hasta la parte inferior de la página y seleccione **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-132">Scroll to the bottom of the page and select **Save**.</span></span>

## <a name="configure-the-sample"></a><span data-ttu-id="5ef0f-133">Configuración del ejemplo</span><span class="sxs-lookup"><span data-stu-id="5ef0f-133">Configure the sample</span></span>

1. <span data-ttu-id="5ef0f-134">Cambie el nombre `./config/oauth_environment_variables.rb.example` del archivo `oauth_environment_variables.rb`a.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-134">Rename the `./config/oauth_environment_variables.rb.example` file to `oauth_environment_variables.rb`.</span></span>
1. <span data-ttu-id="5ef0f-135">Edite `oauth_environment_variables.rb` el archivo y realice los cambios siguientes.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-135">Edit the `oauth_environment_variables.rb` file and make the following changes.</span></span>
    1. <span data-ttu-id="5ef0f-136">Reemplace `YOUR_APP_ID_HERE` por el **identificador de aplicación** que obtuvo desde el portal de registro de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-136">Replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the App Registration Portal.</span></span>
    1. <span data-ttu-id="5ef0f-137">Reemplace `YOUR APP PASSWORD HERE` por la contraseña que obtuvo en el portal de registro de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-137">Replace `YOUR APP PASSWORD HERE` with the password you got from the App Registration Portal.</span></span>
1. <span data-ttu-id="5ef0f-138">En la interfaz de línea de comandos (CLI), navegue a este directorio y ejecute el siguiente comando para instalar los requisitos.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-138">In your command-line interface (CLI), navigate to this directory and run the following command to install requirements.</span></span>

    ```Shell
    bundle install
    ```

1. <span data-ttu-id="5ef0f-139">En la CLI, ejecute el siguiente comando para inicializar la base de datos de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-139">In your CLI, run the following command to initialize the app's database.</span></span>

    ```Shell
    rake db:migrate
    ```

## <a name="run-the-sample"></a><span data-ttu-id="5ef0f-140">Ejecutar el ejemplo</span><span class="sxs-lookup"><span data-stu-id="5ef0f-140">Run the sample</span></span>

1. <span data-ttu-id="5ef0f-141">Ejecute el siguiente comando en su CLI para iniciar la aplicación.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-141">Run the following command in your CLI to start the application.</span></span>

    ```Shell
    rails server
    ```

1. <span data-ttu-id="5ef0f-142">Abra un explorador y vaya a `http://localhost:3000`.</span><span class="sxs-lookup"><span data-stu-id="5ef0f-142">Open a browser and browse to `http://localhost:3000`.</span></span>