# 🇮🇹 CIAO Idiomas — Landing Page de Viajes de Estudio

¡Bienvenidos a la landing page oficial de los **Viajes de Estudio a Italia** organizados por **CIAO Idiomas**! Este sitio web está diseñado con una estética premium, moderna e inmersiva, orientada a convertir consultas en reservas de entrevistas de la manera más fluida posible.

---

## ✨ Características Principales

*   **🎨 Diseño Premium & Rich Aesthetics**: Paleta de colores armoniosa, tipografía moderna, bordes redondeados orgánicos, sombras suaves y micro-interacciones interactivas.
*   **🌀 Fondo Animado con WebGL (Shader)**: La portada (Hero) cuenta con un canvas interactivo animado mediante un shader WebGL nativo de alto rendimiento para simular corrientes fluidas de color italiano.
*   **📱 Diseño 100% Responsivo**: Adaptado perfectamente para celulares, tablets y pantallas de escritorio.
*   **🗺️ Itinerario Completo Continuo**: El recorrido de 18 días por **Bologna, Venecia, Florencia y Roma** se presenta de manera continua y asimétrica en pantallas grandes para un ritmo visual de primer nivel.
*   **💬 Formulario de Contacto Inteligente**: Recopila automáticamente los datos del usuario y genera un mensaje estructurado pre-completado que redirige directamente al WhatsApp de viajes oficial.
*   **🧳 Guía de Consejos y Puntos Clave**: Pestañas dinámicas e interactivas con recomendaciones prácticas de viaje (documentación, equipaje, dinero, etc.).
*   **👥 Enfoque en Convivencia e Inclusión**: Sección dedicada que detalla la filosofía comunitaria del viaje (apto para todas las edades, sin límites) inspirada en los mejores modelos de viajes grupales.

---

## 📂 Estructura del Proyecto

El entregable final está optimizado y estructurado de la siguiente forma:

```text
ciao/
├── assets/                  # Recursos visuales y multimedia del sitio
│   ├── bologna.webp         # Imagen de Bologna
│   ├── comida.webp          # Imagen de gastronomía
│   ├── excursiones.webp     # Imagen de Venecia/excursiones
│   ├── favicon.svg          # Favicon del sitio
│   ├── hero-video.mp4       # Video de fondo para el Hero
│   ├── logo.png             # Logo oficial en alta resolución
│   ├── logo.svg             # Logo vectorial antiguo
│   ├── roma.webp            # Imagen del Coliseo / Roma
│   └── sofia.webp           # Imagen de la coordinadora Sofía Spagnuolo
├── original/                # Respaldos y código original del cliente
│   └── code.html
├── README.md                # Esta guía de documentación
├── index.html               # Estructura principal y estilos integrados
├── script.js                # Lógica de interacciones, shader WebGL y WhatsApp
├── styles.css               # Estilos globales y diseño responsivo
├── task.md                  # Registro interno de tareas del proyecto
└── walkthrough.md           # Resumen detallado de actualizaciones y refactorización
```

---

## 🚀 Cómo Ejecutar el Proyecto Localmente

Al ser un desarrollo web estático frontend puro, no requiere compiladores ni bases de datos. Sin embargo, para que las fuentes externas y las imágenes locales carguen correctamente mediante peticiones del navegador, se recomienda servir el proyecto desde un servidor web local:

### Opción 1: Usando Node.js / npx (Recomendado)
Ejecuta el siguiente comando en la raíz del proyecto para iniciar un servidor ultraligero:
```bash
npx -y http-server -p 8080
```
Luego abre tu navegador en: [http://localhost:8080](http://localhost:8080)

### Opción 2: Usando Python
Si tienes Python instalado, puedes ejecutar:
```bash
python -m http.server 8080
```
Luego abre tu navegador en: [http://localhost:8080](http://localhost:8080)

### Opción 3: Live Server (Extensiones de VS Code)
Si utilizas Visual Studio Code, simplemente haz clic derecho en `index.html` y selecciona **"Open with Live Server"**.

---

## 🛠️ Tecnologías Utilizadas

*   **HTML5** (Semántica óptima para SEO)
*   **Vanilla CSS3** (Flexbox, CSS Grid y Media Queries avanzadas)
*   **Vanilla JavaScript** (Carga asíncrona, WebGL Shader Context, control de formularios)
*   **WebGL (GLSL)** (Animación fluida de la portada en GPU)
*   **Google Fonts** (Familia tipográfica *Poppins* y *Material Icons*)

---

## 📝 Notas de Versión (Actualizaciones Mayo 2027)

1.  Se actualizó el porcentaje de reserva del 50% al **10%** en todas las secciones y FAQs.
2.  Se cambiaron todas las referencias de Verónica a la nueva coordinadora y CEO, **Sofía Spagnuolo**.
3.  Se integró la nueva **excursión opcional de Cinque Terre** por un valor de **USD 500** con itinerario de día completo detallado.
4.  Se eliminó el sistema de pestañas del itinerario para mostrar las tres etapas del viaje de corrido, alternando el orden visual de imágenes para mejorar la experiencia de lectura.
5.  Se integró el logo oficial `.png` de la marca ajustando las proporciones reales para evitar distorsiones.
