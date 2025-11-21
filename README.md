## 📚 Generador de Ideas Sorpresa (Académico) - GISA

¡Bienvenido al repositorio del **Generador de Ideas Sorpresa (Académico)**, una herramienta que utiliza la visión y la creatividad lateral de Gemini para generar conceptos de meta-aplicaciones inesperadas para la comunidad de investigadores, lectores y bibliotecarios\!

El acrónimo del proyecto es **GISA** (Generador de Ideas Sorpresa (Académico)).

-----

### 🚀 ¿Qué es GISA?

GISA es una aplicación web sencilla diseñada para estimular el pensamiento lateral. El usuario sube una imagen y, basándose en el estado de ánimo, los colores y los objetos de la imagen (pero sin relacionarse directamente con su contenido), la aplicación genera un *prompt* profesional en inglés para una mini-aplicación completamente abstracta y sorprendente en el ámbito académico.

El concepto de la aplicación es una **metáfora abstracta** de lo que se ve, asegurando que el resultado sea siempre inesperado. Por ejemplo, una imagen de una puesta de sol tranquila podría inspirar un concepto para una "Aplicación de Gestión de Crisis de Datos" para investigadores.

### ✨ Características

  * **Entrada Visual:** Sube cualquier imagen (JPG, PNG) para iniciar el proceso creativo.
  * **Creatividad Lateral:** Utiliza el modelo Gemini con instrucciones de sistema diseñadas para el pensamiento abstracto y la generación de metáforas.
  * **Output Profesional:** Genera directamente el *prompt* en **inglés** listo para ser utilizado en Google AI Studio (o cualquier herramienta de desarrollo impulsada por IA).
  * **Integración con AI Studio:** Un botón de acción rápida (`¿Quieres que desarrollemos esta app?`) copia el *prompt* y abre Google AI Studio en una nueva pestaña, facilitando el siguiente paso en el desarrollo.

### ⚙️ Tecnología Utilizada

Este proyecto es un **solo archivo HTML** y utiliza tecnologías web estándar:

  * **HTML5 y JavaScript:** Para la estructura y la lógica principal.
  * **Tailwind CSS:** Para un diseño moderno, responsivo y de carga rápida.
  * **API de Gemini (gemini-2.5-flash-preview-09-2025):** Para el análisis de imágenes y la generación creativa de texto, llamada mediante `fetch`.

### 💻 Instalación y Uso

Dado que el proyecto es un solo archivo `index.html` con *scripts* en línea, la instalación es muy sencilla:

1.  **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/nombre-del-repositorio.git
    cd nombre-del-repositorio
    ```
2.  **Abrir el Archivo:** Simplemente abre el archivo `index.html` en tu navegador web.

#### Configuración de la API

El archivo `index.html` tiene la siguiente línea en el bloque `<script type="module">`:

```javascript
const apiKey = ""; // Canvas provides the API key at runtime if left empty
```

Si ejecutas esto localmente, necesitarás una clave de API de Gemini.

1.  Obtén tu clave en Google AI Studio.
2.  Reemplaza la línea con tu clave:
    ```javascript
    const apiKey = "TU_CLAVE_DE_API_AQUÍ"; // ¡Reemplaza por tu clave real!
    ```

**Nota:** Si este código se ejecuta en un entorno de Google (como un *Canvas* o una aplicación interna), la clave de API puede ser proporcionada automáticamente por el entorno si se deja vacía.

### 📝 Cómo Contribuir

¡Las contribuciones son bienvenidas\! Si tienes ideas para mejorar la lógica del *prompt* del sistema, el diseño, o la usabilidad, no dudes en:

1.  Hacer un *Fork* del repositorio.
2.  Crear una nueva rama (`git checkout -b feature/mejora-increible`).
3.  Realizar tus cambios y hacer *commit* (`git commit -m 'Añadir: Funcionalidad X'`).
4.  Subir la rama (`git push origin feature/mejora-increible`).
5.  Abrir un *Pull Request* detallado.
