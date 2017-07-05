<!-- <img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">

html-layout
===========

## Objective
Understand HTML and its uses in layout by completing a series of tasks

## Directions
Fork this repo then clone your fork onto your local machine. Inside each of the three folders you will find an image. That image is a representation of the layout you need to create using HTML and CSS. The 'first' folder contains an index.html and a style.css file. In the other folders, you'll need to add them yourself. *Your first step should be connecting your CSS sheet with your HTML sheet.* -->

<img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">

# Project Summary

In this project, you will be cloning/re-creating three different html-layouts from scratch. This will help you get used to creating html documents and linking css pages. This project will also help you practice the ability to create layouts using html and css.

## Setup

* Fork and clone this repo.
* `cd` into the directory.

## Directions

Inside each of the three folders you will find an image. That image is a representation of the layout you need to create using HTML and CSS. The 'first' folder contains an index.html and a style.css file. In the other folders, you'll need to add them yourself.

## First

### Directions

Below are the very broad directions to finishing the clone of the image in the 'first' folder. We encourage you to try to finish this project with as little help as possible. But if you need more guidance there is a 'Follow Along' section right below these directions that will be a little more in dept. Have Fun!

* Open 'first' folder.
* Create a reset.css file.
* Add reset css styles.
* Create your index.html boiler plate.
* Link your style.css in your index.html file.
* Create a HTML structure using semantic elements.
* Add CSS to give each element a height, width, position, etc. to make your webpage look as close as you can to the image provided.

### Follow Along

* Open 'first' folder.
* Create a reset.css file and add the reset styling in it.
  *  <details>

      <summary> <code> reset.css </code> </summary>

      ```css
      html, body, div, span, applet, object, iframe,
      h1, h2, h3, h4, h5, h6, p, blockquote, pre,
      a, abbr, acronym, address, big, cite, code,
      del, dfn, em, img, ins, kbd, q, s, samp,
      small, strike, strong, sub, sup, tt, var,
      b, u, i, center,
      dl, dt, dd, ol, ul, li,
      fieldset, form, label, legend,
      table, caption, tbody, tfoot, thead, tr, th, td,
      article, aside, canvas, details, embed,
      figure, figcaption, footer, header, hgroup,
      menu, nav, output, ruby, section, summary,
      time, mark, audio, video {
      	margin: 0;
      	padding: 0;
      	border: 0;
      	font-size: 100%;
      	font: inherit;
      	vertical-align: baseline;
      }

      html {
        box-sizing: border-box;
      }
      *, *:before, *:after {
        box-sizing: inherit;
      }
      /* HTML5 display-role reset for older browsers */
      article, aside, details, figcaption, figure,
      footer, header, hgroup, menu, nav, section {
      	display: block;
      }
      body {
      	line-height: 1;
      }
      ol, ul {
      	list-style: none;
      }
      blockquote, q {
      	quotes: none;
      }
      blockquote:before, blockquote:after,
      q:before, q:after {
      	content: '';
      	content: none;
      }
      table {
      	border-collapse: collapse;
      	border-spacing: 0;
      }

      ```

      </details>
* Open `index.html`.
* Inside index.html, create your index.html boiler plate.
  *  <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
        </head>
        <body>
        </body>
      </html>
      ```

      </details>
* Inside `index.html`, link the index.html file to the style.css file.
  *  <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
        </body>
      </html>
      ```

      </details>
* Inside `index.html`, link the index.html file to the reset.css file. Be sure to insert this link before the style.css.
  *  <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="reset.css">
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
        </body>
      </html>
      ```

      </details>
* Inside index.html, in the `body` tags create header. Give it a class so that we can style it later. Close your header tag.
  *  <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="reset.css">
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
          <header class="header"></header>
        </body>
      </html>
      ```

      </details>
