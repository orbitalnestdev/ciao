# Resumen de Actualizaciones y Refactorización (Mayo 2027)

Se han integrado con éxito las especificaciones del cliente sobre el diseño de producción de **CIAO Idiomas**.

## Cambios Realizados

1. **Reversión del Hero a Fondo Animado (Shader WebGL)**:
   - Se restauró el fondo del Hero al diseño original con la animación del shader de WebGL en el canvas (`#hero-canvas`).

2. **Formulario de Contacto Funcional con WhatsApp**:
   - Se configuró el botón "Enviar solicitud de entrevista" para que lea dinámicamente los campos ingresados (Nombre completo, Teléfono, Email y Mensaje).
   - Al hacer clic en enviar, se pre-completa un mensaje estructurado y se redirige automáticamente al WhatsApp de viajes: **+54 9 11 2408-1777** (`https://wa.me/5491124081777`), mejorando drásticamente la utilidad de la landing page.

3. **Sección de FAQs Expandida y Corregida**:
   - **Nuevas Preguntas**: Se sumaron 3 preguntas recurrentes:
     - *¿Puedo ir en habitación single en Roma?* (Respuesta: *"Sí, podemos cotizar una habitación single en Roma sin problema."*)
     - *¿Está incluida la asistencia al viajero?* (Respuesta: *"No, no está incluida la asistencia al viajero. Podés gestionarla con nosotros o también aparte. Es obligatoria."*)
     - *¿Es la única fecha que tienen disponible?* (Respuesta: Contiene un enlace para consultar otras fechas directamente por WhatsApp).
   - **Corrección de Respuestas**:
     - *¿Cómo son los grupos?*: Se actualizó el límite a **máximo 20 personas**.
     - *¿Puedo pagar en cuotas?*: Se reescribió a: *"La reserva es con el 10% y luego armamos un plan de pagos según como te quede cómodo."*

4. **Actualización de Condiciones y Métodos de Pago**:
   - **Nota de pago al pie**: Se expandió el texto bajo los medios de pago para indicar: *"Reserva 10% · Cuotas a tu medida · Todo el saldo abonado antes de partir. En efectivo o transferencia puede ser en dólares o en pesos argentinos al tipo de cambio del día."*
   - **CSS**: Se incrementó el `max-width` de la clase `.payment-note` a `28rem` en `styles.css`.

5. **Actualizaciones en los Paquetes (Medio y Full)**:
   - **Fechas**: Se añadieron las fechas de viaje al encabezado de las tarjetas de ambos paquetes (*"del 14 al 31 de mayo 2027"*).
   - **Hospedaje y Desayuno**: Se especificó la modalidad de alojamiento (*"Single en Bologna y Doble en Roma"*) y que se incluye *"desayuno buffet"*.
   - **Botón de Consulta Single**: Se incorporó un botón discreto (*"Consultar por paquete single en Roma"*) que redirige a WhatsApp con un mensaje preestablecido.
   - **Actividades**: Se sumó el ítem de *"Actividades de integración cultural y culinarias"*.
   - **Asistencia al Viajero**: Se marcó explícitamente como excluido (*"Asistencia al viajero (no incluida)"*) con un ícono de cierre rojo.

6. **Renombrado de Guía y CEO (Sofía Spagnuolo)**:
   - Se cambiaron todas las referencias del nombre **Verónica** a **Sofía** a lo largo del sitio, y el asset de la imagen a `assets/sofia.webp`.
   - Se corrigió la fecha del viaje de estudio de *2026* a *2027* en la descripción del formulario de contacto.

7. **Fechas del Viaje (Mayo 2027)**:
   - Se modificaron las menciones temporales a **Mayo 2027** en todo el sitio.
   - **Paso 04**: Se actualizó el texto descriptivo a *"Del 14 al 31 de mayo de 2027, salida desde Buenos Aires. Volvés el 31, con certificación oficial Dante Alighieri."*

