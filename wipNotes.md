# Challenge Sara y Jon

## TODO'S

### Setup

1. Github & Setup general
   - [x] Repo de Sara y compartirlo
   - [x] Instalar Husky
     - [ ] Pendiente arreglar el fix de los mensajes de commit. Ver comentario abajo
   - [x] Estructura de páginas inicial
   - [x] Instalar SASS
     - [ ] Aprender bien la configuración
     - [ ] Comprobar con Sara que a ella le va bien todo

### Organización

2. Planificación del trabajo

   - **Domingo**: Montar sass, seudocódigo, organización

   1. Home Versión mobile

      1. Header y main INDEX / Sara
      2. Footer WORKS / Jon

   2. Preparación de todo el proyecto
      1. Html pages
         1. home.html
         2. works.html
         3. about.html

_Sass pages_ 1. variables, partials & extends 2. home.scss 3. works.scss 4. about.scss

_Estudiar las inclinaciones_ Ver pruebas hechas por Javier

TREE STRUCTURE AND NOTES

    home.html >
    works.html
    about.html

    scss/
    1. variables, partials & extends
    2. home.scss
    3. works.scss
    4. about.scss

    css/ se generan solos

- [ ] Husky
- [ ] Setup general de carpetas y organización
- [ ] Oswald 300? y OpenSans 300

## INCIDENTES

### Problemas con Husky

```sh
[202204-W3-Jon-Sara] git commit -m 'Adding images and icons folder'                                                                                                    general-setup  ✗ ✈
hint: The '.husky/commit-msg' hook was ignored because it's not set as executable.
hint: You can disable this warning with `git config advice.ignoredHook false`.
[general-setup 6e3c94f] Adding images and icons folder
 45 files changed, 188 insertions(+), 6 deletions(-)
```

<!-- TODO: Revisar esto. Lo dejo desactivado, pero es cutre. -->
<!-- FIXME: Revisar esto. Lo dejo desactivado, pero es cutre. -->

### Instalación

===

## Pseudocode

### Footer **HTML**

footer
footer**header
footer**header-title
footer\_\_header-icon

    footer__menu
        footer__menu-item
        footer__menu-item
        footer__menu-item
        footer__menu-item

    footer__section
        footer__section-title
        footer__section-links
        footer__section-links

    footer__section
        footer__section-title
        footer__section-links
        footer__section-links

    footer__section
        footer__section-title
        footer__section-icon
        footer__section-icon
        footer__section-icon

    footer__section
        footer__section-title
        footer__section-links
        footer__section-links
        footer__section-links

    footer__section
        footer__section-title
        footer__section-links
        footer__section-links
        footer__section-links

**SCSS**

<!-- // Usar variables -->

$font-headings
$font-texts
$color-green 
$color-white
$color-black
$color-pink

<!-- MIXINS -->

```scss
@mixin link-styes() {
  font-family: $font-headings
  color: #fff;
}

.info {
  @include theme;
}
.alert {
  @include theme($theme: DarkRed);
}
.success {
  @include theme($theme: DarkGreen);
}
```

### Works page

**Html**
gallery
gallery**row
gallery**item

**SCSS**
grid
columns repeat 3, 1fr
rows 10 > research how to define height

### Problemas varios

- **Problemas con el footer y los links que el hover se comporta mal**
  - Resuelto con ayuda de J.Mora.
- Problemas con el layout, que no me permitía añadir estilos. El tema era porque hay correlaciones entre los contenedores y los hijos. No podía aplicar estilos de texto si tenía un padre con display: block… creo. Hablarlo con Javier.
- Problemas de nuevo con el layout de bloques… las imágenes me quedan todas mal.
  LEYENDO ESTO: https://techstacker.com/html-block-vs-inline-block/
- ME DEJA DE COMPILAR SASS Y NO ME DOY CUENTA. TOÑO ME AYUDA A RESOLVERLO.

### Tareas para el martes 26 de abril

- Hacer la página de works en mobile
- Hacer la página de works en desktop
- Dar soporte a Sara para que pueda avanzar en lo que precise
- Intentar lograr el efecto de curvatura
- Tratar de implementar alguna "funcionalidad-utilidad" extra de Sass

DAILY SARA:

- Mobile home
- Quiere acabar el home, tiene desde el vídeo hasta la crucecita.
- Cuando tenga hecha la mobile-home hacemos PR
