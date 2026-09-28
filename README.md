# 🎮 Página Web de Videojuegos

Página web dedicada al mundo de los videojuegos, desarrollada utilizando **HTML5 y CSS3**, con apoyo de **Bootstrap 5.3.8**.

## 🔗 Repositorio

El código fuente del proyecto está disponible en GitHub:

[AlbertoPueblas/PaginaWeb en GitHub](https://github.com/AlbertoPueblas/PaginaWeb?utm_source=chatgpt.com)

## 📋 Descripción

La página presenta diferentes videojuegos mediante tarjetas interactivas. Cada tarjeta muestra una imagen y el nombre del videojuego, además de una ficha técnica con información adicional.

Entre la información mostrada se encuentra:

- Fecha de lanzamiento.
- Plataformas disponibles.
- Tamaño aproximado.
- Información sobre el multijugador.
- Precio.

## 🌐 Secciones

La web está organizada en diferentes secciones:

### 🏠 Inicio

Página principal donde se muestran los videojuegos mediante tarjetas.

Actualmente incluye:

- Grand Theft Auto VI
- Forza Horizon 6
- Battlefield 6
- Dune Awakening
- Resonance: A Plague Tale Legacy
- Clair Obscur: Expedition 33
- Forza Motorsport

### 🎮 Plataformas

La página dispone de secciones específicas para:

- **PlayStation 5**
- **Xbox**
- **PC**

### 📰 Novedades

Sección destinada a mostrar información sobre próximos lanzamientos y novedades relacionadas con el mundo de los videojuegos.

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura y contenido.
- **CSS3** — diseño y estilos.
- **Bootstrap 5.3.8** — componentes y estilos adicionales.
- **Git / GitHub** — control de versiones y almacenamiento del proyecto.

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
│   │   └── Imágenes utilizadas en la web
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

La página utiliza un diseño basado en tarjetas para presentar los videojuegos.

Las tarjetas se organizan mediante **Flexbox**, permitiendo que se adapten al espacio disponible:

```css
.contenedor {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}
```

Las imágenes utilizan `object-fit: cover` para mantener una presentación uniforme:

```css
.carta img {
    width: 100%;
    height: 360px;
    object-fit: cover;
}
```

## 🃏 Fichas técnicas

Cada tarjeta puede mostrar información adicional mediante una ficha técnica.

La ficha se posiciona sobre la tarjeta utilizando `position: absolute`, evitando que el contenido desplace las demás tarjetas.

Además, se utilizan pseudoclases CSS para crear la interacción con las tarjetas.

## 🧭 Navegación

La barra de navegación permite acceder a las principales secciones:

```text
Inicio
│
├── PS5
├── Xbox
├── PC
└── Novedades
```

## 🚀 Cómo ejecutar el proyecto

No es necesario instalar ninguna dependencia.

### Opción 1 — Abrir directamente

Abrir el archivo:

```text
Inicio/index.html
```

con un navegador web.

### Opción 2 — Visual Studio Code

Abrir el proyecto con Visual Studio Code y utilizar **Live Server** para visualizar la página y comprobar los cambios en tiempo real.

## 📌 Estado del proyecto

El proyecto se encuentra actualmente en desarrollo.

- [x] Página principal
- [x] Barra de navegación
- [x] Tarjetas de videojuegos
- [x] Fichas técnicas
- [x] Página de PlayStation
- [x] Página de Xbox
- [x] Página de PC
- [x] Sección de novedades
- [x] Diseño mediante Flexbox
- [x] Integración de Bootstrap
- [x] Repositorio en GitHub
- [ ] Ampliar catálogo de videojuegos
- [ ] Añadir más información a las fichas
- [ ] Mejorar la adaptación a dispositivos móviles
- [ ] Añadir nuevas secciones

## 📚 Objetivo

El objetivo del proyecto es poner en práctica los conocimientos de **desarrollo web** mediante la creación de una página temática sobre videojuegos.

Durante el desarrollo se trabajan conceptos como:

- Estructura HTML.
- Selectores CSS.
- Flexbox.
- Posicionamiento.
- Pseudoclases.
- Diseño de tarjetas.
- Enlaces entre páginas.
- Organización de archivos.
- Uso de imágenes.
- Integración de Bootstrap.
- Control de versiones con Git y GitHub.

## 👨‍💻 Autor

**Alberto Pueblas**

Proyecto realizado como práctica de desarrollo web.

---

### 🔗 Enlace al proyecto

[Visitar repositorio en GitHub](https://github.com/AlbertoPueblas/PaginaWeb?)