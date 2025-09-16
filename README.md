<h1 align="center">ShadowHub</h1>

<p align="center">
  <img src="./assets/logo.png" height="120px" alt="ShadowHub logo" />
</p>

<p align="center">
  <strong>Tu centro multimedia personalizable para Android TV y móvil.</strong>
  <br />
  ShadowHub es un navegador de extensiones de código abierto, diseñado para unificar tu experiencia de entretenimiento en una sola interfaz.
</p>

<p align="center">
    <a href="https://github.com/[TU-USUARIO]/shadowhub/releases/latest"><img src="https://img.shields.io/github/v/release/[TU-USUARIO]/shadowhub?style=for-the-badge&logo=android&color=3DDC84" alt="Última Versión"></a>
    <img src="https://img.shields.io/badge/Licencia-Apache_2.0-blue.svg?style=for-the-badge" alt="Licencia">
    <a href="https://github.com/[TU-USUARIO]/shadowhub/issues"><img src="https://img.shields.io/github/issues/[TU-USUARIO]/shadowhub?style=for-the-badge&logo=github" alt="Issues"></a>
</p>

<p align="center">
  <a href="#descargar"><strong>Descargar la App »</strong></a>
  ·
  <a href="https://github.com/[TU-USUARIO]/shadowhub/issues">Reportar un Bug</a>
  ·
  <a href="https://github.com/[TU-USUARIO]/shadowhub/issues">Solicitar una Característica</a>
</p>

<details>
  <summary><strong>Tabla de Contenidos</strong></summary>

