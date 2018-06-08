## Basic CSS Challenges

> Cascading Style Sheets (CSS) tell the browser how to display the text and other content that you write in HTML. Note that CSS is case-sensitive so be careful with your capitalization.

> CSS has been adopted by all major browsers and allows you to control: color, fonts, positioning, spacing, sizing, decorations, transitions.

- [Use CSS Selectors to Style Elements](#use-css-selectors-to-style-elements)
- [Use a CSS class to Style Elements](#use-a-css-class-to-style-elements)
- [Use a CSS class to Style Elements](#use-a-css-class-to-style-elements)
- [Change the Font Size of an Element](#change-the-font-size-of-an-element)
- [Set the Font Family of an Element](#set-the-font-family-of-an-element)
- [Import a Google Font](#import-a-google-font)
- [Specify How Fonts Should Degrade](#specify-how-fonts-should-degrade)
- [Add Images to your Website](#add-images-to-your-website)
- [Size your Images](#size-your-images)
- [Add Borders Around your Elements](#add-borders-around-your-elements)
- [Add Rounded Corners with a Border Radius](#add-rounded-corners-with-a-border-radius)
- [Make Circular Images with a Border Radius](#make-circular-images-with-a-border-radius)
- [Give a Background Color to a Div Element](#give-a-background-color-to-a-div-element)
- [Use an ID Attribute to Style an Element](#use-an-id-attribute-to-style-an-element)
- [Adjusting the Padding of an Element](#adjusting-the-padding-of-an-element)
- [Adjust the Margin of an Element](#adjust-the-margin-of-an-element)
- [Add a Negative Margin to an Element](#add-a-negative-margin-to-an-element)
- [Add Different Padding to Each Side of an Element](#add-different-padding-to-each-side-of-an-element)
- [Add Different Margins to Each Side of an Element](#add-different-margins-to-each-side-of-an-element)
- [Use Clockwise Notation to Specify the Padding of an Element](#use-clockwise-notation-to-specify-the-padding-of-an-element)
- [Use Clockwise Notation to Specify the Margin of an Element](#use-clockwise-notation-to-specify-the-margin-of-an-element)
- [Use Attribute Selectors to Style Elements](#use-attribute-selectors-to-style-elements)
- [Understand Absolute versus Relative Units](#understand-absolute-versus-relative-units)
- [Style the HTML Body Element](#style-the-html-body-element)
- [Inherit Styles from the Body Element](#inherit-styles-from-the-body-element)
- [Prioritize One Style Over Another](#prioritize-one-style-over-another)
- [Override Styles in Subsequent CSS](#override-styles-in-subsequent-css)
- [Override Class Declarations by Styling ID Attributes](#override-class-declarations-by-styling-id-attributes)
- [Override Class Declarations with Inline Styles](#override-class-declarations-with-inline-styles)
- [Override All Other Styles by using Important](#override-all-other-styles-by-using-important)
- [Use Hex Code for Specific Colors](#use-hex-code-for-specific-colors)
- [Use Hex Code to Mix Colors](#use-hex-code-to_mix_colors)
- [Use Abbreviated Hex Code](#use-abbreviated-hex-code)
- [Use RGB values to Color Elements](#use-rgb-values-to-color-elements)
- [Use RGB to Mix Colors](#use-rgb-to-mix-colors)
- [Use CSS Variables to change several elements at once](#use-css-variables-to-change-several-elements-at-once)
- [Create a Custom CSS Variable](#create-a-custom-css-variable)
- [Use a Custom CSS Variable](#use-a-custom-css-variable)
- [Attach a Fallback value to a CSS Variable](#attach-a-fallback-value-to-a-css-variable)
- [Cascading CSS Variables](#cascading-css-variables)
- [Change a variable for a specific area](#change-a-variable-for-a-specific-area)
- [Use a media query to change a variable](#use-a-media-query-to-change-a-variable)

----

#### Use CSS Selectors to Style Elements
At the top of your code, create a style element. Inside that style element, you can create a CSS selector for all h2 elements. Delete your h2 element's style attribute and instead create a CSS style element. Add the necessary CSS to turn all h2 elements blue.

```` html
<style>
  h2 {
    color: blue;
  }
</style>

<h2>CatPhotoApp</h2>
<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
````
----

#### Use a CSS class to Style Elements
Inside your style element, change the `h2` selector to `.red-text` and update the color's value from blue to red. Give your `h2` element the `class` attribute with a value of `'red-text'`.

```` html
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
````
----

#### Style Multiple Elements with a CSS Class
Apply the red-text class to your `h2` and `p` elements.

```` html
<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
````
----

#### Change the Font Size of an Element
Create a second `p` element after the existing `p` element with the following kitty ipsum text: `Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.`

Inside the same `<style>` tag that contains your `red-text` class, create an entry for `p` elements and set the `font-size` to 16 pixels (`16px`).

```` html
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
````
----

#### Set the Font Family of an Element
Make all of your `p` elements use the `Monospace` font.

```` html
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
````
----

#### Import a Google Font
Now, let's import and apply a Google font. First, you'll need to make a call to Google to grab the `Lobster` font and load it into your HTML. Apply the font-family of `Lobster` to your `h2` element.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
````
----

#### Specify How Fonts Should Degrade
There are several default fonts that are available in all browsers. These include `Monospace`, `Serif` and `Sans-Serif`. When one font isn't available, you can tell the browser to *degrade* to another font.
Now comment out your call to Google Fonts, so that the `Lobster` font isn't available. Notice how it degrades to the `Monospace` font.

```` html
<!--
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
-->
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
````
----

#### Add Images to your Website
You can add images to your website by using the `img` element, and point to a specific image's URL using the `src` attribute. All img elements must have an `alt` attribute. The text inside an `alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load. Try it with this image: `https://bit.ly/fcc-relaxing-cat`.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
<img src="https://bit.ly/fcc-relaxing-cat" alt="relaxing cat photograph">
````
----

#### Size your Images
Create a class called `smaller-image` and use it to resize the image so that it's only 100 pixels wide.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
<img  class="smaller-image" src="https://bit.ly/fcc-relaxing-cat"
      alt="relaxing cat photograph">
````
----

#### Add Borders Around your Elements
Create a class called `thick-green-border` that puts a 10-pixel-wide green border with a style of `solid` around an HTML element, and apply that class to your cat photo.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border-width: 10px;
    border-style: solid;
    border-color: green;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
<img  class="smaller-image thick-green-border"
      src="https://bit.ly/fcc-relaxing-cat"
      alt="relaxing cat photograph">
````
----

#### Add Rounded Corners with a Border Radius
You can specify a `border-radius` with pixels. Give your cat photo a `border-radius` of `10px`.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border-width: 10px;
    border-style: solid;
    border-color: green;
    border-radius: 10px;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
<img  class="smaller-image thick-green-border"
      src="https://bit.ly/fcc-relaxing-cat"
      alt="relaxing cat photograph">
````
----

#### Make Circular Images with a Border Radius
In addition to pixels, you can also specify a `border-radius` using a percentage. Give your cat photo a `border-radius` of `50%`.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border-width: 10px;
    border-style: solid;
    border-color: green;
    border-radius: 50%; /* 10px; */
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p class="red-text">
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip
  the couch sleep in the sink fluffy fur catnip scratched.
</p>
<img  class="smaller-image thick-green-border"
      src="https://bit.ly/fcc-relaxing-cat"
      alt="relaxing cat photograph">
````
----

#### Give a Background Color to a Div Element
You can set an element's background color with the `background-color` property.
Create a class called `silver-background` with the `background-color` of silver. Assign this class to your `div` element.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border-width: 10px;
    border-style: solid;
    border-color: green;
    border-radius: 50%;
  }
  .silver-background {
    background-color: silver;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p>
  <a href="#">
    <img  class="smaller-image thick-green-border"
          src="https://bit.ly/fcc-relaxing-cat"
          alt="relaxing cat photograph">
  </a>
</p>
<div class="silver-background">
  <ul>
    <li>milk</li>
    <li>play</li>
    <li>sleep</li>
  </ul>
  <ol>
    <li>water</li>
    <li>dogs</li>
    <li>cheese</li>
  </ol>
</div>

<form action="/submit-cat-photo">
  <label><input type="radio" name="indoor" checked> Indoor</label>
  <label><input type="radio" name="outdoor"> Outdoor</label>
  <label><input type="checkbox" name="personality" checked> Loving</label>
  <label><input type="checkbox" name="personality"> Playful</label>
  <label><input type="checkbox" name="personality"> Charming</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
````
----

#### Use an ID Attribute to Style an Element
One cool thing about `id` attributes is that, like classes, you can style them using CSS. Try giving your form, which now has the id attribute of `cat-photo-form`, a green background.

```` html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">
<style>
  #cat-photo-form {
    background-color: green;
  }
  .red-text {
    color: red;
  }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border-width: 10px;
    border-style: solid;
    border-color: green;
    border-radius: 50%;
  }
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p>
  <a href="#">
    <img  class="smaller-image thick-green-border"
          src="https://bit.ly/fcc-relaxing-cat"
          alt="relaxing cat photograph">
  </a>
</p>
<ul>
  <li>milk</li>
  <li>play</li>
  <li>sleep</li>
</ul>
<ol>
  <li>water</li>
  <li>dogs</li>
  <li>cheese</li>
</ol>

<form id="cat-photo-form" action="/submit-cat-photo">
  <label><input type="radio" name="indoor" checked> Indoor</label>
  <label><input type="radio" name="outdoor"> Outdoor</label>
  <label><input type="checkbox" name="personality" checked> Loving</label>
  <label><input type="checkbox" name="personality"> Playful</label>
  <label><input type="checkbox" name="personality"> Charming</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
````
----

#### Adjusting the Padding of an Element
Now let's put our Cat Photo App away for a little while and learn more about styling HTML.

Three important properties control the space that surrounds each HTML element: `padding`, `margin`, and `border`.
An element's `padding` controls the amount of space between the element and its `border`. Change the padding of your green box to match that of your red box.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
  }
  .green-box {
    background-color: green;
    padding: 20px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Adjust the Margin of an Element
An element's `margin` controls the amount of space between an element's `border` and surrounding elements. Change the `margin` of the green box to match that of the red box.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
    margin: 20px;
  }
  .green-box {
    background-color: green;
    padding: 20px;
    margin: 20px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Add a Negative Margin to an Element
If you set an element's `margin` to a negative value, the element will grow larger. Change the `margin` of the green box to `-15px`, so it fills the entire horizontal width of the yellow box around it.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
    margin: 20px;
  }
  .green-box {
    background-color: green;
    padding: 20px;
    margin: -15px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Add Different Padding to Each Side of an Element
Sometimes you will want to customize an element so that it has different `padding` on each of its sides. Give the green box a `padding` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
    margin: 20px;
  }
  .green-box {
    background-color: green;
    padding-left: 40px;
    padding-top: 40px;
    padding-right: 20px;
    padding-bottom: 20px;
    margin: -15px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Add Different Margins to Each Side of an Element
Sometimes you will want to customize an element so that it has a different `margin` on each of its sides. Give the green box a `margin` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
    margin: 20px;
  }
  .green-box {
    background-color: green;
    padding-left: 40px;
    padding-top: 40px;
    padding-right: 20px;
    padding-bottom: 20px;
    margin-left: 40px;
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Use Clockwise Notation to Specify the Padding of an Element
Use `Clockwise Notation` to give the ".green-box" class a `padding` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
    margin: 20px;
  }
  .green-box {
    background-color: green;
    padding: 40px 20px 20px 40px;
    margin-left: 40px;
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Use Clockwise Notation to Specify the Margin of an Element
Use `Clockwise Notation` to give the element with the green-box class a `margin` of `40px` on its top and left side, but only `20px` on its bottom and right side.

```` html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }
  .red-box {
    background-color: red;
    padding: 20px;
    margin: 20px;
  }
  .green-box {
    background-color: green;
    padding: 40px 20px 20px 40px;
    margin: 40px 20px 20px 40px;
  }
</style>

<h5 class="injected-text">margin</h5>
<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Use Attribute Selectors to Style Elements
Using the `type` attribute selector, try to give the checkboxes in CatPhotoApp a top margin of `10px` and a bottom margin of `15px`.

````html
<link href="https://fonts.googleapis.com/css?family=Lobster"
      rel="stylesheet" type="text/css">

<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, monospace;
  }

  p {
    font-size: 16px;
    font-family: monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }

  .silver-background {
    background-color: silver;
  }

  [type='checkbox'] {
    margin: 10px 0px 15px 0px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<main>
  <p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <div class="silver-background">
    <p>Things cats love:</p>
    <ul>
      <li>cat nip</li>
      <li>laser pointers</li>
      <li>lasagna</li>
    </ul>
    <p>Top 3 things cats hate:</p>
    <ol>
      <li>flea treatment</li>
      <li>thunder</li>
      <li>other cats</li>
    </ol>
  </div>

  <form action="/submit-cat-photo" id="cat-photo-form">
    <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label><input type="checkbox" name="personality" checked> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
````
----

#### Understand Absolute versus Relative Units
Add a `padding` property to the element with class `red-box` and set it to `1.5em`.

````html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }

  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }

  .yellow-box {
    background-color: yellow;
    padding: 20px 40px 20px 40px;
  }

  .red-box {
    background-color: red;
    margin: 20px 40px 20px 40px;
    padding: 1.5em;
  }

  .green-box {
    background-color: green;
    margin: 40px 20px 20px 40px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
````
----

#### Style the HTML Body Element
Now let's start fresh and talk about **CSS inheritance**.
Every HTML page has a `body` element. We can prove that the `body` element exists here by giving it a `background-color` of black. Add a black background color to the `body` element.

```` html
<style>
  body {
    background-color: black;
  }
</style>
````
----

#### Inherit Styles from the Body Element
First, create a `h1` element with the text `Hello World`. Then, let's give all elements on your page the color of green by adding `color: green;` to your body element's style declaration. Finally, give your body element the `font-family` of Monospace by adding `font-family: Monospace;` to your body element's style declaration.

```` html
<style>
  body {
    color: green;
    font-family: Monospace;
  }
</style>

<h1>Hello World</h1>
````
----

#### Prioritize One Style Over Another
Sometimes your HTML elements will receive multiple styles that conflict with one another.
Create a CSS `class` called `pink-text` that gives an element the color pink. Give your `h1` element the class of pink-text.

```` html
<style>
  body {
    color: green;
    font-family: Monospace;
  }
  .pink-text {
    color: pink;
  }
</style>

<h1 class="pink-text">Hello World</h1>
````
----

#### Override Styles in Subsequent CSS
Our `pink-text` class overrode our `body` element's CSS declaration!

Create an additional CSS class called `blue-text` that gives an element the color blue. Make sure it's below your `pink-text` class declaration. Apply the `blue-text` class to your `h1` element in addition to your `pink-text` class, and let's see which one wins.

**NB :** the order of the class declarations in the `style` section is important. *The second declaration will always take precedence over the first*. Because `.blue-text` is declared second, it overrides the attributes of `.pink-text`.

```` html
<style>
  body {
    color: green;
    font-family: Monospace;
  }
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
</style>

<h1 class="blue-text pink-text">Hello World</h1>
````
----

#### Override Class Declarations by Styling ID Attributes
We just proved that browsers read CSS from top to bottom. That means that, in the event of a conflict, the browser will use whichever CSS declaration came last.
Let's override your `pink-text` and `blue-text` classes, and make your `h1` element `orange`, by giving the `h1` element an `id` and then styling that id.
Give your `h1` element the `id` attribute of `orange-text`.

```` html
<style>
  #orange-text {
    color: orange;
  }
  body {
    color: green;
    font-family: Monospace;
  }
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
</style>

<h1 id="orange-text" class="blue-text pink-text">Hello World</h1>
````
----

#### Override Class Declarations with Inline Styles
Use an `in-line style` to try to make our` h1` element white.

```` html
<style>
  #orange-text {
    color: orange;
  }
  body {
    color: green;
    font-family: Monospace;
  }
  .pink-text {
    color: pink;
  }
  .blue-text {
    color: blue;
  }
</style>

<h1 id="orange-text" class="blue-text pink-text" style="color: white">
  Hello World
</h1>
````
----

#### Override All Other Styles by using Important
There's one last way to override CSS. This is the most powerful method of all. But before we do it, let's talk about why you would ever want to override CSS.

In many situations, you will use CSS libraries. These may accidentally override your own CSS. So when you absolutely need to be sure that an element has specific CSS, you can use `!important`.
Let's add the keyword `!important` to your `pink-text` element's color declaration to make 100% sure that your h1 element will be pink.

```` html
<style>
  #orange-text {
    color: orange;
  }
  body {
    color: green;
    font-family: Monospace;
  }
  .pink-text {
    color: pink !important;
  }
  .blue-text {
    color: blue;
  }
</style>

<h1 id="orange-text" class="blue-text pink-text" style="color: white">
  Hello World
</h1>
````
----

#### Use Hex Code for Specific Colors
Replace the word `black` in our body element's background-color with its hex code representation, `#000000`.

```` html
<style>
  body {
    color: #000000;
  }
</style>
````
----

#### Use Hex Code to Mix Colors
Replace the color words in our `style` element with their correct **hex** codes.

```` html
<style>
  .red-text {
    color: #FF0000;
  }
  .green-text {
    color: #00FF00;
  }
  .dodger-blue-text {
    color: #2998E4;
  }
  .orange-text {
    color: #FFA500;
  }
</style>

<h1 class="red-text">I am red!</h1>
<h1 class="green-text">I am green!</h1>
<h1 class="dodger-blue-text">I am dodger blue!</h1>
<h1 class="orange-text">I am orange!</h1>
````
----

#### Use Abbreviated Hex Code
Go ahead, try using the abbreviated hex codes to color the correct elements.

| Color       | Short Hex Code  |  
|-------------|:---------------:|
| Cyan        | #0FF            |
| Green       | #0F0            |
| Red         | #F00            |
| Fuchsia     | #F0F            |

```` html
<style>
  .red-text {
    color: #F00;
  }
  .green-text {
    color: #0F0;
  }
  .fuchsia-text {
    color: #F0F;
  }
  .cyan-text {
    color: #0FF;
  }
</style>

<h1 class="red-text">I am red!</h1>
<h1 class="green-text">I am green!</h1>
<h1 class="fuchsia-text">I am fuchsia!</h1>
<h1 class="cyan-text">I am cyan!</h1>
````
----

#### Use RGB values to Color Elements
Another way you can represent colors in CSS is by using `RGB` values. Let's replace the hex code in our `body` element's background color with the `RGB` value for black: `rgb(0, 0, 0)`.

```` html
<style>
  body {
    background-color: rgb(0, 0, 0);
  }
</style>
````
----

#### Use RGB to Mix Colors
Just like with hex code, you can mix colors in `RGB` by using combinations of different values. Replace the color words in our `style` element with their correct RGB values.

| Color       | RGB                 |  
|-------------|---------------------|
| Blue        | rgb(0, 0, 255)      |
| Red         | rgb(255, 0, 0)      |
| Orchid      | rgb(218, 112, 214)  |
| Sienna      | rgb(160, 82, 45)    |

```` html
<style>
  .red-text {
    color: rgb(255, 0, 0);
  }
  .blue-text {
    color: rgb(0, 0, 255);
  }
  .orchid-text {
    color: rgb(218, 112, 214);
  }
  .sienna-text {
    color: rgb(160, 82, 45);
  }
</style>

<h1 class="red-text">I am red!</h1>
<h1 class="blue-text">I am green!</h1>
<h1 class="orchid-text">I am fuchsia!</h1>
<h1 class="sienna-text">I am cyan!</h1>
````
----

#### Use CSS Variables To Change Several Elements At Once
In the `penguin` class, change the `black` value to `gray`, the gray value to `white`, and the `yellow` value to `orange`.

````html
<style>
  .penguin {
    /* change code below */
    --penguin-skin: gray;
    --penguin-belly: white;
    --penguin-beak: orange;
    /* change code above */
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    background: var(--penguin-skin, gray);
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    background: var(--penguin-skin, gray);
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 0%;
    left: -5%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(45deg);
    z-index: -1;
  }

  .left-hand {
    top: 0%;
    left: 75%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: var(--penguin-belly, white);
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;  
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;  
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;  
  }

  .sparkle {
    top: 25%;
    left: 15%;
    background: white;
    width: 35%;
    height: 35%;
    border-radius: 50%;  
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;  
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;  
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: var(--penguin-beak, orange);
    width: 20%;
    height: 10%;
    border-radius: 50%;  
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: var(--penguin-beak, orange);
    width: 16%;
    height: 10%;
    border-radius: 50%;  
  }

  body {
    background:#c6faf1;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----

#### Create a custom CSS Variable
In the `penguin` class, create a variable name `--penguin-skin` and give it a value of `gray`.

````html
<style>
  .penguin {
    /* add code below */
    --penguin-skin: gray;
    /* add code above */
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    background: black;
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    background: black;
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 0%;
    left: -5%;
    background: black;
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(45deg);
    z-index: -1;
  }

  .left-hand {
    top: 0%;
    left: 75%;
    background: black;
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: white;
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: white;
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: white;
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: orange;
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;  
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: orange;
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;  
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;  
  }

  .sparkle {
    top: 25%;
    left: 15%;
    background: white;
    width: 35%;
    height: 35%;
    border-radius: 50%;  
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;  
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;  
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: orange;
    width: 20%;
    height: 10%;
    border-radius: 50%;  
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: orange;
    width: 16%;
    height: 10%;
    border-radius: 50%;  
  }

  body {
    background:#c6faf1;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----

#### Use a custom CSS Variable
Apply the `--penguin-skin` variable to the `background` property of the `penguin-top`, `penguin-bottom`, `right-hand` and `left-hand` classes.

````html
<style>
  .penguin {
    --penguin-skin: gray;
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    /* change code below */
    background: var(--penguin-skin);
    /* change code above */
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    /* change code below */
    background: var(--penguin-skin);
    /* change code above */
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 0%;
    left: -5%;
    /* change code below */
    background: var(--penguin-skin);
    /* change code above */
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(45deg);
    z-index: -1;
  }

  .left-hand {
    top: 0%;
    left: 75%;
    /* change code below */
    background: var(--penguin-skin);
    /* change code above */
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: white;
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: white;
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: white;
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: orange;
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;  
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: orange;
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;  
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .sparkle {
    top: 25%;
    left: 15%;
    background: white;
    width: 35%;
    height: 35%;
    border-radius: 50%;
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: orange;
    width: 20%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: orange;
    width: 16%;
    height: 10%;
    border-radius: 50%;
  }

  body {
    background:#c6faf1;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----

#### Attach A Fallback Value To A CSS Variable
Add a fallback value of `black` to the `background` property of `penguin-top` and `penguin-bottom` classes. This style will be applied because of a typo in the variable name.

````html
<style>
  .penguin {
    --penguin-skin: gray;
    --penguin-belly: white;
    --penguin-beak: orange;
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    /* change code below */
    background: var(--penguin-skin, black);
    /* change code above */
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    /* change code below */
    background: var(--penguin-skin, black);
    /* change code above */
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 0%;
    left: -5%;
    background: var(--penguin-skin, black);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(45deg);
    z-index: -1;
  }

  .left-hand {
    top: 0%;
    left: 75%;
    background: var(--penguin-skin, black);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: var(--penguin-belly, white);
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .sparkle {
    top: 25%;
    left: 15%;
    background: white;
    width: 35%;
    height: 35%;
    border-radius: 50%;
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: var(--penguin-beak, orange);
    width: 20%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: var(--penguin-beak, orange);
    width: 16%;
    height: 10%;
    border-radius: 50%;
  }

  body {
    background:#c6faf1;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----

#### Cascading CSS Variables
Define a variable named `--penguin-belly` in the `:root` selector and give it the value of `pink`. You can then see how the value will cascade down to change the value to pink, anywhere that variable is used.

````html
<style>
  :root {
    /* add code below */
    --penguin-belly: pink;
    /* add code above */
  }

  body {
    background: var(--penguin-belly, #c6faf1);
  }

  .penguin {
    --penguin-skin: gray;
    --penguin-beak: orange;
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: var(--penguin-belly, white);
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    background: var(--penguin-skin, gray);
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    background: var(--penguin-skin, gray);
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 0%;
    left: -5%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(45deg);
    z-index: -1;
  }

  .left-hand {
    top: 0%;
    left: 75%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .sparkle {
    top: 25%;
    left: 15%;
    background: white;
    width: 35%;
    height: 35%;
    border-radius: 50%;
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: var(--penguin-beak, orange);
    width: 20%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: var(--penguin-beak, orange);
    width: 16%;
    height: 10%;
    border-radius: 50%;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----

#### Change A Variable For A Specific Area
Change the value of `--penguin-belly` to `white` in the `penguin` class.

````html
<style>
  :root {
    --penguin-skin: gray;
    --penguin-belly: pink;
    --penguin-beak: orange;
  }

  body {
    background: var(--penguin-belly, #c6faf1);
  }

  .penguin {    
    /* add code below */
    --penguin-belly: white;
    /* add code above */

    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: 300px;
    height: 300px;
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: var(--penguin-belly, pink);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: var(--penguin-belly, pink);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: var(--penguin-belly, pink);
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    background: var(--penguin-skin, gray);
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    background: var(--penguin-skin, gray);
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 0%;
    left: -5%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(45deg);
    z-index: -1;
  }

  .left-hand {
    top: 0%;
    left: 75%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .sparkle {
    top: 25%;
    left: 15%;
    background: white;
    width: 35%;
    height: 35%;
    border-radius: 50%;
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: var(--penguin-beak, orange);
    width: 20%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: var(--penguin-beak, orange);
    width: 16%;
    height: 10%;
    border-radius: 50%;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----

#### Use A Media Query To Change A Variable
In the `:root` selector of the media query, change it so --penguin-size is redefined and given a value of 200px. Also, redefine --penguin-skin and give it a value of black. Then resize the preview to see this change in action.

````html
<style>
  :root {
    --penguin-size: 300px;
    --penguin-skin: gray;
    --penguin-belly: white;
    --penguin-beak: orange;
  }

  @media (max-width: 350px) {
    :root {
      /* add code below */
      --penguin-size: 200px;
      --penguin-skin: black;
      /* add code above */
    }
  }

  .penguin {
    position: relative;
    margin: auto;
    display: block;
    margin-top: 5%;
    width: var(--penguin-size, 300px);
    height: var(--penguin-size, 300px);
  }

  .right-cheek {
    top: 15%;
    left: 35%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .left-cheek {
    top: 15%;
    left: 5%;
    background: var(--penguin-belly, white);
    width: 60%;
    height: 70%;
    border-radius: 70% 70% 60% 60%;
  }

  .belly {
    top: 60%;
    left: 2.5%;
    background: var(--penguin-belly, white);
    width: 95%;
    height: 100%;
    border-radius: 120% 120% 100% 100%;
  }

  .penguin-top {
    top: 10%;
    left: 25%;
    background: var(--penguin-skin, gray);
    width: 50%;
    height: 45%;
    border-radius: 70% 70% 60% 60%;
  }

  .penguin-bottom {
    top: 40%;
    left: 23.5%;
    background: var(--penguin-skin, gray);
    width: 53%;
    height: 45%;
    border-radius: 70% 70% 100% 100%;
  }

  .right-hand {
    top: 5%;
    left: 25%;
    background: var(--penguin-skin, black);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 120% 30%;
    transform: rotate(130deg);
    z-index: -1;
    animation-duration: 3s;
    animation-name: wave;
    animation-iteration-count: infinite;
    transform-origin:0% 0%;
    animation-timing-function: linear;
  }

  @keyframes wave {
      10% {
        transform: rotate(110deg);
      }
      20% {
        transform: rotate(130deg);
      }
      30% {
        transform: rotate(110deg);
      }
      40% {
        transform: rotate(130deg);
      }  
    }

  .left-hand {
    top: 0%;
    left: 75%;
    background: var(--penguin-skin, gray);
    width: 30%;
    height: 60%;
    border-radius: 30% 30% 30% 120%;
    transform: rotate(-45deg);
    z-index: -1;
  }

  .right-feet {
    top: 85%;
    left: 60%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(-80deg);
    z-index: -2222;
  }

  .left-feet {
    top: 85%;
    left: 25%;
    background: var(--penguin-beak, orange);
    width: 15%;
    height: 30%;
    border-radius: 50% 50% 50% 50%;
    transform: rotate(80deg);
    z-index: -2222;
  }

  .right-eye {
    top: 45%;
    left: 60%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .left-eye {
    top: 45%;
    left: 25%;
    background: black;
    width: 15%;
    height: 17%;
    border-radius: 50%;
  }

  .sparkle {
    top: 25%;
    left:-23%;
    background: white;
    width: 150%;
    height: 100%;
    border-radius: 50%;
  }

  .blush-right {
    top: 65%;
    left: 15%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .blush-left {
    top: 65%;
    left: 70%;
    background: pink;
    width: 15%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-top {
    top: 60%;
    left: 40%;
    background: var(--penguin-beak, orange);
    width: 20%;
    height: 10%;
    border-radius: 50%;
  }

  .beak-bottom {
    top: 65%;
    left: 42%;
    background: var(--penguin-beak, orange);
    width: 16%;
    height: 10%;
    border-radius: 50%;
  }

  body {
    background:#c6faf1;
  }

  .penguin * {
    position: absolute;
  }
</style>
<div class="penguin">
  <div class="penguin-bottom">
    <div class="right-hand"></div>
    <div class="left-hand"></div>
    <div class="right-feet"></div>
    <div class="left-feet"></div>
  </div>
  <div class="penguin-top">
    <div class="right-cheek"></div>
    <div class="left-cheek"></div>
    <div class="belly"></div>
    <div class="right-eye">
      <div class="sparkle"></div>
    </div>
    <div class="left-eye">
      <div class="sparkle"></div>
    </div>
    <div class="blush-right"></div>
    <div class="blush-left"></div>
    <div class="beak-top"></div>
    <div class="beak-bottom"></div>
  </div>
</div>
````
----
