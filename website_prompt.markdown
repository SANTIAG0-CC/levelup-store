# Prompt para la Creación de la Página Web de LevelUp Store

## Descripción General
Crear una página web para **LevelUp Store**, una tienda en línea de juegos digitales para PC, PlayStation, Xbox y Nintendo Switch. La página debe ser moderna, responsiva y optimizada para una experiencia de usuario fluida, con un diseño atractivo que refleje una tienda digital profesional. El sitio debe incluir secciones para inicio, juegos, ofertas, novedades, carrito, inicio de sesión, soporte y pie de página con información adicional.

## Requerimientos Específicos

### 1. Tecnologías
- **HTML5** y **CSS3** para la estructura y el diseño.
- **JavaScript** para interacciones dinámicas (por ejemplo, búsqueda, filtros, carrito).
- **Framework CSS** (opcional, como Tailwind CSS o Bootstrap) para acelerar el desarrollo y garantizar responsividad.
- **CDN** para cargar recursos externos (por ejemplo, íconos o fuentes).
- Diseñar para ser **responsivo** en dispositivos móviles, tabletas y escritorios.
- Usar **React** o **JSX** si se requiere un enfoque basado en componentes (opcional, pero preferible para escalabilidad).

### 2. Estructura de la Página

#### Encabezado (Header)
- **Logotipo**: "LevelUp Store" en la esquina superior izquierda, clickable hacia la página de inicio.
- **Barra de búsqueda**: Campo de texto con un botón/icono de búsqueda.
- **Navegación principal**:
  - Enlaces a: Inicio, Juegos (con submenú para PC, PlayStation 5, Xbox Series X, Nintendo Switch), Ofertas, Novedades, Top Ventas, Soporte.
  - Submenú desplegable para "Juegos" con las plataformas mencionadas.
- **Botones de usuario**:
  - "Iniciar Sesión" (enlace a la página de login).
  - "Carrito" con un contador dinámico (inicialmente "0").

#### Sección Principal (Inicio)
- **Banner principal**:
  - Texto destacado: "Los mejores juegos digitales al mejor precio".
  - Subtexto: "Descubre ofertas exclusivas en miles de juegos para PC, PlayStation, Xbox y Nintendo Switch. Entrega instantánea y soporte 24/7."
  - Botón: "Ver Ofertas Especiales" (enlace a la sección de ofertas).
- **Estadísticas**:
  - Cuatro bloques con íconos y texto:
    - "10,000+ Juegos Disponibles"
    - "500,000+ Clientes Satisfechos"
    - "24/7 Soporte al Cliente"
    - "95% Descuentos Exclusivos"
- **Categorías**:
  - Cuatro tarjetas con imágenes y texto para las plataformas: PC, PlayStation, Xbox, Nintendo.
- **Oferta destacada**:
  - Banner con texto: "¡Oferta de Verano! Hasta 70% de descuento en juegos seleccionados. Oferta válida hasta agotar existencias."
  - Botón: "Ver Ofertas".
- **Secciones de juegos**:
  - "Juegos Destacados" con enlace "Ver todos".
  - "Ofertas Especiales" con enlace "Ver todas".
  - "Últimos Lanzamientos" con enlace "Ver todos".
  - Cada sección debe mostrar una lista de juegos (puede ser un placeholder con tarjetas de juegos).

#### Página de Juegos
- **Ruta**: `/juegos`
- **Breadcrumb**: Inicio > Juegos
- **Título**: "Todos los Juegos"
- **Filtros**:
  - **Plataforma**: Dropdown o botones con opciones: Todas, PC, PlayStation 5, Xbox Series X, Nintendo Switch.
  - **Ordenar por**: Dropdown con opciones: Nombre, Precio: Menor a Mayor, Precio: Mayor a Menor, Mayor Descuento.
- **Lista de juegos**: Mostrar tarjetas de juegos con imagen, título, precio y posible descuento (placeholder para contenido dinámico).

#### Página de Ofertas
- **Ruta**: `/ofertas`
- **Breadcrumb**: Inicio > Ofertas
- **Título**: "Ofertas Especiales"
- **Contenido**: Lista de juegos en oferta con tarjetas similares a la página de juegos.

#### Página de Novedades
- **Ruta**: `/novedades`
- **Breadcrumb**: Inicio > Novedades
- **Título**: "Últimos Lanzamientos"
- **Contenido**: Lista de juegos nuevos con tarjetas similares a la página de juegos.

