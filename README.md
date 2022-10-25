# Typography CSS library
**Author:** *Filip Roubínek*

## Demo site
Link to **[demo](https://pslib-cz.github.io/2022l4web-css-typographic-library-FilipRoubinek/)** site for preview.

## Description
This Library functions as starting point for building your website. Elements are by named by places they are used on. This library helps you with setting up quickly your site with the basic improvements using raw tags. Description of seperate components is made chronologicaly from CSS file for quick navigation.
## Navigation
1. [Implementation](#Implementation)
2. [Usage](#Usage)
3. [Components](#Components)
   3.1 [Colours](#Colours)
   3.2 [Body](#Body)
   3.3 [Navigation bar](#Navigation bar)
   3.4 [Section & .wrapper](#Section & .wrapper)
   3.5 [Headings](# Headings)
   3.6 [Text tags](#Text tags)
   3.7 [Quotes](#Quotes)
   3.8 [Lists](#Lists)
   3.9 [Table](#Table)
   3.10 [Buttons](#Buttons)
   3.11 [Pictures and gallery](#Pictures and gallery)
   3.12 [Code showcase](#Code showcase)
  
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
Tag `<h>` is defined directly, without class. This is done for the sole purpose of having each tag `<h>` the same size troughout the whole site

* 40px for `<h1>`
* 32px for `<h2>`
* 24px for `<h3>`
* 18px for `<h4>`
* 12px for `<h5>`
* 8px for `<h6>`

### Text tags
#### `Strike`
Used on text that has been redacted. Color changed by value `var`
#### `a`
Link in text left with it's default color for good visibility in text and stripped of underline
#### `.underline`
`span` class for highlighted text using underline
#### Undefined tags
Tags `<b>``<i>``<small>` were left with their browser values.

### Quotes
Tag `<q>` has been given italic and lighter values, so it distinct from normal text. Quotes can be used as separate blocks of text supplemented by tag `<figcaption>` filled with the origins of the quote. It can also be used in text alone.

After quote, usualy we can find the authors name, for this purpose there is tag `<span class="author">` for highlighting the authors name by adding weight to font and making it italic.

### Lists
Tags for making lists weren't changed, just tag `<li>` was given some padding for readability.

### Table
Custom table was given class `.pretable`. It's values were changed, so that the it's brackets are together spanning the whole width of their parent tag. The head of the table has changed color with value `var`.

### Buttons
Buttons were made by modifying tag `<a class="btn">` to version that is visible at **[demo](https://pslib-cz.github.io/2022l4web-css-typographic-library-FilipRoubinek/)** site.

Showcased buttons with class `btm-calm``btn-hover` and `btn-clicked` aren't meant for usage and are in code just for the sole purpose of showing how button looks in different stages (calm, hovered and clicked).

### Pictures and gallery
Tag `<img>` is placed inside tag `<figure class="GalleryItem">` for giving the maximal width value it will have by our own choosing. Tag `<div class="gallery">` is sorting `.GalleryItem` into value `display=flex;`, so that they are equaly displayed across their parenting tag.

### Code showcase
Here is short showcase of HTML code for you to see how some tags are used (in the example is section with quotes).
```html
<section class="presec">
        <div class="wrapper">
            <h2 id="quotes">
                Quotes
            </h2>
            <h3>
                Blockquote
            </h3>
            <p>
                <q>
                    Going to church doesn’t make you a Christian any more than going to a garage makes you an
                    automobile.
                </q>
            <figcaption> <span class="author">Billy Sunday</span> Billy Sunday, the Man and His Message: With His Own
                Words
                Which Have Won Thousands for Christ</figcaption>
            </p>
            <h3>
                Q tag
            </h3>
            <p>
                <q>You said what? An egg</q>. He stabs him
            </p>
            <p>
                <q>You know the world is going crazy when the best rapper is a white guy, the best golfer is a black
                    guy,
                    the tallest guy in the NBA is Chinese, the Swiss hold the America's Cup, France is accusing the U.S.
                    of
                    arrogance, Germany doesn't want to go to war, and the three most powerful men in America are named
                    "Bush", "Dick", and "Colin." Need I say more?</q> <span class="author">Chris Rock</span>
            </p>
        </div>
    </section>
```
Thanks for reading and have a nice day!
