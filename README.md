Proyecto LMSGI: Portal de Componentes (IE2UT2)

Descripción del Proyecto:

Se trata de una plataforma web sobre componentes de PC que integra una sección de benchmark, menús de navegación y un sistema de recogida de datos mediante formularios.

---

Especificaciones Técnicas

Ejercicio 1: Estructura HTML5
- Contenedor Global
- Encabezado: Sección "main-header" que integra el título, barra de búsqueda y el carrusel de imágenes.
- Carrusel: Estructura de "carrusel-container" y "carrusel-track" con 3 imágenes de productos (Intel, ASUS, MSI).
- Navegación: Menú principal con efectos de hover.
  - sidebar-left: Menú secundario con enlaces externos (TechPowerUp, Geekbench, etc.) que se abren en nueva pestaña.
- Contenido Semántico: Uso de "<article>" para la noticia principal, un "<iframe>" de YouTube y una sección "<aside>" para el "Componente del mes".
- Pie de Página: Etiqueta "<footer>" con el copyright 2026 y créditos del equipo.

Ejercicio 2: Hojas de Estilo
- Layout Moderno: Uso de "display: flex" para organizar los menús laterales y el contenido central.
- Tipografía: Familia "Segoe UI" / Arial, con tamaño base de 16px. Se aplican variaciones en los porcentajes (90% en contenido)
- Animaciones CSS:
  - Carrusel: Animación "@keyframes slide" de 15 segundos.
  - Interactividad: Transición suave en los enlaces del menú lateral y botones 3D.
- Estética Gaming: Uso de filtros oscuros y sombras para profundidad.

Ejercicio 3: Formulario
- Interacción: Formulario diseñado para captura de datos de usuario con envío vía "POST".
- Campos: Incluye validación de campos obligatorios, selectores de radio, checkboxes y menú desplegable.

---

Flujo de Trabajo

1. Ramas: Uso de "main" para versiones finales y "develop" para el trabajo diario.
2. Sincronización: Comandos git pull al inicio de la sesión y git push al finalizar para evitar conflictos.
3. Mensajes de Commit: Documentación de los cambios realizados.