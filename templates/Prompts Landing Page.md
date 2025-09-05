

### 1) Landing simple “Promoción del día”

**Prompt para Copilot:**  
Crea un `index.html` con una landing responsive para “Promoción del día” de un restaurante. Incluye: hero con título, subtítulo y botón “Ordenar ahora”; sección de 3 beneficios con íconos; carrusel simple de 3 platillos; footer con aviso de privacidad. Estilo limpio (fondos claros, acentos azules), tipografía sans. Accesible (contraste AA, etiquetas ARIA). JS: carrusel auto y manual. Sin frameworks, todo en un archivo.

### 2) Menú interactivo con filtro

**Prompt:**  
Genera un menú de alimentos con tarjetas (imagen, nombre, precio, botón “Agregar”). Barra de búsqueda y filtros por categoría (Desayuno, Comida, Bebidas). Contador de ítems en carrito (badge en navbar). CSS con grid/fluid, hover suave, sombras sutiles. JS: filtrar en vivo, agregar al carrito y total parcial. Un solo `index.html`.

### 3) Mini checkout (carrito + resumen)

**Prompt:**  
Construye una UI de mini checkout: lista de artículos (nombre, cantidad +/−, precio), cupones (input + “Aplicar”), método de pago (radio), botón “Pagar”. Muestra subtotal, descuento y total. Validaciones básicas y manejo de estados vacíos. Diseño claro, accesible y mobile-first. Todo en un `index.html`.

### 4) Reservación rápida (widget)

**Prompt:**  
Crea un widget de reservación con campos: sucursal (dropdown), fecha, hora, personas (stepper), nombre y teléfono. Valida requeridos y formatos, muestra mensajes de éxito/error, y preven dupes (mismo nombre+hora). Calendario mínimo con JS nativo. Estilo corporativo sobrio. Un solo archivo.

### 5) Rastreador de pedido (tracking)

**Prompt:**  
Diseña un rastreador visual con 4 etapas: Recibido → En preparación → En ruta → Entregado. Barra de progreso con animación, y “ETA estimada”. Input para “Número de pedido” que simula estados aleatorios. Accesible con `aria-current`. Sin frameworks, todo inline.

### 6) Tablero de lealtad (puntos)

**Prompt:**  
UI para “Mi cuenta”: tarjetas con puntos actuales, nivel (Bronce/Plata/Oro), y beneficios. Lista de movimientos (tabla responsive). Botón “Canjear puntos” abre modal con opciones. Colores neutros, acentos azules, íconos simples (emoji ok). JS: simula canje restando puntos.

### 7) Encuesta de satisfacción (kiosk)

**Prompt:**  
Pantalla a pantalla completa con 3 caritas (mala/neutral/buena), textarea opcional y botón “Enviar”. Después de enviar, pantalla de “¡Gracias!” con confeti ligero (CSS/JS). Accesible (teclado/lectores). Estilo minimal. Un archivo.

### 8) Formulario de contacto con validación UX

**Prompt:**  
Formulario: nombre, email, motivo (select), mensaje. Validación: on-blur y on-submit con mensajes claros, borde rojo/verde, y resumen de errores arriba (ARIA live). Botón “Enviar” deshabilitado hasta que todo sea válido. Estética limpia, responsive. Todo en `index.html`.

### 9) Localizador de sucursales (mock)

**Prompt:**  
Cuadro de búsqueda por colonia/CP; lista de sucursales (nombre, dirección, horario, botón “Cómo llegar”). Sin mapas reales: coloca un recuadro “Mapa” estilizado. Filtro en vivo y orden por cercanía simulada. Tarjetas con shadow suave y layout de 2 columnas en desktop.

### 10) Pantalla de turnos (operaciones)

**Prompt:**  
Dashboard simple para staff: tabla de turnos (nombre, rol, hora inicio/fin), filtro por rol, botón “Intercambiar” que abre modal para proponer swap (solo UI). Estados vacíos, loading skeleton, y toasts de confirmación. Diseño sobrio, accesible. Un archivo.

### 11) Generador de banner de promoción

**Prompt:**  
UI con formulario: título, subtítulo, porcentaje de descuento, y color de acento. Previsualiza un banner responsive con esas variables (tipografía grande, CTA). Botón “Descargar PNG” usando `canvas` (implementa export). Estilo corporativo, sombras sutiles.

### 12) Galería de platillos con modal

**Prompt:**  
Cuadrícula de 6 imágenes de comida (placeholders). Al hacer clic, abre modal con imagen grande, nombre, descripción corta y botón “Agregar”. Teclas ← → para navegar, Esc para cerrar. En mobile, carrusel táctil. CSS grid, transiciones suaves.

### 13) Barra de navegación sticky + sección anclada

**Prompt:**  
Navbar sticky con logo (texto), links ancla a secciones: Inicio, Menú, Sucursales, Contacto. Scroll suave, resalta link activo (scrollspy). Hero, sección menú (3 cards), sucursales (lista), contacto (form). Sombras ligeras, fondo claro, accesible. Un archivo.

### 14) Contador de ofertas del día (timer)

**Prompt:**  
Sección “Oferta termina en:” con cuenta regresiva (hh:mm:ss) hasta las 23:59 del día actual. Al llegar a cero, cambia a “Nueva oferta mañana” y desactiva botón “Aprovechar”. Estética limpia, números grandes, contraste alto. JS sin librerías.

### 15) Lista de tareas operativas (to-do con estados)

**Prompt:**  
To-do para staff: input para nueva tarea, lista con check para completar, botón de eliminar y filtro (todas/pendientes/completas). Persiste en `localStorage`. Estilos con chips y badges; estados vacíos y microinteracciones (focus/hover).

---

#### Tips rápidos para el curso

- Pídele a Copilot **“todo en un solo `index.html` con `<style>` y `<script>`”** para acelerar la demo.
    
- Incluye en el prompt **accesibilidad (WAI-ARIA, contraste AA)** y **mobile-first** para elevar la calidad.
    
- Si quieres variaciones: agrega “dame 2 variantes de estilos” o “haz versión oscura/clara”.
    

