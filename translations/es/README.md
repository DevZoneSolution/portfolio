[![Abre en GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=education/codespaces-project-template-dotnet) 

# .NET (Blazor) Portafolio del Sitio con GitHub Codespaces

_Cree, personalice e implemente su propio sitio web de portafolio en minutos._ ✨

En este repositorio de plantillas tenemos el entorno de desarrollo y el conjunto base y listo para funcionar. Para que pueda iniciar inmediatamente Codespaces para personalizar sin configuración.

* **¿Para quién es esto?** __Cualquiera__ que desee crear un sitio de portafolio, aprender desarrollo web o probar Codespaces.
* **¿Cuánta experiencia necesitas?** __Cero__. Usted decide cuánto desea personalizar según su experiencia y el tiempo disponible.
* **Herramientas necesarias:** _Ninguna_. ¡No es necesario instalar nada! Todo lo que necesitas es un navegador web.
* **Requisitos previos:** _Ninguno_. Esta plantilla incluye su entorno de desarrollo y una aplicación web implementable para que pueda crear su propio sitio.

## Acerca de esta plantilla de portafolio

En este portafolio de plantillas "elige tu propia aventura", tenemos una aplicación web basada en [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor?WT.mc_id=dotnet-82024-juyoo) lista para que la personalice e implemente fácilmente usando solo su navegador web.

![Aplicación web de perfil de Blazor WebAssembly](./images/blazorwasm-portfolio-site.gif "Aplicación web de perfil de Blazor WebAssembly")

### Inicio rápido

1. Haga clic en el botón **Usar esta plantilla**
   
    [![Usar esta plantilla](/images/template-button.svg)](https://github.com/education/codespaces-project-template-dotnet/generate)
1. Seleccione el propietario del repositorio (por ejemplo, su cuenta de GitHub)
1. Ingrese un nombre único para su nuevo repositorio
1. Haga clic en el botón **Código**
1. Haga clic en **Crear Codespace en el botón principal**
1. [Personalice el sitio de su portafolio}(#-personalice-su-sitio-en-4-pasos)
1. [Implemente su sitio](#-implemente-su-aplicación-web)

<details>
    <summary><b>🎥 Para obtener más información sobre Codespaces, vea nuestra serie de tutoriales en video</b></summary>
   
[![Tutorial de Codespaces](https://img.youtube.com/vi/ozuDPmcC1io/0.jpg)](https://aka.ms/CodespacesVideoTutorial "Tutorial de Codespaces")
</details>

<br />

## 🗃️ .NET (Blazor) Plantilla de Portafolio

Este repositorio es una plantilla de GitHub para crear una aplicación web frontend de portafolio personal de .NET utilizando el framework Blazor WebAssembly. El objetivo es brindarle una plantilla para que pueda utilizar de inmediato para crear su propio sitio web a través de Codespaces.

El repositorio contiene lo siguiente:

* `/.DevContainer`
   - `.DevContainer/DockerFile`: archivo de configuración utilizado por Codespaces para determinar el sistema operativo y otros detalles.
   - `.DevContainer/DevContainer.json`: archivo de configuración utilizado por Codespaces para configurar la configuración del código de Visual Studio, como la habilitación de extensiones adicionales.
   - `.devcontainer/post-create.sh`: archivo de configuración utilizado por Codespaces para instalar herramientas adicionales, como PowerShell.
* `/SRC`: Proyecto Blazor WebAssembly para construir su sitio de portafolio.
* `.EditorConfig`: Configuración para [EditorConfig] (https://editorconfig.org/) que ayuda a mantener estilos de codificación consistentes en CodeSpaces.
* `Global.json`: Configuración para la aplicación Blazor WebAssembly para evitar el uso de la versión .NET pre-lanzada.
* `swa-cli.config.json`: Configuración para [Azure SWA CLI](https://azure.github.io/static-web-apps-cli/) para ejecutar la aplicación Blazor WebAssembly en Codespaces.
* `Myportfolio.sln`: el archivo de solución que contiene el proyecto de aplicación Blazor WebAssembly.

<br />

## 🚀 Empezando

Este proyecto de sitio de portafolio está lleno de datos de muestra para que pueda abrir Codespaces inmediatamente, verlo en ejecución e implementarlo en cualquier momento.

Su entorno de desarrollo está listo para que comience. Basado en nuestra [plantilla .NET CodesPaces](https://github.com/education/codespaces-teaching-template-dotnet), aquí está lo que ya está configurado y listo para que use:

* Simple [Blazor WebAssembly](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor?wt.mc_id=dotnet-82024-juyoo) Aplicación con componentes para cada sección del sitio de portafolio
* [SWA CLI](https://azure.github.io/static-web-apps-cli/) en su lugar para construir su sitio cuando se implementa
* Código linting y en formato usando [EditorConfig](https://editorconfig.org/) para la consistencia del código.