* Inside index.html, below the closing header tag create a aside section. Give it a class name. Close your aside tag.
  * <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="reset.css">
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
          <header class="header"></header>
          <aside class="side-bar"></aside>
        </body>
      </html>
      ```

      </details>
* Inside index.html, below the closing aside tag create a main section. Give it a class name and close the main section.
  * <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="reset.css">
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
          <header class="header"></header>
          <aside class="side-bar"></aside>
          <main class="main">

          </main>
        </body>
      </html>
      ```

      </details>
* Inside index.html, inside your main section add a div. Give it a class name and do forget to close the div.
  * <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="reset.css">
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
          <header class="header"></header>
          <aside class="side-bar"></aside>
          <main class="main">
            <div class="main-footer"></div>
          </main>
        </body>
      </html>
      ```

      </details>
* Inside index.html, below the closing main tag create another aside section. Give it the same class name as the previous aside tag and close the aside section.
  * <details>

      <summary> <code> index.html </code> </summary>

      ```html
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>first Solution</title>
          <link rel="stylesheet" href="reset.css">
          <link rel="stylesheet" href="style.css">
        </head>
        <body>
          <header class="header"></header>
          <aside class="side-bar"></aside>
          <main class="main">
            <div class="main-footer"></div>
          </main>
          <aside class="side-bar"></aside>
        </body>
      </html>
      ```

      </details>
* Open `style.css`.
* Inside style.css, select the header by class and give it a height and background color.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .header{
      background: #444444;
      height: 20vh;
    }
    ```

    </details>
* Inside style.css, select the aside sections by class and give them a height, width, background color, and make them float to the left side of the page.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .side-bar{
      height: 80vh;
      width: 15%;
      background: #D8D8D8;
      float: left;
    }
    ```

    </details>
* Inside style.css, select the main section by class and give it a height, width, background color, position, and make it float to the left side of the page.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .main{
      height: 80vh;
      width: 70%;
      background: #EFEFEF;
      position: relative;
      float: left;
    }
    ```

    </details>
* Inside style.css, select the div inside the main section by class and give it a height, width, background color, position, bottom property, and left property.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .main-footer{
      height: 20%;
      width: 100%;
      background: #222222;
      position: absolute;
      bottom: 0;
      left: 0;
    }
    ```

    </details>

### Solution

<details>

<summary> <code> index.html </code> </summary>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>first Solution</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header class="header"></header>
    <aside class="side-bar"></aside>
    <main class="main">
      <div class="main-footer"></div>
    </main>
    <aside class="side-bar"></aside>
  </body>
</html>
```

</details>
details>

<summary> <code> style.css </code> </summary>

```css
.header{
  background: #444444;
  height: 20vh;
}

.side-bar{
  height: 80vh;
  width: 15%;
  background: #D8D8D8;
  float: left;
}

.main{
  height: 80vh;
  width: 70%;
  background: #EFEFEF;
  position: relative;
  float: left;
}

.main-footer{
  height: 20%;
  width: 100%;
  background: #222222;
  position: absolute;
  bottom: 0;
  left: 0;
}
```

</details>

## Second

### Directions

Below are the very broad directions to finishing the clone of the image in the 'second' folder. We encourage you to try to finish this project with as little help as possible. But if you need more guidance there is a 'Follow Along' section right below these directions that will be a little more in dept. Good luck!

* Open 'second' folder.
* Create a html file named `index.html` inside of the 'second' folder.
* Create css file named `style.css` inside of the 'second' folder.
* Create a `reset.css` file inside of the 'second' folder.
* Add reset css styles into `reset.css`.
* Create the boiler plate in the index.html file you created during setup.
* Link the style.css file you created during setup in your index.html file.
* Create a HTML structure using semantic elements.
* Add CSS to give each element a height, width, position, etc. to make your webpage look as close as you can to the image provided.

### Follow Along

* Open 'second' folder.
* Create a html file named `index.html` inside of the 'second' folder.
* Create css file named `style.css` inside of the 'second' folder.
* Create a `reset.css` file inside of the 'second' folder.
* Add reset css styles into `reset.css`.
  * solution
* Open `index.html`.
* Inside index.html, create your index.html boiler plate.
  * solution
