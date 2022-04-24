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

    1. Home Versión mobile / Header - Footer

        1. Header / Sara
        2. Footer / Jon

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

-   [ ] Husky
-   [ ] Setup general de carpetas y organización
-   [ ] Oswald 300? y OpenSans 300

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

## Pseudocode para el footer

**HTML**

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
