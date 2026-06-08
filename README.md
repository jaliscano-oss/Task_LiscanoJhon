# PracticaCSSFinal — Sitio Web Responsivo

Proyecto de práctica de HTML5 y CSS3 desarrollado en la asignatura **Fundamentos de Sistemas Web** de la Universidad de las Fuerzas Armadas ESPE, sede Santo Domingo.

---

## Descripción del Proyecto

Sitio web multi-página que aplica etiquetas semánticas de HTML5, estilos CSS3 modulares, diseño responsivo mediante media queries y buenas prácticas de maquetación con Flexbox. Incluye formularios, multimedia, tablas y navegación entre páginas.

---

## Estructura de Carpetas

```
PracticaCSSFinal/
│
├── index.html                  # Página principal — Perfil profesional
├── portafolio.html             # Página de portafolio (nueva)
│
├── pages/
│   ├── buscar.html             # Página de búsqueda (recibe datos GET)
│   └── cto/
│       └── contacto.html       # Página de contacto
│
├── css/
│   ├── general.css             # Estilos compartidos para todo el sitio
│   ├── index.css               # Estilos exclusivos de index.html
│   ├── buscar.css              # Estilos exclusivos de buscar.html
│   ├── contacto.css            # Estilos exclusivos de contacto.html
│   └── portafolio.css          # Estilos exclusivos de portafolio.html
│
├── img/
│   ├── mundito.ico             # Ícono de la pestaña del navegador
│   └── espe/
│       └── imagenEjemploEspe.png
│
├── audio/
│   └── audioEjemploA7X.mp3
│
├── video/
│   └── videoEjemploDiagnostica.mp4
│
└── README.md
```

---

## Páginas del Sitio

| Página | Descripción |
|--------|-------------|
| `index.html` | Página principal con perfil, multimedia, formularios y tabla de horarios |
| `portafolio.html` | Portafolio personal con proyectos, habilidades y metas profesionales |
| `pages/buscar.html` | Página receptora de formularios con método GET |
| `pages/cto/contacto.html` | Formulario de contacto con validación |

---

## Tecnologías Utilizadas

- **HTML5** — Estructura semántica completa
- **CSS3** — Estilos visuales, Flexbox, Box Model, media queries
- **Font Awesome 6.5** — Íconos vectoriales (CDN)
- **Google Fonts** — Tipografía Poppins (portafolio)
- **Git / GitHub** — Control de versiones y repositorio público

---

## Características Principales

- Diseño responsivo con breakpoint en `700px`
- CSS modular: cada página tiene su propio archivo CSS
- Uso de selectores de clase e ID en todos los archivos CSS
- Flexbox para maquetación de grids y navegación
- Formularios con validación HTML5 (required, minlength, pattern)
- Multimedia: video local, audio local e iframe de YouTube
- Navegación multi-página con rutas relativas

---

## Capturas de Pantalla

### Vista escritorio — index.html
> Header oscuro, navegación dorada, contenido en tarjetas blancas.

### Vista móvil — index.html
> Menú en columna vertical, formularios a ancho completo, imágenes fluidas.

### portafolio.html — Vista escritorio
> Grid de 3 tarjetas de proyectos, tabla de habilidades con barras de progreso.

### portafolio.html — Vista móvil
> Tarjetas apiladas en columna, perfil con imagen arriba y texto abajo.

---

## Información del Autor

| Campo | Dato |
|-------|------|
| **Nombre** | Jhon Anderson Liscano Carbo |
| **Carrera** | Ingeniería en Tecnologías de la Información |
| **Universidad** | Universidad de las Fuerzas Armadas ESPE |
| **Sede** | Santo Domingo de los Tsáchilas |
| **Período** | 202650 — abril / agosto 2026 |
| **Nivel / NRC** | Cuarto — 29535 |
| **Docente** | Ing. Geovanny Brito |

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/PracticaCSSFinal.git
   ```
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Usar la extensión **Live Server** para abrir `index.html` en el navegador.
4. Navegar entre páginas usando el menú principal.

---

*© 2026 Jhon Anderson Liscano Carbo — Fundamentos de Sistemas Web — ESPE Santo Domingo*