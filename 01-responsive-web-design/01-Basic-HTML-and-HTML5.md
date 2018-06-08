## Basic HTML and HTML5 Challenges

> HTML, or HyperText Markup Language, is a markup language used to describe the structure of a web page. It uses a special syntax or notation to organize and give information about the page to the browser. Elements usually have opening and closing tags that surround and give meaning to content. For example, there are different tag options to place around text to show whether it is a heading, a paragraph, or a list.

- [Say Hello to HTML Elements](#say-hello-to-html-elements)
- [Headline with the `h2` Element](#headling-with-the-h2-element)
- [Inform with the Paragraph Element](#inform-with-the-paragraph-element)
- [Uncomment HTML](#uncomment-html)
- [Comment HTML](#comment-html)
- [Fill in the Blank with Placeholder Text](#fill-in-the-blank-with-placeholder-text)
- [Delete HTML](#delete-html)
- [Introduction to HTML5 Elements](#introduction-to-html5-elements)
- [Change the Color of Text](#change-the-color-of-text)
- [Link to External Pages with Anchor Elements](#link-to-external-pages-with-anchor-elements)
- [Link to Internal Sections of a Page with Anchor Elements](#link-to-internal-sections-of-a-page-with-anchor-elements)
- [Nest an Anchor Element within a Paragraph](#nest-an-anchor-element-within-a-paragraph)
- [Make Dead Links using the Hash Symbol](#make-dead-links-using-the-hash-symbol)
- [Turn an Image into a Link](#turn-an-image-into-a-link)
- [Create a Bulleted Unordered List](#create-a-bulleted-unordered-list)
- [Create an Ordered List](#create-an-ordered-list)
- [Create a Text Field](#create-a-text-field)
- [Add Placeholder Text to a Text Field](#add-placeholder-text-to-a-text-field)
- [Create a Form Element](#create-a-form-element)
- [Add a Submit Button to a Form](#add-a-submit-button-to-a-form)
- [Use HTML5 to Require a Field](#use-html5-to-require-a-field)
- [Create a Set of Radio Button](#create-a-set-of-radio-button)
- [Create a Set of Checkboxes](#create-a-set-of-checkboxes)
- [Check Radio Buttons and Checkboxes by Default](#check-radio-buttons-and-checkboxes-by-default)
- [Nest Many Elements within a Single Div Element](#nest-many-elements-within-a-single-div-element)
- [Set the ID of an Element](#set-the-id-of-an-element)
- [Declare the Doctype of an HTML Document](#declare-the-doctype-of-an-html-document)
- [Define the Head and Body of an HTML Document](#define-the-head-and-body-of-an-html-document)

----

#### Say Hello to HTML Elements
To pass the test on this challenge, change your `h1` element's text to say "Hello World" instead of "Hello".

```` html
<h1>Hello World</h1>
````
----

#### Headline with the `h2` Element
Add an `h2` tag that says "CatPhotoApp" to create a second HTML `element` below your "Hello World" `h1` element.

```` html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
````
----

#### Inform with the Paragraph Element
Create a `p` element below your `h2` element, and give it the text "Hello Paragraph".

```` html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Hello Paragraph</p>
````
----

#### Uncomment HTML
Uncomment your `h1`, `h2` and `p` elements.

```` html
<!-- -->
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Hello Paragraph</p>
````
----

#### Comment HTML
Comment out your `h1` element and your `p` element, but leave your `h2` element uncommented.

```` html
<h1>Hello World</h1>
<!-- <h2>CatPhotoApp</h2> -->
<p>Hello Paragraph</p>
````
----

#### Fill in the Blank with Placeholder Text
Replace the text inside your `p` element with the first few words of this kitty ipsum text: `Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff`.

```` html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
````
----

#### Delete HTML
Delete your `h1` element so we can simplify our view.

```` html
<h2>CatPhotoApp</h2>
<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
````
----

#### Introduction to HTML5 Elements
Create a second `p` element after the existing `p` element with the following
kitty ipsum text: "Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched."
Wrap the paragraphs with an opening and closing `main` tag.

```` html
<h2>CatPhotoApp</h2>
<main>
  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
````
----

#### Change the Color of Text
Change your `h2` element's style so that its text color is red.

```` html
<h2 style="color: red">CatPhotoApp</h2>
<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
````
----

#### Link to External Pages with Anchor Elements
Create an `a` element that links to `http://freecatphotoapp.com` and has "cat photos" as its anchor text.

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
<a href="http://freecatphotoapp.com">
  <img  class="smaller-image thick-green-border"
        src="https://bit.ly/fcc-relaxing-cat"
        alt="relaxing cat photograph">
</a>
````
----

#### Link to Internal Sections of a Page with Anchor Elements
Change your external link to an internal link by changing the `href` attribute to "#footer" and the text from "cat photos" to "Jump to Bottom".
Remove the target attribute from the anchor tag since this causes the linked document to open in a new window tab. Then add an `id` attribute with a value of "footer" to the `<footer>` element at the bottom of the page.

```` html
<h2>CatPhotoApp</h2>
<main>  
  <a href="#footer">Jump to Bottom</a>  
  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
  <p>
    Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.
  </p>
  <p>
    Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.
  </p>
</main>
<footer id="footer">Copyright Cat Photo App</footer>
````
----

#### Nest an Anchor Element within a Paragraph
`Nesting` just means putting one element inside of another element. Now nest your existing `a` element within a new `p` element (just after the existing `h2` element) so that the surrounding paragraph says "View more cat photos", but where only "cat photos" is a link, and the rest of the text is plain text.

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
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p>View more <a href="http://freecatphotoapp.com">cat photos</a></p>
<img  class="smaller-image thick-green-border"
      src="https://bit.ly/fcc-relaxing-cat"
      alt="relaxing cat photograph">
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

#### Make Dead Links using the Hash Symbol
Sometimes you want to add `a` elements to your website before you know where they will link. Replace the value of your `a` element's `href` attribute with a `#`, also known as a hash symbol, to turn it into a dead link.

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
  p {
    font-size: 16px;
    font-family: Monospace;
  }
  h2 {
    font-family: Lobster;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<p>View more <a href="#">cat photos</a></p>
<img  class="smaller-image thick-green-border"
      src="https://bit.ly/fcc-relaxing-cat"
      alt="relaxing cat photograph">
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

#### Turn an Image into a Link
You can make elements into links by nesting them within an `a` element.
Place the existing image element within an anchor element. Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.

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

#### Create a Bulleted Unordered List
Remove the last two `p` elements and create an unordered list of three things that cats love at the bottom of the page.

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
````
----

#### Create an Ordered List
HTML has a special element for creating `ordered lists`, or numbered-style lists. Create an ordered list of the top 3 things cats hate the most.

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

````
----

#### Create a Text Field
Create an input element of type `text` below your lists.

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
<input type="text">
````
----

#### Add Placeholder Text to a Text Field
The placeholder text is what appears in your text `input` before your user has input anything. Set the `placeholder` value of your text `input` to "cat photo URL".

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
<input type="text" placeholder="cat photo URL">
````
----

#### Create a Form Element
You can build web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action on your `form` element. Nest your text field in a `form` element. Add the `action="/submit-cat-photo"` attribute to this form element.

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

<form action="/submit-cat-photo">
  <input type="text" placeholder="cat photo URL">
</form>
````
----

#### Add a Submit Button to a Form
Let's add a `submit` button to your form. Clicking this button will send the data from your form to the URL you specified with your form's `action` attribute. Add a submit button to your `form` element with type `submit` and "Submit" as its text.

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

<form action="/submit-cat-photo">
  <input type="text" placeholder="cat photo URL">
  <button type="submit">Submit</button>
</form>
````
----

#### Use HTML5 to Require a Field
You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.
Make your text `input` a `required` field, so that your user can't submit the form without completing this field. Then try to submit the form without inputing any text. See how your HTML5 form notifies you that the field is required?

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

<form action="/submit-cat-photo">
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
````
----

#### Create a Set of Radio Button
You can use `radio buttons` for questions where you want the user to only give you one answer. Add a pair of radio buttons to your form. One should have the option of `indoor` and the other should have the option of `outdoor`.

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

<form action="/submit-cat-photo">
  <label><input type="radio" name="indoor"> Indoor</label>
  <label><input type="radio" name="outdoor"> Outdoor</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
````
----

#### Create a Set of Checkboxes
Forms commonly use checkboxes for questions that may have more than one answer.
Add to your form a set of three checkboxes. Each checkbox should be nested within its own `label` element. All three should share the `name` attribute of `personality`.

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

<form action="/submit-cat-photo">
  <label><input type="radio" name="indoor"> Indoor</label>
  <label><input type="radio" name="outdoor"> Outdoor</label>
  <label><input type="checkbox" name="personality"> Loving</label>
  <label><input type="checkbox" name="personality"> Playful</label>
  <label><input type="checkbox" name="personality"> Charming</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
````
----

#### Check Radio Buttons and Checkboxes by Default
Set the first of your `radio buttons` and the first of your `checkboxes` to both be checked by default.

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

#### Nest Many Elements within a Single Div Element
Nest your "Things cats love" and "Things cats hate" lists all within a single `div` element.

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
<div>
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

#### Set the ID of an Element
In addition to classes, each HTML element can also have an `id` attribute. Give your form element the id `cat-photo-form`.

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

#### Declare the Doctype of an HTML Document
Add a `DOCTYPE` tag for `HTML5` to the top of the blank HTML document. Under it, add opening and closing `html` tags, which wrap around an `h`1 element. The heading can include any text.

```` html
<!DOCTYPE html>
<html>
  <h1>Declare the DOCTYPE of an HTML document</h1>
</html>
````
----

#### Define the Head and Body of an HTML Document
Edit the markup so there's a `head` and a `body`. The `head` element should only include the `title`, and the `body` element should only include the `h1` and `p`.

```` html
<!DOCTYPE html>
<html>
  <head>
    <title>The Best Page Ever</title>
  </head>
  <body>
    <h1>The Best Page Ever</h1>
    <p>
      Cat ipsum dolor sit amet, jump launch to pounce upon little yarn mouse, bare fangs at toy run hide in litter box until treats are fed. Go into a room to decide you didn't want to be in there anyway.
      I like big cats and i can not lie kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Meow i could pee on this if i had the energy for slap owner's face at 5am until human fills food dish yet scamper. Knock dish off table head butt cant eat out of my own dish scratch the furniture. Make meme, make cute face. Sleep in the bathroom sink chase laser but pee in the shoe. Paw at your fat belly licks your face and eat grass, throw it back up kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.
    </p>
  </body>
</html>
````
