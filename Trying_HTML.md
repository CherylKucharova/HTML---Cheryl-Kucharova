# Tech Stack & Web Environment: HTML

## HTML Introduction

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading </h1>
<p>My first paragraph.</p>

</body>
</html>

----
## HTML Attributes

### The href Atrribute
The <.a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to: </br> <a href="https://itbss.lms.siakad.tech/beranda">Visit LMS</a>

### The src Atriibute
The <.img> tag is used to embed an image in an HTML page. The .src attribute specifies the path to the image to be displayed: 
<!DOCTYPE html>
<html>
<body>

<h2>The src Attribute</h2>
<p>HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:</p>
<img src="https://pin.it/2OVUIW3JD" width="500" height="600">

</body>
</html>


### The width and height Attibutes
The <.img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

### The alt Attribute
The required alt attribute for the <.img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

----
## HTML Headings

HTML headings are defined with the <.h1> to <.h6> tags.
<.h1> defines the most important heading. <.h6> defines the least important heading. </br> Example:

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

<h1 style="font-size:60px;">Cheryl Kucharova</h1>

----
## HTML Paragraphs

### HTML Paragraphs
The HTML <.p> element defines a paragraph.
A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.
The <.hr> tag is an empty tag, which means that it has no end tag.

Example: </br>
<p>Paragraf pertama</p>
<p>Paragraf Kedua</p>

<p>
  This paragraph
  contains a lot of lines
  in the source code,
  but the browser
  ignores it.
</p>

<p>
  This paragraph
  contains       a lot of spaces
  in the source      code,
  but the      browser
  ignores it.
</p>

### HTML Horizontal Rules
The <.hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule. </br>

The <.hr> element is used to separate content (or define a change) in an HTML page: 
<h1>This is heading 1</h1>
<p>This is some text</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text</p>
<hr>

### HTML Line Breaks
The HTML <br> element defines a line break.
Use <.br> if you want a line break (a new line) without starting a new paragraph: <br>

Example:
<p>This is<br>a paragraph<br>with line breaks.</p>

The <.br> tag is an empty tag, which means that it has no end tag.

### The Poem Problem
<p>
  Roses are red.

  Violets are blue.

  Sugar is sweet.

  And so are you.
</p>

## Solution - The HTML <.pre> Element
<html>
<body>
<pre>
  Roses are red.

  Violets are blue.

  Sugar is sweet.

  And so are you.
</pre>
</body>
</body>
<html>

----
## HTML Styles
The HTML style attribute is used to add styles to an element, such as color, font, size, and more:

<html>
<body>
<p>I am normal</p>
<p style="color:red;">I am red</p>
<p style="color:blue;">I am blue</p>
<p style="font-size:50px;">I am big</p>
</body>
</html>

### Background Color 
<html>
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph</p>

</body>
</html>

<body>
<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>
</body>

### Text Color
<html>
<body>

<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>

### Fonts
<html>
<body>
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
</body>
</html>

### Text Size
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>

### Text Alignment
<html>
  <body>
    <h1 style="text-align:center;">Centered Heading</h1>
    <p style="text-align:center;">Centered paragraph.</p>
  </body>
</html>

----
## HTML Text Formatting

### HTML <.b> and <.strong> Elements
<b>This text is bold</b> <br>
<strong>This text is important!</strong>

### HTML <.i> and <.em> Elements
<i>This text is italic</i> <br>
<em>This text is emphasized</em>

### HTML <.small> Element
<small>This is some smaller text.</small>

### HTML <.mark> Element
defines text that should be marked or highlighted:
<p>Do not forget to buy <mark>milk</mark> today.</p>

### HTML <.del> Element
<p>My favorite color is <del>blue</del> red.</p>

### HTML <.ins> Element
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

### HTML <.sub> Element
defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:
<p>This is <sub>subscripted</sub> text.</p>

### HTML <.sup> Element
defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
<p>This is <sup>superscripted</sup> text.</p>

----
## HTML Quotation and Citation Elements
