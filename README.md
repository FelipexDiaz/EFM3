Este proyecto es una interfaz web desarrollada con HTML, Bootstrap 5, preprocesador SASS bajo la arquitectura **7-1**, y metodología de nombrado **BEM (Block Element Modifier)**. Se enfoca en la correcta organización del código, modularización de estilos y cumplimiento de buenas prácticas.

## 📁 Estructura del Proyecto

```
proyecto/
├── css/
├── img/
├── scss/
│   ├── abstracts/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── pages/
│   ├── themes/
│   └── main.scss
├── index.html
├── README.md
```

## 🚀 Tecnologías Usadas

- HTML5
- CSS3 con SASS (arquitectura 7-1)
- Bootstrap 5 (CDN)
- Metodología BEM

## 🎨 Organización (SASS + BEM)

- Variables SASS (`$primary-color`, etc.)
- Mixins reutilizables
- Clases BEM como `gallery__image`, `form__group`, `button--primary`

## 🖼️ Funcionalidades

1. Layout responsive con Bootstrap Grid  
2. Parallax con fondo fijo  
3. Carrusel de imágenes  
4. Flechas rojas, grandes y gruesas en carrusel  
5. Formulario estilizado  
6. Código SASS modular

## 📦 Compilar SASS

```bash
sass scss/main.scss css/main.css --style compressed
```
