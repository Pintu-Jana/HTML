# BASIC.

https://github.com/Asabeneh/30-Days-Of-HTML

HTML is the most widely used language for developing web pages.

It define the structure of the websites and formats web pages.

HTML is not a real programming language in itself. It is a set of markup tags that describe the content and present it in a structured and formatted way. We cannot code much logic into HTML. There are no variables or loops.

TML tags consist of a tag name inside of the angle brackets (<>).

**Two tags with text in between them is an element.**

### Attribute

HTML attributes provide additional information about the element. An attribute can added only in the opening tag. It will be difficult to list down all HTML attributes but we can list down the most common ones.

- alt - to add information about added image, use with *img* element.
- autocompelete - to enable auto complete feature of a form, use with form and input.
- autofocus - enable auto focus of input fields
- autoplay - allows playing an audio/video on the page loads
- charset - enable character encoding of meta tag
- checked - to make a checkbox checked of an input element
- class - to give a common identifier for HTML elements
- cols - to determine the width of a textarea element
- contenteditable - make any element editable
- download - allows a link to download a resource(image, pdf, PPT, etc)
- draggable - to make an element draggable, apply to all elements
- for - to connect/bound a label element with a specific input field, use with a label tag
- href - to specify a URL or a path of a resource, use with a link tag
- id - a unique id for an HTML element, apply to all elements
- lang - specifies the language of the page
- type - specifies the type of the element and it uses with only a certain elements
- src - to specify URL of a media file(img, audio, video, source, embed, script)
 **example:-**

```html
<h2>Overview of HTML</h2>
 <div>HTML is a ...</div> 
<link rel="stylesheet" type="text/css" href="style.css" />
```

### class

The class attribute defines a class that is used for styling in CSS or Domain Object Model (DOM) manipulation; for example: 

**`<p class="normal">...</p>`**

The value may appear once and only once per page so as to identify a single element.

### id

The id attribute defines an ID that is similar in purpose to element class, but it has to be unique; for example: 

`**<div id="footer">...</div>**`

The value may appear multiple times per page.
• A particular class attribute value may contain multiple class names, each separated by a space.

You can say **CLass Selector** is a superior form because it just can be applied to multiple elements, and it is used much more common than **ID Selector** Only use **ID Selector**
 if you're sure it's only going to be applied to one element!

### style

The style attribute defines inline CSS to style an element; for example: 

**`<font style="font-size:20px">...</font>`**

### Each HTML element can have id attributes, class attributes, or both:

```html

<div id="main" class="large">   
Lorem ipsum dolor sit amet,   Duis sit amet neque eu.
 </div>
```