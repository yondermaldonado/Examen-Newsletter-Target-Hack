# 🌿 EcoMarket — Newsletter

Sitio web informativo y catálogo de productos para **EcoMarket**, una tienda de productos ecológicos, orgánicos y de residuo cero, que incluye un **formulario de suscripción a newsletter** para la comunidad de clientes. El proyecto está construido **únicamente con HTML5 y CSS3**, sin JavaScript.

## ✨ Características

- **Home** (`index.html`): presentación de la empresa, su objetivo, su catálogo y su ética de trabajo.
- **Ofertas** (`views/ofertas.html`): productos en descuento, mostrando precio anterior, precio con oferta, nombre y porcentaje de descuento.
- **Productos** (`views/productos.html`): catálogo general de productos con nombre, precio e imagen.
- **Categorías** (`views/Categorias.html`): navegación por categorías de producto:
  - Aceites (`aceites.html`)
  - Cereales (`cereales.html`)
  - Condimentos (`condimentos.html`)
  - Cuidado personal (`cuidado_personal.html`)
  - Endulzantes (`endulzantes.html`)
  - Frutos secos (`frutos_secos.html`)
  - Harinas (`harinas.html`)
  - Limpieza (`limpieza.html`)
  - Nueces y semillas (`nueces_semillas.html`)
- **Newsletter** (`views/formulario.html`): formulario de suscripción a la comunidad EcoMarket, con nombre, correo electrónico, selección de intereses (todas las novedades, ofertas y descuentos, consejos saludables) y casilla de aceptación de la política de privacidad.
- **Contacto** (`views/contacto.html`): formas de contacto de la empresa (correo, teléfono, ubicación).
- **Comentarios** (`views/comentarios.html`): formulario para dejar nombre, correo, teléfono y comentario, con botón de reinicio y de envío (redirige al Home).
- **Sección de redes sociales**: enlaces a Facebook, Instagram y TikTok de EcoMarket, presente en el pie de página de todo el sitio.
- **Buscador**: campo de búsqueda visible en la barra de navegación (presente en todas las vistas).
- **Diseño responsivo**: la página se adapta a distintos tamaños de pantalla; las animaciones de entrada se desactivan en dispositivos móviles para evitar fallos de visualización.

> ⚠️ Nota: el formulario de newsletter no tiene backend asociado (`action="#"`); al enviarse no se procesa ni almacena la información, solo demuestra la maquetación del formulario.

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura semántica de todas las vistas.
- **CSS3** — estilos organizados en módulos:
  - `main.css` — estilos generales.
  - `layout.css` — estructura y disposición de la página.
  - `components.css` — estilos de componentes reutilizables (tarjetas de producto, formularios, navegación, etc.).
  - `animations.css` — animaciones de entrada, desactivadas en móvil.
- Sin JavaScript ni frameworks: toda la maquetación se resuelve con HTML y CSS puros.

## 📁 Estructura del proyecto

```
Proyecto_html_css/
├── index.html                  # Página principal (Home)
├── css/
│   ├── main.css                # Estilos generales
│   ├── layout.css              # Layout / estructura
│   ├── components.css          # Componentes reutilizables
│   └── animations.css          # Animaciones de entrada
├── views/
│   ├── Categorias.html         # Índice de categorías
│   ├── aceites.html
│   ├── cereales.html
│   ├── condimentos.html
│   ├── cuidado_personal.html
│   ├── endulzantes.html
│   ├── frutos_secos.html
│   ├── harinas.html
│   ├── limpieza.html
│   ├── nueces_semillas.html
│   ├── ofertas.html
│   ├── productos.html
│   ├── contacto.html
│   ├── comentarios.html
│   └── formulario.html         # Formulario de suscripción al newsletter
└── img/                         # Imágenes del sitio y de los productos (img/productos/)
```

## 🚀 Instalación y visualización

Este proyecto es completamente estático (HTML + CSS), no requiere backend ni instalación de dependencias.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/yondermaldonado/Examen-Newsletter-Target-Hack.git
   cd "Examen-Newsletter-Target-Hack/Proyecto_html_css"
   ```

2. Abre `index.html` directamente en tu navegador, o sírvelo con un servidor local (opcional):

   ```bash
   python3 -m http.server 8080
   ```

   y accede a `http://localhost:8080/index.html`.

3. Navega por el sitio usando el menú superior: Home, Ofertas, Productos, Categorías, Contacto, Comentario y Formulario.

## 👤 Autor

Yonder Daniel Maldonado Pabón

## 📄 Licencia

Este proyecto se distribuye con fines educativos. Puedes usarlo y adaptarlo libremente citando la fuente.