8. **Modificación de la Seña de Reserva (10%)**:
   - Se actualizaron todas las referencias al pago de la reserva del **50% al 10%** (Paso 02, precios de paquetes Medio y Full, nota de pago al pie y respuestas de FAQs).

9. **Integración Completa con WhatsApp**:
   - Los botones de reserva ("Reservar mi entrevista", "Reservar entrevista") y el botón flotante se dirigen al número de WhatsApp de viajes: **+54 9 11 2408-1777** (`https://wa.me/5491124081777`).

10. **Enlace al Calendario/Itinerario en PDF**:
    - Los botones de consulta del itinerario enlazan al documento de Google Drive del calendario de Mayo 2027: [Ver PDF en Drive](https://drive.google.com/file/d/15FLo937d_eLY3hP826VzS_62QMRxGX59/view?usp=drive_link).

11. **Rediseño Completo del Itinerario (Sin Pestañas/Botones)**:
    - Se eliminaron los botones de pestañas en la sección del itinerario. Ahora todo el itinerario (Bologna, Excursiones y Roma) se muestra de corrido de forma vertical y responsiva.
    - Se alternó el orden del panel central (Excursiones) en pantallas grandes, de forma que en pantallas de escritorio muestra la imagen a la izquierda y el texto a la derecha para un ritmo visual más dinámico.
    - Se unificó y centró el botón de descarga del itinerario al final de toda la sección.

12. **Ampliación de Detalles del Curso y Público Objetivo**:
    - Se actualizó el Hero con una descripción concisa pero rica en detalles del curso (2 semanas, todos los niveles) y el target demográfico (viajeras/os de todas las edades sin límite).
    - Se añadieron preguntas frecuentes adicionales para especificar el funcionamiento del curso intensivo en la Dante Alighieri y la naturaleza inclusiva/multigeneracional del grupo.

13. **Auditoría Estética y Alineación Visual de Encabezados**:
    - Se realizó una auditoría estética completa del sitio para unificar el estilo visual de los encabezados principales (`h2`).
    - Se estandarizó el uso de etiquetas `<span class="italic">` para resaltar las palabras clave finales en cada título.
    - Se configuraron los colores de énfasis de manera consistente en la hoja de estilos: verde primario (`var(--primary)`) en las secciones de Sofía y Valen, violeta oscuro (`var(--dark-violet)`) en Consejos Prácticos, Convivencia y FAQ, unificando toda la identidad visual del sitio.

14. **Nueva Sección Exclusiva: Cinque Terre con CIAO**:
    - Se incorporó una sección dedicada para la excursión opcional a Cinque Terre por un valor de USD 500.
    - Se detallaron todos los servicios incluidos (traslado privado, visita guiada con desayuno, paseo en barco privado con prosecco, almuerzo gourmet en Ristorante Dau Cila, aperitivo en terraza privada y traslado en tren regional).
    - Se esquematizó un cronograma completo paso a paso (desde las 06:00 AM hasta las 22:00 PM) para guiar al usuario en la experiencia del día.
    - Se añadió un botón de reserva enlazando directamente a WhatsApp con un mensaje pre-completado.

15. **Corrección de Espaciado, Desbordamiento y Superposición en el Itinerario**:
    - Se solucionó el problema de desbordamiento de las cajas de fecha en la sección de excursiones, acortando los valores a "Ven." y "Flor." e integrando el nombre de las ciudades directamente en el título de las tarjetas de día.
    - Se agregaron estilos de anulación consolidados en el bloque de cabecera de `index.html` para asegurar que las secciones del itinerario tengan un espacio de separación óptimo (`gap: 7rem`), una altura de imagen más proporcionada (`height: 420px`) y un mayor espacio de respiro entre columnas (`gap: 4rem`), resolviendo cualquier conflicto de caché con la hoja de estilos externa.
    - **Solución de Contraste de Textos**: Se corrigió el error por el cual las palabras destacadas en cursiva (ej. *"la dotta"*, *"tres mundos"*, *"caput mundi"*) resultaban invisibles al coincidir su color con el fondo violeta de la sección. Ahora se colorean con amarillo/lima (`var(--secondary)`), garantizando un contraste óptimo y un diseño muy llamativo.

16. **Integración del Logo Real**:
    - Se descargó el logo oficial de CIAO y se guardó en `assets/logo.png`.
    - Se actualizaron las referencias del logo tanto en la cabecera (navbar) como en el pie de página (footer) para usar la versión oficial `.png`.

17. **Documentación del Proyecto (README.md)**:
    - Se creó un archivo `README.md` profesional y detallado en la raíz del proyecto para resumir las características principales, la estructura de archivos y las instrucciones rápidas de ejecución local.

18. **Video de Presentación de Sofía**:
    - Se actualizó el video de la sección de la fundadora (Sofi) con su presentación real de YouTube Shorts (`Ur4a0TXZEiA`).

19. **Integración del Video de Fondo Local (Hero)**:
    - Se reemplazó el reproductor de YouTube de fondo (`00GVjWG5hd0` - el cual se encontraba no disponible) por el archivo de video local `assets/hero-video.mp4` mediante la etiqueta nativa `<video>` de HTML5.
    - Se configuraron los atributos de reproducción automática, bucle y silencio nativos (`autoplay loop muted playsinline`).
    - Esto elimina por completo la dependencia del servicio de YouTube para el fondo de la portada y erradica definitivamente el problema de la visualización de controles de reproducción.

20. **Actualización de la Paleta de Colores**:
    - Se modificaron las variables globales `:root` en `styles.css` para aplicar la nueva identidad de marca: Carbón oscuro (`#333333`), Lavanda/Lila (`#7c72ab`), Verde Lima suave (`#e6ffc7`) y Blanco grisáceo (`#f4f4f4`).
    - Se actualizaron las variables de color RGB normalizadas en el shader WebGL de la portada (`script.js`) para sincronizar la animación fluida del fondo con la nueva gama cromática.
    - Se actualizó el degradado del contenedor de video de Cinque Terre para armonizar con los nuevos colores de la paleta.
    - **Solución de Caché del Navegador (Cache-Busting)**: Para evitar que el navegador use copias en caché de `styles.css` y `script.js` ignorando la nueva paleta, se agregaron parámetros de versión (`?v=2.1`) a sus enlaces de importación en `index.html`, forzando la recarga inmediata de los nuevos estilos y colores del shader.




21. **Personalización y Ajuste de Fondos de Secciones**:
    - **Sección de Paquetes en Oscuro**: A pedido del cliente, se mantuvo el fondo oscuro original (Carbón `#333333`) para la sección de Paquetes ("Dos paquetes, una misma experiencia").
    - **Sección de Itinerario en Violeta**: A pedido del cliente, la sección del Itinerario se configuró con el fondo de color **Violeta/Lavanda (`#7c72ab`)** y textos en blanco. Las tarjetas diarias se mantuvieron en fondo blanco con texto carbón.
    - **Rediseño y Proporciones de Badges de Fecha**: Se solucionó el problema de estrechez y aplastamiento de los badges de día de las tarjetas de itinerario (Bologna y Roma). Se les otorgaron dimensiones fijas cuadradas (`5.5rem` x `5.5rem`), bordes redondeados y centrado mediante Flexbox, aplicando fondo **Violeta/Lavanda (`#7c72ab`)**, textos de valor en blanco y etiquetas ("GIORNO") en verde lima para un contraste y legibilidad excelentes.
    - **Tono Verde Lima Oscuro Contrastado para Títulos (`#AABF4A`)**: Se identificó que las palabras destacadas en cursiva dentro de los títulos generales `h2` (como "Conocé nuestras *modalidades*" o "Preguntas *frecuentes*") se pintaban con el verde lima de marca muy claro (`#e6ffc7`), haciéndolas invisibles sobre fondos claros. Se configuró un tono verde oliva/lima más oscuro y de alta legibilidad (**`#AABF4A`**) para todos los destaques de títulos en secciones claras.
    - **Sección del Aval Académico en Verde**: A pedido del cliente, la sección de la Società Dante Alighieri se vistió con fondo **Verde Lima suave (`#e6ffc7`)**, textos en carbón oscuro y destaques/estadísticas en lavanda.
    - **Sección de Convivencia en Verde**: A pedido del cliente, la sección de Convivencia se vistió con fondo **Verde Lima suave (`#e6ffc7`)**, textos en carbón oscuro y destaques en lavanda, con tarjetas blancas de bordes suaves y una tarjeta final de CTA en color lavanda sólido.
    - **Sección de Cinque Terre en Violeta**: A pedido del cliente, la sección de Cinque Terre se vistió con fondo **Violeta/Lavanda (`#7c72ab`)**, textos en blanco y destaques en verde lima. Las tarjetas y cronogramas se presentan en blanco puro.
    - **Solución de Contraste en Inclusiones y Cronograma de Cinque Terre**: Se corrigió el color de las etiquetas de hora (ej: "06:00 AM") y líneas divisorias que resultaban invisibles al renderizarse en verde lima sobre fondo blanco. Además, se solucionó el problema por el cual los títulos destacados en negrita (`strong`) tanto de la tarjeta de "Qué incluye la experiencia" (ej. "Visita guiada con desayuno") como del cronograma (ej. "Recogida por hotel") quedaban invisibles debido al estilo heredado de color blanco sobre las tarjetas blancas. Ahora se colorean en **Carbón Oscuro (`#333333`)**, garantizando legibilidad total.
    - **Sección de Contacto (Empezá tu viaje) en Violeta**: A pedido del cliente, la sección de contacto se vistió con fondo **Violeta/Lavanda (`#7c72ab`)** y textos en blanco, con la tarjeta de formulario en blanco puro.
    - **Barra de Estadísticas (Stats Strip) en Violeta**: A pedido del cliente, la franja de datos estadísticos situada debajo del Hero (que detalla los días, ciudades, semanas y meses del viaje) se configuró con fondo **Violeta/Lavanda (`#7c72ab`)**, valores en color verde lima y etiquetas en blanco translúcido, logrando una estética sumamente premium e integrada.
    - **Logo del Footer Oficial en Colores**: Se removieron los filtros de escala de grises y opacidad en el logo del pie de página (footer) para que se renderice con los mismos colores reales y brillo de la marca (Lila y Verde) que el logo del header.

22. **Restauración del Video del Hero de Alta Calidad (YouTube)**:
    - Se reinstauró la carga del video de portada original directamente desde YouTube (`00GVjWG5hd0`), el cual cuenta con resolución en alta definición (HD) y colores premium, superando en calidad de imagen al archivo comprimido local.
    - **Bloqueo Total de Clics y Taps**: Se elevó el nivel de la capa `.hero-overlay` con `z-index: 3 !important` y `pointer-events: auto !important` para bloquear definitivamente cualquier interacción física del usuario con el reproductor de YouTube, impidiendo que aparezcan los controles de pausa o adelanto nativos en móviles o escritorio.
    - Se aumentaron el brillo y la transparencia a **`0.8`** (`opacity: 0.8 !important; filter: brightness(0.8) !important`) para que el video luzca luminoso, vibrante y premium, manteniendo una perfecta lectura del texto mediante sombras de texto integradas.


## Estructura Final del Entregable
La raíz del proyecto cuenta únicamente con los archivos necesarios para su distribución directa:
```text
ciao/
├── assets/
│   ├── bologna.webp
│   ├── comida.webp
│   ├── excursiones.webp
│   ├── favicon.svg
│   ├── hero-video.mp4
│   ├── logo.png
│   ├── logo.svg
│   ├── roma.webp
│   └── sofia.webp
├── original/
│   └── code.html
├── index.html
├── README.md
├── script.js
└── styles.css
```
