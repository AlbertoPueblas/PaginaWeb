# 🎮 Página Web de Videojuegos

Página web dedicada al mundo de los videojuegos, desarrollada como proyecto web utilizando **HTML5 y CSS3**, con apoyo de **Bootstrap 5.3.8** para algunos elementos de diseño.

El proyecto presenta diferentes videojuegos, información técnica de cada uno y páginas organizadas según la plataforma.

## 📋 Descripción

La página principal muestra una colección de videojuegos mediante tarjetas. Cada tarjeta incluye:

- Imagen del videojuego.
- Nombre del videojuego.
- Ficha técnica.
- Fecha de lanzamiento.
- Plataformas disponibles.
- Tamaño aproximado.
- Información sobre el multijugador.
- Precio.

La web también dispone de una barra de navegación desde la que se puede acceder a diferentes secciones.

## 🌐 Secciones

La página está organizada en las siguientes secciones:

### 🏠 Inicio

Página principal del proyecto.

En ella se muestran diferentes videojuegos mediante tarjetas:

- Grand Theft Auto VI
- Forza Horizon 6
- Battlefield 6
- Dune Awakening
- Resonance: A Plague Tale Legacy
- Clair Obscur: Expedition 33
- Forza Motorsport

Las tarjetas muestran la imagen del juego y su información correspondiente.

### 🎮 Plataformas

La web dispone de páginas específicas para diferentes plataformas:

- **PlayStation**
- **Xbox**
- **PC**

Estas secciones permiten organizar el contenido según la plataforma.

### 📰 Novedades

Sección destinada a noticias y novedades relacionadas con el mundo de los videojuegos y las futuras generaciones de consolas.

Actualmente incluye contenido relacionado con las próximas generaciones de hardware y la evolución de las consolas.

## 🛠️ Tecnologías utilizadas

### HTML5

Utilizado para crear la estructura y el contenido de las diferentes páginas.

### CSS3

Utilizado para:

- Diseño de las tarjetas.
- Colores.
- Fondos.
- Distribución de los elementos.
- Bordes y formas.
- Efectos al pasar el cursor.
- Posicionamiento de elementos.
- Diseño de las diferentes secciones.

### Bootstrap 5.3.8

Se utiliza principalmente para algunos componentes y estilos de la interfaz, especialmente los botones y elementos de navegación.

## 📁 Estructura del proyecto

```text
PaginaWeb/
│
├── Inicio/
│   ├── index.html
│   │
│   ├── css/
│   │   └── index.css
│   │
│   ├── img/
│   │   ├── bf.webp
│   │   ├── dune.jpg
│   │   ├── expedition.avif
│   │   ├── favicon.png
│   │   ├── Fondo.png
│   │   ├── ForzaHorizon6.jpg
│   │   ├── forzaMotorsport.jpg
│   │   ├── gtaVI.jpg
│   │   ├── LogoA.png
│   │   ├── pc.jpg
│   │   ├── ps5.jpg
│   │   ├── ps5.png
│   │   ├── resonance.webp
│   │   ├── xbox25.jpg
│   │   └── xboxXxX.jpg
│   │
│   └── juegos/
│       ├── proximos.html
│       │
│       └── plataformas/
│           ├── pc.html
│           ├── playstation.html
│           └── xbox.html
│
└── README.md
```

## 🎨 Diseño

La página utiliza un fondo personalizado y un sistema de tarjetas para presentar los videojuegos.

Las tarjetas tienen un tamaño fijo y utilizan imágenes adaptadas mediante:

```css
object-fit: cover;
```

Esto permite mantener las proporciones de las tarjetas aunque las imágenes originales tengan diferentes dimensiones.

La distribución de las tarjetas se realiza mediante **Flexbox**:

```css
.contenedor {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}
```

De esta forma, las tarjetas se reorganizan automáticamente cuando cambia el tamaño de la pantalla.

## 🃏 Fichas técnicas

Las tarjetas incorporan información adicional sobre cada videojuego.

Mediante CSS se puede mostrar una ficha técnica al interactuar con la tarjeta:

```css
.carta:hover span {
    display: block;
}
```

La información se coloca sobre la tarjeta utilizando posicionamiento absoluto:

```css
position: absolute;
```

Esto permite mantener las dimensiones de la tarjeta y mostrar la información sin desplazar los demás elementos.

## 🧭 Navegación

La navegación principal permite acceder rápidamente a:

```text
Inicio
│
├── PS5
├── Xbox
├── PC
└── Novedades
```

Todas las páginas comparten la hoja de estilos principal para mantener una apariencia común.

## 🚀 Cómo ejecutar el proyecto

No es necesario instalar ningún servidor ni dependencia.

### 1. Descargar o clonar el repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
```

### 2. Abrir el proyecto

Entrar en la carpeta:

```text
PaginaWeb/Inicio/
```

### 3. Abrir `index.html`

Se puede abrir directamente con cualquier navegador moderno.

También se puede utilizar **Visual Studio Code** junto con la extensión **Live Server** para visualizar los cambios en tiempo real.

## 📌 Estado del proyecto

El proyecto se encuentra en desarrollo.

Actualmente incluye:

- [x] Página principal
- [x] Barra de navegación
- [x] Tarjetas de videojuegos
- [x] Fichas técnicas
- [x] Página de PlayStation
- [x] Página de Xbox
- [x] Página de PC
- [x] Sección de novedades
- [x] Diseño responsive mediante Flexbox
- [x] Bootstrap
- [ ] Ampliar catálogo de videojuegos
- [ ] Añadir más información a las fichas
- [ ] Mejorar la adaptación a dispositivos móviles
- [ ] Añadir nuevas secciones

## 📚 Objetivo del proyecto

El objetivo del proyecto es poner en práctica los conocimientos adquiridos en desarrollo web mediante la creación de una página web temática sobre videojuegos.

Se trabajan conceptos como:

- Estructura HTML.
- Selectores CSS.
- Flexbox.
- Posicionamiento.
- Pseudoclases como `:hover`.
- Diseño de tarjetas.
- Enlaces entre páginas.
- Organización de archivos.
- Uso de imágenes.
- Integración de Bootstrap.

## 👨‍💻 Autor

**Alberto Pueblas**

Proyecto realizado como práctica de desarrollo web.