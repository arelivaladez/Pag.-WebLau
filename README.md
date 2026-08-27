# Laura's Boutique 👗

Aplicación web de comercio electrónico con frontend en HTML, CSS y JavaScript, y carrito de compras funcional.

## Descripción

Tienda en línea de ropa y accesorios (vestidos, pantalones, cardigans, vestidos de XV años, ofertas, otoño y más). Incluye una interfaz en HTML conectada a un carrito de compras en JavaScript, con selección de colores y checkout simulado. Generada para poder llevar también un control de inventario.
## Mi participación en el proyecto

Retomé un catálogo ya existente y le agregué las funcionalidades que faltaban para que la tienda fuera realmente usable:
- Conecté el botón de "agregar al carrito" en cada prenda, funcionando en todas las páginas del sitio.
- Implementé la lógica del carrito de compras: cantidades, eliminar producto, total en tiempo real y persistencia entre páginas.
- Agregué la selección de color por prenda antes de agregar al carrito.
- Corregí íconos, imágenes y enlaces rotos del proyecto original.
- Dejé preparada (aunque no activada) la conexión a Firebase para autenticación de usuarios y guardado de pedidos.

## Estado del proyecto

**No está conectado a una base de datos real.** El carrito y los pedidos se guardan únicamente en el navegador de cada usuario (`localStorage`), no en un servidor.

### Limitaciones conocidas
- No tiene conexión a una base de datos real; todo es de manera local.
- El método de pago no está funcional, es una simulación.
- No existe un panel de administrador para ver los pedidos de los clientes.

## Tecnologías utilizadas

- **HTML5** — estructura de la interfaz
- **CSS3** — estilos y diseño
- **JavaScript** — lógica del carrito, colores y autenticación
