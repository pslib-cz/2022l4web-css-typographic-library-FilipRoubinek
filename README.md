# Typography CSS library
**Author:** *Filip Roubínek*

## Demo site
Link to **[demo](https://pslib-cz.github.io/2022l4web-css-typographic-library-FilipRoubinek/)** site for preview.

## Description
This Library functions as starting point for building your website. Elements are by named by places they are used on. This library helps you with setting up quickly your site with the basic improvements using raw tags. Description of seperate components is made chronologicaly from CSS file for quick navigation.

## Implementation
Download style.css file at **[docs/](https://github.com/pslib-cz/2022l4web-css-typographic-library-FilipRoubinek)** folder and implement it into your site by connecting it with your HTML code in the `<head>` part

## Usage
Quic setup for building your website that offers you basic design that you can change to your liking.

## Components

### Colours
At the top of the CSS file in `:root` you can find predefined variables of colours in RGB.

### Body
The whole body of your HTML code has predifined gradient color used `--var` value as well as predefined `font-family`. While opening demo site you can see quick animation while the site is loading, this function is defined in body as well. After `body` there are keyframes that tell us what animation is used (in this case `opacity`) for the loading animation. At last `scroll-behavior` is set to value smooth.

### Navigation bar
Navigation bar is made using tag `<nav>` and tag `<a>`. Using function flex and borders forms quite neat box of options to choose which part of site we want to scroll to.

### Section & .wrapper
Tag `<section>` is defined by class `.presec` (predefined section) for easy writing. Section has slight padding and margin for content visibility

Class `.wrapper` is used for centralizing content in the middle directing down. It's used in every section of content except `<nav>`, which is defined alone.

### Headings
Tag `<h>` is defined directly, without class, because it has 

### Text tags

### Quotes

### Table

### Buttons

### Gallery