- [¿Por qué ShadowHub?](#por-qué-shadowhub)
- [Acerca del Proyecto](#acerca-del-proyecto)
  - [Características Principales](#características-principales)
  - [Construido Con](#construido-con)
- [Empezando](#empezando)
  - [Prerrequisitos](#prerrequisitos)
  - [Instalación y Desarrollo](#instalación-y-desarrollo)
- [Uso Básico](#uso-básico)
- [Hoja de Ruta (Roadmap)](#hoja-de-ruta-roadmap)
- [Cómo Contribuir](#cómo-contribuir)
- [Apoya el Proyecto](#apoya-el-proyecto)
- [Agradecimientos](#agradecimientos)
- [Descargo de Responsabilidad](#descargo-de-responsabilidad)
- [Autor](#autor)
- [Licencia](#licencia)
</details>

## ¿Por qué ShadowHub?

En el ecosistema digital actual, el contenido multimedia está fragmentado en innumerables servicios y plataformas. ShadowHub nace como una solución a este problema, ofreciendo una plataforma unificada y agnóstica que pone el control en manos del usuario.

En lugar de ser otro servicio de contenido, ShadowHub es una **herramienta poderosa**. Funciona como un navegador especializado que, a través de **extensiones de terceros**, te permite agregar, organizar y acceder a tus fuentes de entretenimiento favoritas desde una interfaz limpia, rápida y optimizada para cualquier pantalla.

## Acerca del Proyecto

<p align="center">
  <img src="./.github/docs/screenshot.png" alt="ShadowHub Preview">
</p>

**ShadowHub** es una aplicación para Android TV y móvil que actúa como un centro de entretenimiento modular. No aloja ni distribuye contenido por sí misma; su poder reside en su arquitectura extensible. Los usuarios pueden instalar repositorios de extensiones desarrolladas por la comunidad para acceder a una variedad casi ilimitada de películas, series y más.

### Características Principales

* ✅ **100% Gratis y de Código Abierto**: Sin costos ocultos, sin anuncios. Transparencia total.
* 🧩 **Arquitectura Basada en Extensiones**: El corazón de ShadowHub. Instala extensiones de diversas fuentes para personalizar tu catálogo de contenido. ¡Tú decides qué agregar!
* 📱 **Interfaz Unificada y Adaptable**: Diseñada desde cero con Kotlin, ofrece una experiencia de usuario fluida y consistente tanto en dispositivos móviles como en la pantalla grande de tu Android TV (Leanback UI).
* 🌐 **Múltiples Proveedores**: Agrega contenido de todas tus extensiones y navega por él en un solo lugar, eliminando la necesidad de cambiar entre aplicaciones.
* 🔄 **Sincronización y Continuidad**: Reanuda la reproducción exactamente donde la dejaste, sin importar el proveedor del contenido.
* ⬆️ **Actualizaciones Frecuentes**: Sistema de actualización integrado en la app para asegurar que siempre tengas las últimas características y correcciones.

### Construido Con

Este proyecto es posible gracias al increíble ecosistema de desarrollo de Android. Aquí están algunas de las tecnologías clave que lo impulsan:

| Tecnología | Descripción |
| :--- | :--- |
| **Kotlin** | Lenguaje de programación principal: moderno, seguro y conciso. |
| **Android Studio** | IDE oficial para el desarrollo nativo de Android. |
| **MVVM Architecture** | Patrón de diseño para una base de código limpia, escalable y fácil de mantener. |
| **Coroutines** | Para una gestión de tareas asíncronas eficiente y legible. |
| **Retrofit** | Cliente HTTP para una comunicación robusta con APIs externas. |
| **ExoPlayer** | Reproductor de medios avanzado y personalizable para Android. |
| **Leanback** | Librería oficial para construir interfaces de usuario de alta calidad en Android TV. |
| **Android Arch. Components**| Componentes como ViewModel, LiveData y Room para un desarrollo moderno. |

## Empezando

Si deseas contribuir al código o simplemente ejecutar tu propia versión, sigue estos pasos.

### Prerrequisitos

* **[Android Studio](https://developer.android.com/studio)** (versión Iguana o superior recomendada).
* Conocimientos básicos de Kotlin y desarrollo de apps para Android.

### Instalación y Desarrollo

1.  **Haz un Fork** del repositorio a tu propia cuenta de GitHub.
2.  **Clona tu Fork** en tu máquina local:
    ```bash
    git clone [https://github.com/](https://github.com/)[TU-USUARIO]/shadowhub.git
    ```
3.  **Abre el proyecto** en Android Studio.
4.  **Sincroniza Gradle**: Espera a que Android Studio descargue todas las dependencias necesarias.
5.  **Selecciona el dispositivo**: Elige un emulador o un dispositivo físico conectado.
6.  **Ejecuta la aplicación**: Haz clic en el botón **Run** (▶️).

## Uso Básico

Una vez instalada la aplicación:
1.  Ve a la sección de **Configuración** dentro de ShadowHub.
2.  Selecciona la opción para **Añadir Repositorio de Extensiones**.
3.  Introduce la URL del repositorio de extensiones que desees usar.
4.  Una vez añadido, podrás navegar y elegir qué extensiones específicas instalar.
5.  ¡Listo! El contenido de las extensiones instaladas aparecerá en la pantalla principal.

## Hoja de Ruta (Roadmap)

ShadowHub está en desarrollo activo. Aquí hay algunas de las características planeadas para el futuro:

-   [ ]  Chromecast Support
-   [ ] Sincronización de cuenta (Trakt.tv, etc.)
-   [ ] Temas personalizables (Modo claro/oscuro)
-   [ ] Descarga de contenido para visualización sin conexión
-   [ ] Búsqueda global mejorada a través de todas las extensiones

¡Si tienes una idea, no dudes en [abrir un issue](https://github.com/[TU-USUARIO]/shadowhub/issues) para discutirla!

## Cómo Contribuir

¡Las contribuciones son el alma de los proyectos de código abierto! Si quieres ayudar a mejorar ShadowHub, eres más que bienvenido.

1.  Haz un Fork del Proyecto.
2.  Crea tu rama de característica (`git checkout -b feature/AmazingFeature`).
3.  Haz commit de tus cambios (`git commit -m 'feat: Add some AmazingFeature'`).
4.  Haz push a la rama (`git push origin feature/AmazingFeature`).
5.  Abre un Pull Request, describiendo claramente los cambios que has realizado.

## Apoya el Proyecto

ShadowHub es un proyecto personal desarrollado en mi tiempo libre. Si te gusta la aplicación y quieres apoyar su continuo desarrollo, puedes invitarme un café o hacer una donación. ¡Cualquier ayuda es enormemente apreciada!

<p align="center">
  <a href="https://www.buymeacoffee.com/tu-usuario-coffee">
    <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee">
  </a>
  <a href="https://paypal.me/tu-usuario-paypal">
    <img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="Donate with PayPal">
  </a>
</p>

## Agradecimientos

-   Este proyecto está fuertemente inspirado y basado en el código de **Streamflix**.
-   Un agradecimiento especial a **[Lory-Stan TANASI](https://github.com/stantanasi)** por su increíble trabajo original, que sirvió como pilar fundamental para ShadowHub.

## Descargo de Responsabilidad

> **Este proyecto se ha creado y se mantiene con fines puramente educativos, como un incentivo para el aprendizaje y la experimentación en la programación de aplicaciones Android.**
>
> ShadowHub es una herramienta de software neutra, análoga a un navegador web. No aloja, distribuye ni tiene afiliación alguna con el contenido que se pueda visualizar a través de las extensiones. La aplicación simplemente actúa como un motor que interpreta datos y enlaces proporcionados por terceros.
>
> **Los únicos y totales responsables del contenido son los sitios web de terceros que lo alojan públicamente en Internet.** Cualquier procedimiento legal o reclamo sobre derechos de autor debe dirigirse directamente a dichos proveedores de contenido. Nuestro proyecto no se hace responsable de la legalidad o la naturaleza del material al que se accede.
>
> **El usuario final es el único y total responsable de las extensiones que instala y del uso que hace de la aplicación.** Cualquier problema legal o de derechos de autor relacionado con el contenido es responsabilidad exclusiva del usuario. Se recomienda a los usuarios cumplir con las leyes de derechos de autor de su localidad.

## Autor

-   **[Tu Nombre]** - *Desarrollador Principal* - [[Tu Perfil de GitHub](https://github.com/[TU-USUARIO])]

## Licencia

Este proyecto está licenciado bajo la Licencia `Apache-2.0`. Consulta el archivo [LICENSE](LICENSE) para más detalles.

<p align="center">
  <br />
  © 2025 Tu Nombre. Todos los derechos reservados.
</p>
