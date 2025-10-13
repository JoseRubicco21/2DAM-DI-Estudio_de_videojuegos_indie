# 2DAM-DI-Estudio_de_videojuegos_indie

GRUPO 2
Responsable de equipo: Jose Angel Rubicco
Equipo: Marcos Rey, Manuel Dono, Nuno Sotelo, Adriam Gaspar.

## Descripción:
Sitio para un pequeño estudio que desarrolla videojuegos independientes, donde muestran sus juegos y novedades.

### Partes de la web:
Inicio: Presentación del estudio y su filosofía, banner con el juego destacado.
Juegos: Listado con los juegos desarrollados, imágenes, descripciones, y enlaces para descarga o demo.
Noticias: Sección sencilla con entradas de blog o actualizaciones del estudio.
Contacto: Formulario y redes sociales.


## Ejemplos:

Ejemplo dado por nuestro cliente:  Axóuxere Games

Otros ejemplos: 
Supergiant Games ( Hades, Bastion, Transistor )
Team Cherry ( Hollow Knight, Hollow knight Silksong )
Nomada Studio ( Gris, Neva )


## División del trabajo
La propuesta inicial para la división del trabajo es la siguiente:
Equipo de diseño.
Equipo de implementación.

El equipo de diseño se encargará de diseñar la página en figma. Sus componentes, su disposición, paleta de colores, tipografía, etc.

El equipo de implementación se encargará de implementar dicho diseño.

Considerando que, hay 4 páginas en total será sensato dividir la carga de trabajo en 2 páginas cada uno, de esta forma se puede ir trabajando simultáneamente.

## Contribuir al Repositorio

Después de haber asignado el trabajo a cada uno trabajaremos de la siguiente manera en el código:

Habrá 5 ramas, una por cada página:
- Main: Rama a entregar, el proyecto entero.
- Inicio: Presentación del estudio y su filosofía, banner con el juego destacado.
- Juegos: Listado con los juegos desarrollados, imágenes, descripciones, y enlaces para descarga o demo.
- Noticias: Sección sencilla con entradas de blog o actualizaciones del estudio.
- Contacto: Formulario y redes sociales.

### Estructura

La estructura del repositorio es la siguiente:

```
DI-Grupo/
├── README.md
├── res/
│   └── img/                # Recursos de imágenes
│       ├── juegos/          # Imágenes de juegos
│       ├── noticias/           # Imágenes para noticias
│       ├── estudio/         # Imágenes del estudio
│       └── iconos/          # Iconos y elementos UI
└── src/
    └── html/
        ├── index.html      # Página de inicio
        ├── juegos.html     # Página de juegos
        ├── noticias.html   # Página de noticias
        └── contacto.html   # Página de contacto
```

**Descripción de archivos:**
- `README.md`: Documentación del proyecto
- `res/img/`: Directorio de recursos de imágenes
  - `juegos/`: Capturas, logos y assets de los juegos
  - `noticias/`: Imágenes para las noticias y blog
  - `estudio/`: Fotos del estudio y equipo
  - `iconos/`: Iconos de redes sociales y elementos de UI
- `src/html/`: Directorio principal con las páginas HTML
  - `index.html`: Página principal con presentación del estudio
  - `juegos.html`: Listado de juegos desarrollados
  - `noticias.html`: Blog y actualizaciones del estudio
  - `contacto.html`: Formulario de contacto y redes sociales

Para la mayoria de Iconos utilizaremos [FontAwesome](https://fontawesome.com/) o [Lucide](https://lucide.dev/)