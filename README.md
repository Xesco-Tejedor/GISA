<p align="center"><img src="assets/assets/gisa-amber.svg" alt="GISA · Generador de Ideas Sorpresa · Xesco Tejedor" width="100%"></p>

<p align="center"><a href="https://xesco-tejedor.github.io/GISA/"><img src="https://img.shields.io/badge/ABRIR-GISA-ffb800?style=for-the-badge&amp;labelColor=161215" alt="Abrir GISA"></a></p>

## Una imagen. Otra mirada. Una app inesperada.

El **Generador de Ideas Sorpresa (Académico)** es una herramienta que utiliza la visión y la creatividad lateral de Gemini para generar conceptos de meta-aplicaciones inesperadas para la comunidad de investigadores, lectores y bibliotecarios.

El acrónimo del proyecto es **GISA** (Generador de Ideas Sorpresa (Académico)).

-----

### 🚀 ¿Qué es GISA?

GISA es una aplicación web sencilla diseñada para estimular el pensamiento lateral. El usuario sube una imagen y, basándose en el estado de ánimo, los colores y los objetos de la imagen (pero sin relacionarse directamente con su contenido), la aplicación genera un *prompt* profesional en inglés para una mini-aplicación completamente abstracta y sorprendente en el ámbito académico.

El concepto de la aplicación es una **metáfora abstracta** de lo que se ve, asegurando que el resultado sea siempre inesperado. Por ejemplo, una imagen de una puesta de sol tranquila podría inspirar un concepto para una "Aplicación de Gestión de Crisis de Datos" para investigadores.

### ✨ Características

  * **Identidad ámbar:** Fondos carbón y burdeos, acento #ffb800, Space Grotesk, luz suave y movimiento discreto, como el portfolio de Xesco Tejedor. Respeta la preferencia de movimiento reducido.
  * **Cámara y navegación:** Usa la cámara del dispositivo, vuelve al inicio o empieza con otra imagen o una nueva foto.

  * **Entrada Visual:** Sube cualquier imagen (JPG, PNG) para iniciar el proceso creativo.
  * **Creatividad Lateral:** Utiliza el modelo Gemini con instrucciones de sistema diseñadas para el pensamiento abstracto y la generación de metáforas.
  * **Output Profesional:** Genera directamente el *prompt* en **inglés** listo para ser utilizado en Google AI Studio (o cualquier herramienta de desarrollo impulsada por IA).
  * **Construcción:** Copia el *prompt* y abre AI Studio o Bolt con la idea prellenada. GISA no crea ni publica automáticamente una app. Los límites y las condiciones de publicación dependen de cada plataforma.

### ⚙️ Tecnología Utilizada

Este proyecto es un **solo archivo HTML** y utiliza tecnologías web estándar:

  * **HTML5 y JavaScript:** Para la estructura y la lógica principal.
  * **Tailwind CSS:** Para un diseño moderno, responsivo y de carga rápida.
  * **API de Gemini (gemini-3.8-flash):** Para el análisis de imágenes y la generación creativa de texto, llamada mediante `fetch`.

### 💻 Instalación y Uso

Dado que el proyecto es un solo archivo `index.html` con *scripts* en línea, la instalación es muy sencilla:

1.  **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/Xesco-Tejedor/GISA.git
    cd GISA
    ```
2.  **Abrir el Archivo:** Simplemente abre el archivo `index.html` en tu navegador web.

#### Configuración de la API

Demo: https://xesco-tejedor.github.io/GISA/

La clave de Gemini no está en el código público. La web llama a un pequeño servidor intermedio (proxy) que guarda la clave como secreto y reenvía la petición a Gemini; su URL va en la constante `PROXY_URL` de `index.html`. Para ejecutarlo por tu cuenta, o bien despliegas un proxy equivalente, o bien (solo en local) pones tu propia clave de https://aistudio.google.com/apikey en `apiKey` y no la subes a ningún repositorio.

### 📝 Cómo Contribuir

¡Las contribuciones son bienvenidas\! Si tienes ideas para mejorar la lógica del *prompt* del sistema, el diseño, o la usabilidad, no dudes en:

1.  Hacer un *Fork* del repositorio.
2.  Crear una nueva rama (`git checkout -b feature/mejora-increible`).
3.  Realizar tus cambios y hacer *commit* (`git commit -m 'Añadir: Funcionalidad X'`).
4.  Subir la rama (`git push origin feature/mejora-increible`).
5.  Abrir un *Pull Request* detallado.

### Privacidad y cuotas

La imagen se envía al proveedor de IA mediante el servidor intermediario. Las cuotas gratuitas pueden limitar la generación. Nunca publiques claves de API en el código del navegador.