#### Página de Carrito
- **Ruta**: `/carrito`
- **Breadcrumb**: Inicio > Carrito
- **Título**: "Tu Carrito de Compras"
- **Contenido**: Lista de juegos añadidos al carrito (inicialmente vacío, con placeholder para contenido dinámico).

#### Página de Iniciar Sesión
- **Ruta**: `/iniciar-sesion`
- **Breadcrumb**: Inicio > Iniciar Sesión
- **Título**: "Iniciar Sesión"
- **Formulario**:
  - Campo de texto: "Correo Electrónico"
  - Campo de contraseña: "Contraseña"
  - Botón: "Iniciar Sesión"
  - Enlaces:
    - "¿Olvidaste tu contraseña?" (enlace a recuperación de contraseña).
    - "¿No tienes cuenta? Regístrate aquí" (enlace a registro).

#### Página de Soporte
- **Ruta**: `/soporte`
- **Breadcrumb**: Inicio > Soporte
- **Título**: "Centro de Soporte"
- **Subtítulo**: "¿Necesitas ayuda?"
- **Descripción**: "Estamos aquí para ayudarte con cualquier problema o pregunta que tengas."
- **Secciones**:
  - **Preguntas Frecuentes**: Enlace a una página o sección de FAQs.
  - **Contacto**: Enlace a un formulario o información de contacto.
  - **Chat en Vivo**: Botón para iniciar un chat en tiempo real.

#### Pie de Página (Footer)
- **Columnas**:
  - **LevelUp Store**:
    - Sobre Nosotros
    - Contacto
    - Trabaja con Nosotros
    - Prensa
  - **Información**:
    - Preguntas Frecuentes
    - Cómo Comprar
    - Métodos de Pago
    - Seguridad
  - **Legal**:
    - Términos y Condiciones
    - Política de Privacidad
    - Política de Cookies
    - Política de Reembolsos
  - **Síguenos**:
    - Enlaces a redes sociales (Twitter, Facebook, Instagram, YouTube) con íconos.
- **Copyright**: "© 2023 LevelUp Store. Todos los derechos reservados."

### 3. Diseño y Estilo
- **Paleta de colores**: Moderna y vibrante (por ejemplo, tonos oscuros con acentos en azul, rojo o verde neón para reflejar la temática gaming).
- **Tipografía**: Fuentes sans-serif modernas (como Roboto, Open Sans o similar).
- **Íconos**: Usar una biblioteca de íconos (como FontAwesome o Material Icons) para botones y redes sociales.
- **Imágenes**: Usar placeholders para portadas de juegos, optimizadas para carga rápida.
- **Responsividad**:
  - Menú hamburguesa en dispositivos móviles.
  - Ajustar el diseño de tarjetas y secciones para pantallas pequeñas.
- **Interacciones**:
  - Hover en enlaces y botones con transiciones suaves.
  - Carrito actualizable dinámicamente.
  - Filtros funcionales para la página de juegos.

### 4. Funcionalidad
- **Búsqueda**: Permitir buscar juegos por nombre o plataforma (puede ser un mockup con resultados simulados).
- **Carrito**: Mostrar el número de ítems en el carrito y permitir añadir/eliminar productos (simulado con JavaScript).
- **Filtros**: Implementar filtros dinámicos en la página de juegos (puede ser un mockup con datos estáticos).
- **Navegación**: Usar rutas relativas para las páginas (por ejemplo, `/juegos`, `/ofertas`).
- **SEO**: Incluir metadatos básicos (título, descripción) para cada página.
- **Accesibilidad**: Usar etiquetas semánticas (`<nav>`, `<main>`, `<footer>`), atributos `alt` en imágenes y compatibilidad con lectores de pantalla.

### 5. Entregables
- Archivo **index.html** con la estructura principal.
- Archivo **styles.css** para los estilos.
- Archivo **script.js** para la lógica de interacción.
- Opcionalmente, un proyecto en **React** con componentes reutilizables si se elige esta tecnología.
- Documentación breve sobre cómo ejecutar y personalizar el sitio.

### 6. Notas Adicionales
- Usar **CDN** para recursos externos (por ejemplo, Tailwind CSS, FontAwesome).
- Asegurar que el sitio sea **rápido** y optimizado (imágenes comprimidas, CSS/JS minificados).
- Incluir comentarios en el código para facilitar el mantenimiento.
- Simular datos dinámicos (como listas de juegos) con placeholders, ya que no se requiere backend.