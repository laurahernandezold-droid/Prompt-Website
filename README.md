# ✍️ Prompt Creator - Potenciador de IAs

**Licencia:** [MIT](LICENSE) | **Versión Actual:** V3.0



---

### 🔗 Ver Demo en Vivo
Accede a la aplicación directamente:

➡️ **[PROMPT CREATOR EN VIVO]** ⬅️

---

## 🌟 Acerca del Proyecto
Prompt Creator es una aplicación web de propósito único diseñada para mejorar, detallar y optimizar los **prompts** (instrucciones) de los usuarios antes de que sean enviados a modelos de Inteligencia Artificial Generativa, como Gemini, Midjourney, DALL-E, o modelos de código.

El objetivo principal es tomar una idea simple del usuario y transformarla en una instrucción técnica y bien estructurada que maximice la calidad y precisión de la respuesta de la IA.

## 💡 Características Destacadas
* **Optimización por Categoría:** Elige entre cuatro modos especializados (Imagen, Video, Texto, Consejo Desarrollador) para que la IA refine el prompt de manera específica.
* **Modo Gemini 3.0:** Permite la integración de una clave API de Gemini para aprovechar el modelo más avanzado.
* **Interfaz Clara y Fluida:** Construido con Tailwind CSS para una experiencia de usuario rápida y moderna.
* **Multilenguaje:** Soporte inicial para Español, Inglés, Portugués y Francés (V2.1.1).

---

## 📜 Historial de Cambios (Changelog)
Una lista de los cambios significativos y las nuevas características añadidas en cada versión.

### **V3.1 - (3 de Diciembre 2025)**
* **🤖 Actualización Pollinations (Gratis):** El motor de IA gratuito se ha actualizado a la **versión 2.1**, ofreciendo una generación más coherente y rápida sin necesidad de API Key.
* **🧠 Mejoras en la IA:** Se han añadido nuevas capas de refinamiento lógico para que la IA comprenda mejor contextos complejos en todas las categorías.
* **🐛 Corrección de Bugs:** Solución de errores detectados en la versión 3.0 y parches de estabilidad.
* **✨ Mejoras Generales:** Optimizaciones varias en el rendimiento y ajustes menores en la interfaz.

### V3.0.0 - (Diciembre 2025)
* **🚀 Lanzamiento Estable:** Cambio a la versión principal V3.0.0, enfocada en la estabilidad, la optimización y la experiencia de usuario general.
* **🛡️ Seguridad:** Mejora del proceso de verificación de la clave Gemini y manejo de errores de API.
* **⚙️ Optimización:** Refinamiento de las instrucciones del sistema (System Instructions) para asegurar que el output del prompt sea más limpio y directo.

### V2.1.1 Beta - (Noviembre 2025)
* **✨ Nueva Característica:** Implementación de la sección de Configuración (Menú de 3 puntos).
* **🌐 Multilenguaje:** Añadido soporte inicial para 4 idiomas (Español, Inglés, Portugués, Francés).
* **🎨 UX/UI:** Mejoras visuales en los botones de categoría y animaciones de carga.
* **🐛 Corrección:** Arreglado el viewport para una mejor experiencia móvil.

### V2.0.0 - (Octubre 2025)
* **🚀 Lanzamiento Mayor:** Introducción del Modo Gemini 3.0 con verificación de clave API.
* **⚡ Rendimiento:** Cambio de la arquitectura de la API a `fetch` con gestión de errores y `retry`.
* **🆕 Categoría:** Añadida la categoría "Consejo Desarrollador" para prompts de código.

---

## 🛠️ Tecnología Utilizada
Este proyecto es una aplicación web estática (Single Page Application) que se ejecuta enteramente en el lado del cliente (navegador).

* **HTML5:** Estructura base.
* **Tailwind CSS (v3):** Framework para el diseño y la interfaz de usuario.
* **JavaScript ES6+:** Lógica de la aplicación, manejo de modales y la comunicación asíncrona (API calls).
* **API de Gemini (Integración):** Usada para la optimización real de los prompts cuando se activa el Modo Gemini 3.0.

---

## 🚀 Instalación y Ejecución Local
Dado que esta es una aplicación web puramente basada en HTML, Tailwind CSS y JavaScript, no requiere de un proceso de build complejo o dependencias de backend.

1.  **Clonar el Repositorio:**
    ```bash
    git clone [https://github.com/TuUsuario/prompt-creator-repo.git](https://github.com/TuUsuario/prompt-creator-repo.git)
    cd prompt-creator-repo
    ```
2.  **Abrir en el Navegador:** Simplemente abre el archivo `index.html` en tu navegador web.

> **Nota:** Para probar la funcionalidad completa de la API, deberás subir la aplicación a un servidor web o usar una extensión de servidor local (como **Live Server** de VS Code), ya que los navegadores modernos restringen las llamadas a la API desde archivos locales (`file://`).

---

## ⚙️ Configuración del Modo Gemini
Para obtener la mejor experiencia de optimización, puedes activar el "Modo Gemini 3.0":

1.  Haz clic en el botón "Activar 'Modo Gemini 3.0'" en la parte inferior de la página principal.
2.  Obtén tu Clave API de Gemini desde [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key).
3.  Pega la clave en el campo de texto y haz clic en "Verificar y Activar Key".

Una vez verificada, la aplicación usará tu clave para refinar los prompts en lugar del modo básico predeterminado.

> **Advertencia de Código:** Recuerda que la categoría "Consejo Desarrollador" viene con una advertencia: "Verifica siempre el código generado" antes de usarlo en producción, ya que las IAs pueden cometer errores lógicos.

---

## 🤝 Contribución
¡Las contribuciones son bienvenidas! Si deseas mejorar el diseño, añadir categorías de prompts o expandir la funcionalidad, sigue estos pasos:

1.  Haz un *fork* de este repositorio.
2.  Crea una rama para tu característica: `git checkout -b feature/nueva-caracteristica`.
3.  Realiza tus cambios y haz commit: `git commit -m 'feat: Añade soporte para prompts de música'`.
4.  Sube tu rama: `git push origin feature/nueva-caracteristica`.
5.  Abre un *Pull Request* detallando tus cambios.

---

## 📄 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---
*Creador: Ghosy*
