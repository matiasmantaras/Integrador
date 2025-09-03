# Premium Store

Un sitio web de e-commerce moderno y elegante desarrollado con HTML, CSS y JavaScript.

## Descripción del Proyecto

Premium Store es una tienda en línea que ofrece productos de alta calidad con un diseño minimalista y moderno. El sitio incluye:

- **Página de inicio** con productos destacados
- **Catálogo de productos** en formato de tarjetas y tabla
- **Página de producto individual** con detalles completos
- **Sistema de compra** con carrito de compras
- **Página de login** para usuarios
- **Diseño responsive** compatible con dispositivos móviles

## Estructura del Proyecto

```
integrador/
├── pages/           # Páginas HTML
│   ├── index.html
│   ├── listado_box.html
│   ├── listado_tabla.html
│   ├── producto.html
│   ├── comprar.html
│   └── login.html
├── styles/          # Archivos CSS
│   ├── home.css
│   ├── style.css
│   ├── listado.css
│   ├── producto.css
│   └── comprar.css
├── assets/          # Recursos estáticos
│   └── img/         # Imágenes SVG
│       ├── auriculares.svg
│       ├── reloj.svg
│       ├── zapatillas.svg
│       ├── gafas.svg
│       ├── mochila.svg
│       └── camara.svg
└── README.md
```

## Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y animaciones
- **JavaScript** - Interactividad
- **Tailwind CSS** - Framework CSS utility-first
- **Font Awesome** - Iconografía
- **SVG** - Imágenes vectoriales escalables

## Cómo Ejecutar el Proyecto

### Opción 1: Servidor HTTP con Python

1. Abre una terminal en la carpeta raíz del proyecto
2. Ejecuta el siguiente comando:
   ```bash
   python -m http.server 8000
   ```
3. Abre tu navegador y ve a: `http://localhost:8000/pages/index.html`

### Opción 2: Servidor HTTP con Node.js

1. Instala http-server globalmente:
   ```bash
   npm install -g http-server
   ```
2. En la carpeta raíz del proyecto, ejecuta:
   ```bash
   http-server
   ```
3. Abre tu navegador y ve a la URL mostrada en la terminal

### Opción 3: Extensión Live Server (VS Code)

1. Instala la extensión "Live Server" en VS Code
2. Haz clic derecho en `pages/index.html`
3. Selecciona "Open with Live Server"

## Características Principales

- ✅ Diseño responsive y moderno
- ✅ Navegación intuitiva entre páginas
- ✅ Carrito de compras funcional
- ✅ Imágenes SVG optimizadas
- ✅ Efectos hover y transiciones suaves
- ✅ Estructura de carpetas escalable
- ✅ Código limpio y bien organizado

## Navegación del Sitio

- **Inicio**: Página principal con productos destacados
- **Productos**: Vista en tarjetas de todos los productos
- **Catálogo**: Vista en tabla con más detalles
- **Producto**: Página individual de producto
- **Comprar**: Proceso de compra y carrito
- **Login**: Autenticación de usuarios

---

*Desarrollado como proyecto integrador de paradigmas de programación*