* Inside index.html, link the index.html file to the style.css file.
  * solution
* Inside `index.html`, link the index.html file to the reset.css file. Make sure it's linked before your `style.css` file.
  * solution
* Inside index.html, inside the body create a section. Give it two class names. One that will be the same as the next couple of sections. And another that will be unique and differentiate it from the other sections by background color. This will allow us to not repeat ourselves. Close the section.
  * solution
* Inside index.html, below the section you made in the previous step create another section. Give it two class names as well, one will be the same as the previous section and the other will be different according to the background color.
  * solution
* Inside index.html, below the section you made in the previous step create a third section. Give it two class names as well, one will be the same as the previous sections and the other will be different according to the background color.
  * solution
* Inside index.html, inside the third section tags create a image element. Give it a class name so we can style it later.
  * solution
* Open `style.css`.
* Inside style.css, select the sections by their similar class and give them a height, width, and another property that will make them float the the left.
  * solution
* Inside style.css, select each of the sections by their unique class name and add a property to change their background color.
  * solution
* Inside style.css, select the green section by its unique class and give it a position so that we can later move its children in relation to it.
  * solution
* Inside style.css, select the image by class and give it a height, width, position, bottom property, and left property.
  * solution


### Solution

* html solution
* css solution

## Third

### Directions

Below are the very broad directions to finishing the clone of the image in the 'third' folder. We encourage you to try to finish this project with as little help as possible. But if you need more guidance there is a 'Follow Along' section right below these directions that will be a little more in dept.. Have Fun!

* Open 'third' folder.
* Create a index.html file inside the 'third' folder.
* Create a style.css file inside the 'third' folder.
* Create a `reset.css` file inside of the 'third' folder.
* Add reset css styles into `reset.css`.
* Create the boiler plate in the index.html file you created during setup.
* Link the style.css file you created during setup in your index.html file.
* Create a HTML structure using semantic elements.
* Add CSS to give each element a height, width, position, etc. to make your webpage look as close as you can to the image provided.

### Follow Along

* Open 'third' folder.
* Create a index.html file inside the 'third' folder.
* Create a style.css file inside the 'third' folder.
* Create a reset.css file inside of the 'third' folder.
* Add reset css styles into `reset.css`.
* Open `index.html`.
* Inside index.html, create your index.html boiler plate.
  * solution
* Inside index.html, link the index.html file to the style.css file.
  * solution
* Inside index.html, link the index.html file to the reset.css file. Make sure it is linked before your style.css file.
  * solution
* Inside index.html, inside the body create a header. Give it a class name and close the header.
  * solution
* Inside index.html, inside the header create a div and give it a class name so we can style it later. Close the div.
  * solution
* Inside index.html, below the header element create a main section. Give it a class name and close the main section.
  * solution
* Inside  index.html, inside the main section you created in the previous step create a paragraph. Add the same text you see in the image provided. Give it a class name and close the paragraph.
  * solution
* Inside index.html, below the main section create four sections one after the other and close each of them. Give each of the section the same class name.
  * solution
* Inside index.html, for each of the four sections you created in the previous step give each one a second unique class name that will differentiate them by background color.
  * solution
* Open `style.css`.
* Inside style.css, select the header by class and give it a height, width, background color, and padding.
  * solution
* Inside style.css, select the div inside the header by class name and give it a height, width, background color, and margin property.
  * solution
* Inside style.css, select the main section by class and give it some padding.
  * solution
* Inside style.css, select the text inside the main section by class and give it font-size, line height, font family, and a margin to add some space between it and the elements below it.
  * solution
* Inside style.css, select the lower four sections by their similar class name and give them a height.
  * solution
* Inside style.css, select the lower four section by their unique class name individually and give each their corresponding background color.
  * solution

### Solution

* html solution
* css solution

# End of project

Congratulations you have finish this project.

## Contributions
If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2015. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<img src="https://devmounta.in/img/logowhiteblue.png" width="250">
