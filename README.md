# 🎮 Página Web de Videojuegos

Página web dedicada al mundo de los videojuegos, desarrollada como proyecto de desarrollo web utilizando **HTML5, CSS3 y Bootstrap 5**.

El objetivo principal del proyecto es practicar la creación y organización de una página web, trabajando con tarjetas, navegación entre páginas, estilos CSS, imágenes, audio y control de versiones mediante Git y GitHub.

## 🔗 Repositorio

El código fuente del proyecto está disponible en GitHub:

**[AlbertoPueblas/PaginaWeb](https://github.com/AlbertoPueblas/PaginaWeb)**

---

## 📋 Descripción

La página web muestra diferentes videojuegos mediante tarjetas interactivas.

Cada tarjeta contiene:

- 🖼️ Imagen del videojuego.
- 🎮 Nombre del juego.
- 📅 Fecha de lanzamiento.
- 💻 Plataformas disponibles.
- 💾 Tamaño aproximado.
- 👥 Información sobre el multijugador.
- 💰 Precio.
- ▶️ Enlace al tráiler cuando está disponible.
- 📄 Ficha técnica que aparece mediante interacción con la tarjeta.

La página también dispone de una barra de navegación que permite acceder a las diferentes categorías y de un reproductor de audio integrado.

---

## 🌐 Secciones

### 🏠 Inicio

Página principal donde se muestran diferentes videojuegos mediante tarjetas.

Actualmente incluye:

- Grand Theft Auto VI
- Forza Horizon 6
- Battlefield 6
- Dune Awakening
- Resonance: A Plague Tale Legacy
- Clair Obscur: Expedition 33
- Forza Motorsport

### 🎮 Plataformas

La web dispone de páginas específicas para diferentes plataformas:

- **PlayStation 5**
- **Xbox**
- **PC**

### 📰 Novedades

Sección dedicada a próximos lanzamientos y novedades relacionadas con videojuegos.

---

## 🎵 Audio

La página incluye un reproductor de audio integrado en la barra de navegación.

El usuario puede:

- ▶️ Reproducir el audio.
- ⏸️ Pausarlo.
- 🔊 Controlar el volumen.
- 🔁 Reproducirlo en bucle.
- ⬇️ Descargar el archivo de audio.

El navegador puede bloquear la reproducción automática con sonido debido a las políticas de reproducción automática de los navegadores.

---

## 🃏 Tarjetas interactivas

Las tarjetas utilizan **CSS** para crear efectos de interacción.

Al interactuar con una tarjeta, se muestra una ficha técnica con información adicional del videojuego.

Para conseguir este efecto se utilizan propiedades como:

```css
position: absolute;
overflow: hidden;
border-radius: 25px;
```

Además, se utilizan pseudoclases como `:hover` para modificar el aspecto de las tarjetas durante la interacción.

---

## 🎨 Diseño

El diseño de la página está basado principalmente en **Flexbox**, permitiendo distribuir las tarjetas y adaptarlas al espacio disponible.

Ejemplo:

```css
.contenedor {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}
```

Las imágenes de los videojuegos utilizan `object-fit: cover` para mantener una presentación uniforme:

```css
.carta img {
    width: 100%;
    height: 360px;
    object-fit: cover;
}
```

Las tarjetas también utilizan bordes redondeados y diferentes estilos para mejorar la presentación visual.

---

## 🧭 Navegación

La barra de navegación permite acceder a las principales secciones de la web:

```text
Inicio
│
├── PS5
├── Xbox
├── PC
└── Novedades
```

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura y contenido de las páginas |
| **CSS3** | Diseño, estilos y efectos visuales |
| **Bootstrap 5.3.8** | Componentes y estilos adicionales |
| **Git** | Control de versiones |
| **GitHub** | Almacenamiento y gestión del repositorio |

---

## 📁 Estructura del proyecto

```text
PaginaWeb/
│
├── Inicio/
│   │
│   ├── index.html
│   │
│   ├── audio/
│   │   └── WeLost-LorienTestard.mp3
│   │
│   ├── css/
│   │   └── index.css
│   │
│   ├── img/
│   │   ├── Imágenes de los videojuegos
│   │   ├── Imágenes de las plataformas
│   │   └── Recursos gráficos
│   │
│   └── juegos/
│       │
│       ├── proximos.html
│       │
│       └── plataformas/
│           ├── pc.html
│           ├── playstation.html
│           └── xbox.html
│
└── README.md
```

---

## 🚀 Cómo ejecutar el proyecto

El proyecto no requiere instalar dependencias adicionales.

### Opción 1 — Abrir directamente

Abrir el archivo:

```text
Inicio/index.html
```

con cualquier navegador web compatible.

### Opción 2 — Visual Studio Code

Abrir el proyecto con **Visual Studio Code** y utilizar una extensión como **Live Server** para ejecutar la página y visualizar los cambios en tiempo real.

---

## 🌿 Control de versiones

El proyecto utiliza **Git** para controlar las diferentes versiones del código.

Actualmente se utilizan ramas para organizar el desarrollo:

```text
master
│
└── dev
```

La rama `dev` se utiliza para realizar cambios y desarrollar nuevas funcionalidades antes de incorporarlas a la rama principal.

El repositorio remoto está alojado en GitHub:

**https://github.com/AlbertoPueblas/PaginaWeb**

---

## 📌 Estado del proyecto

El proyecto se encuentra actualmente en desarrollo.

### Completado

- [x] Página principal
- [x] Barra de navegación
- [x] Tarjetas de videojuegos
- [x] Fichas técnicas
- [x] Efectos `hover`
- [x] Página de PlayStation
- [x] Página de Xbox
- [x] Página de PC
- [x] Sección de novedades
- [x] Diseño mediante Flexbox
- [x] Integración de Bootstrap
- [x] Reproductor de audio
- [x] Descarga del archivo de audio
- [x] Enlaces a tráileres
- [x] Organización del proyecto
- [x] Repositorio en GitHub
- [x] Control de versiones mediante Git

### Pendiente

- [ ] Ampliar el catálogo de videojuegos
- [ ] Añadir más información a las fichas técnicas
- [ ] Mejorar la adaptación a dispositivos móviles
- [ ] Añadir nuevas secciones
- [ ] Mejorar algunos aspectos visuales y de navegación

---

## 📚 Objetivo del proyecto

El objetivo del proyecto es poner en práctica los conocimientos adquiridos en **desarrollo web**, especialmente en:

- Estructura de documentos HTML.
- Selectores CSS.
- Flexbox.
- Posicionamiento de elementos.
- Pseudoclases.
- Diseño de tarjetas.
- Enlaces entre páginas.
- Organización de archivos.
- Uso de imágenes y recursos multimedia.
- Integración de Bootstrap.
- Control de versiones con Git.
- Trabajo con repositorios de GitHub.

---

## 👨‍💻 Autor

**Alberto Pueblas**

Proyecto realizado como práctica de desarrollo web.

---

## 🔗 Enlaces

- **Repositorio:** [github.com/AlbertoPueblas/PaginaWeb](https://github.com/AlbertoPueblas/PaginaWeb)