<h1 align="center">
    <a href="https://github.com/Toufiq-Gilani" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/8488/8488931.png" alt="Logo" width="150" height="150">
    </a>
</h1>

<h1 align="center">HTML Documentation 📘📗<br><br></h1>

<div align="center">

<h2 align="center">

[![](https://img.shields.io/badge/ALL-TOPIC-00abe1?style=for-the-badge&=appveyor)](https://twitter.com/GilaniRabbu)

</h2>

[![](https://img.shields.io/badge/TOPIC%201-HTML%20Introduction-00abe1)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%202-HTML%20Elements%20and%20Attributes-00abe1)](https://codepen.io/toufiq-gilani)
[![](https://img.shields.io/badge/TOPIC%203-HTML%20Basic%20Structure%20and%20Inside%20Head%20Tag-00abe1)](https://twitter.com/GilaniRabbu)

[![](https://img.shields.io/badge/TOPIC%204-Environment%20Setup%20and%20Debugging-00abe1)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%205-Typography-00abe1)](https://codepen.io/toufiq-gilani)
[![](https://img.shields.io/badge/TOPIC%206-HTML%20Lists%20and%20Images-00abe1)](https://twitter.com/GilaniRabbu)

[![](https://img.shields.io/badge/TOPIC%207-HTML%20Block%20and%20Inline%20Elements-00abe1)](https://twitter.com/GilaniRabbu)

[![](https://img.shields.io/badge/TOPIC%208-HTML%20Styles%20and%20Selectors-0049ff)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%209-HTML%20Forms-0049ff)](https://codepen.io/toufiq-gilani)
[![](https://img.shields.io/badge/TOPIC%2010-HTML%20Quotation%20and%20Citation-0049ff)](https://twitter.com/GilaniRabbu)

[![](https://img.shields.io/badge/TOPIC%2011-HTML%20Favicon%20and%20Iframes-0049ff)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%2012-HTML%20Media%20and%20Graphics-0049ff)](https://codepen.io/toufiq-gilani)

[![](https://img.shields.io/badge/TOPIC%2013-HTML%20Computer%20Code%20and%20Progress%20Bars-0049ff)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%2014-HTML%20Entities%20and%20Symbol-0049ff)](https://codepen.io/toufiq-gilani)

[![](https://img.shields.io/badge/TOPIC%2015-HTML%20Emojis%20and%20Icon-bcfd4c)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%2016-HTML%20Responsive%20Web%20Design-bcfd4c)](https://codepen.io/toufiq-gilani)
[![](https://img.shields.io/badge/TOPIC%2017-HTML%20Links-bcfd4c)](https://twitter.com/GilaniRabbu)

[![](https://img.shields.io/badge/TOPIC%2018-HTML%20Tables-bcfd4c)](https://github.com/Toufiq-Gilani)
[![](https://img.shields.io/badge/TOPIC%2019-HTML%20Semantic%20Elements-bcfd4c)](https://codepen.io/toufiq-gilani)
[![](https://img.shields.io/badge/TOPIC%2020-Web%20Accessibility-bcfd4c)](https://twitter.com/GilaniRabbu)

</div>

## <br>

<h2 align="center">TOPIC 1<br>HTML Introduction</h2>

<h3>What is HTML?</h3>

- HTML stands for Hyper Text Markup Language.
- HTML is the standard markup language for creating Web pages.
- HTML describes the structure of a Web page.
- HTML consists of a series of elements.
- HTML elements tell the browser how to display the content.
- With the help of markup tag we can display text, image, video etc on the webpage.

##

<h3>History of HTML</h3>

- Tim Berners-Lee invented HTML in 1991

##

<h3>A Simple HTML Document</h3>

```html
<!DOCTYPE html>
<html>
<head>

<title>Page Title</title>

</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

##

<h3>Example Explained</h3>

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document.
- The `<html>` element is the root element of an HTML page.
- The `<head>` element contains meta information about the HTML page.
- The `<title>` element specifies a title for the HTML page.
- The `<body>` element defines the document's body, and is a container for all the visible contents.
- The `<h1>` element defines a large heading.
- The `<p>` element defines a paragraph.

## <br>

<h2 align="center">TOPIC 2<br>HTML Elements and Attributes</h2>

<h3>What is an HTML Element?</h3>

- An HTML element is defined by a start tag, some content, and an end tag:
- `<tagname> Content goes here... </tagname>` ;
- The HTML element is everything from the start tag to the end tag:
- `<h1>My First Heading</h1>` ;
- `<p>My first paragraph.</p>` ;

##

<h3>Example Explained</h3>

| Start tag | Element content     | End tag |
| :-------- | :------------------ | :------ |
| `<h1>`    | My First Heading    | `</h1>` |
| `<p>`     | My first paragraph. | `</p>`  |
| `<br>`    | none                | none    |

##

<h3>What Are The Types of Tag?</h3>

- There Are 2 Types of HTML Tag.
  + Pair / Container Tag.
  + Empty Tag.
- Pair tag has starting and ending, Empty tag has no closing tag.

##

<h3>Example</h3>

```html
<!-- Some examples of Pair / Container Tag -->
<html> ... </html>
<head> ... </head>
<body> ... </body>
<p> ... </p>
<h1> ... </h1>

<!-- Some examples of Empty Tag -->
<br>
<hr>
<img>
<input>
```

##

<h3>HTML Attributes</h3>

- All HTML elements can have attributes.
- Attribute helps tag to extend its capabilities.
- In the following example, `<img>` is tag; src, height, width are the attributes.
- Attributes usually come in name / value pairs like: `name="value"` ;
- The `href` attribute of `<a>` specifies the URL of the page the link goes to.
- The `src` attribute of `<img>` specifies the path to the image to be displayed.
- The `width` and `height` attributes of `<img>` provide size information for images.
- The `alt` attribute of `<img>` provides an alternate text for an image.
- The `style` attribute is used to add styles to an element, such as color, font, size, and more.
- The `lang` attribute of the `<html>` tag declares the language of the Web page.
- The `title` attribute defines some extra information about an element.
- Example: `<img src="img_nature.jpg" width="500" height="600">` ;

## <br>

<h2 align="center">TOPIC 3<br>HTML Basic Structure and Inside Head Tag</h2>

<h3>HTML Basic Structure</h3>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Title Here</title>
</head>
<body>
    Content of the Webpage
</body>
</html>
```

##

<h3>Example Explained</h3>

- Always use `<!DOCTYPE html>` to tell the browser what type of document to expect; remember it is not a tag, just a declaration.
- Every HTML document must have `<html>` pair tag and Inside `<html>` tag we use `<head>` and `<body>` as the example shows above.
- Inside `head` tag we use `meta` tag, set title etc.
- Inside `body` tag we write everything that we want to display on web page.

##

<h3>Inside Head Tag</h3>

```html
<head>
    <!-- Define the character set used: -->
    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <!-- Setting the viewport to make your website look good on all devices: -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Define a description of your web page: -->
    <meta name="description" content="Free Complete HTML Tutorial For Web Development">

    <!-- Define keywords for search engines: -->
    <meta name="keywords" content="HTML, html, html tutorial, web development">

    <!-- Define the author of a page: -->
    <meta name="author" content="Toufiq Gilani R">

    <meta name="robots" content="INDEX, FOLLOW">

    <!-- Insert CSS -->
    <link rel="stylesheet" href="mystyle.css">

    <!-- Insert JavaScript -->
    <script src="JavaScript.js"></script>

    <!-- Defines the title of a document -->
    <title>Title</title>

    <!-- Defines style information for a document -->
    <style></style>
</head>
```

## <br>

<h2 align="center">TOPIC 4<br>Environment Setup and Debugging</h2>

<h3>Web Browsers</h3>

- Google Chrome
- Firefox
- Microsoft Edge
- Safari

##

<h3>Version Control</h3>

- Github

##

<h3>Editor</h3>

- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text](https://www.sublimetext.com/)
- [Codespaces](https://github.com/features/codespaces)
- [Atom](https://atom.io/)
- [Notepad++](https://notepad-plus-plus.org/)
- [Brackets](https://brackets.io/)
- [Vim](https://www.vim.org/)
- [CoffeeCup](https://www.coffeecup.com/)
- [Codepen](https://codepen.io/)
- [Replit](https://replit.com/)

##

<h3>Debugging</h3>

- [After Writing Your HTML Code You Can Check The Validity On This Website](https://validator.w3.org/)

## <br>

<h2 align="center">TOPIC 5<br>Typography</h2>

<h3>HTML Headings</h3>

- HTML headings are titles or subtitles that you want to display on a webpage.
- HTML headings are defined with the `<h1>` to `<h6>` tags.
- **Note:** Browsers automatically add some white space (a margin) before and after a heading.

##

<h3>HTML Paragraphs</h3>

- The HTML `<p>` element defines a paragraph.
- A paragraph always starts on a new line.
- Browsers automatically add some white space (a margin) before and after a paragraph.

##

<h3>HTML Horizontal Rules</h3>

- The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
- The `<hr>` element is used to separate content (or define a change) in an HTML page.
- The `<hr>` tag is an empty tag, which means that it has no end tag.

##

<h3>HTML Line Breaks</h3>

- The HTML `<br>` element defines a line break.
- Use `<br>` if you want a line break (a new line) without starting a new paragraph.
- The `<br>` tag is an empty tag, which means that it has no end tag.

##

<h3>Example</h3>

```html
<body>
    <!-- HTML headings are defined with the <h1> to <h6> tags -->
    <h1>This is Headings 1</h1>
    <h2>This is Headings 2</h2>
    <h3>This is Headings 3</h3>
    <h4>This is Headings 4</h4>
    <h5>This is Headings 5</h5>
    <h6>This is Headings 6</h6>

    <!-- The HTML <p> element defines a paragraph -->
    <p>This is a Paragraph.</p>
    <p>This is Another Paragraph.</p>

    <!-- This is Horizontal Rules Tag -->
    <hr>

    <!-- The HTML <br> element defines a line break -->
    <p>This is <br>a paragraph<br> with line breaks.</p>
</body>
```

##

<h3>HTML Text Formatting</h3>

| HTML Tag   | Details           |
| :--------- | :---------------- |
| `<b>`      | Bold text.        |
| `<strong>` | Important text.   |
| `<i>`      | Italic text.      |
| `<em>`     | Emphasized text.  |
| `<mark>`   | Marked text.      |
| `<small>`  | Smaller text.     |
| `<del>`    | Deleted text.     |
| `<ins>`    | Inserted text.    |
| `<sub>`    | Subscript text.   |
| `<sup>`    | Superscript text. |

##

<h3>HTML Pre-Formatted Text</h3>

- The HTML `<pre>` element defines pre-formatted text.
- The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

##

<h3>Example</h3>

```html
<pre>
    "Amongst the trees, there is a tree,
        the leaves of which do not fall and is like a Muslim.
    Tell me the name of that tree."
        Everybody started thinking about the trees of the desert areas.
    And I thought of the date-palm tree
        but felt shy to answer the others then asked,
    "What is that tree, O Allah's Messenger?"
        He replied, "It is the date-palm tree."
</pre>
```

##

<h3>HTML Comments</h3>

- HTML comments are not displayed in the browser, but they can help document your HTML source code.
- Notice that there is an exclamation point (!) in the start tag, but not in the end tag.
- HTML Comment Tag `<!-- Write your Comments Here -->` ;
- Comments can be used to hide content.
- This can be helpful if you hide content temporarily.
- You can also hide more than one line.

## <br>

<h2 align="center">TOPIC 6<br>HTML Lists and Images</h2>

<h3>HTML Lists</h3>

- HTML lists allow web developers to group a set of related items in lists.

##

<h3>Unordered HTML List</h3>

- An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.
- The CSS `list-style-type` property is used to define the style of the list item marker.

##

<h3>Ordered HTML List</h3>

- An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.
- The type attribute of the `<ol>` tag, defines the type of the list item marker.

##

<h3>HTML Description Lists</h3>

- A description list is a list of terms, with a description of each term.
- The `<dl>` tag defines the description list, the `<dt>` tag defines the term (name), and the `<dd>` tag describes each term.

##

<h3>Example</h3>

```html
<body>
    <h2>Unordered HTML List</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>PYTHON</li>
    </ul>

    <h2>Ordered HTML List</h2>
    <ol>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>PYTHON</li>
    </ol>

    <h2>HTML Description Lists</h2>
    <dl>
        <dt>HTML</dt>
        <dd>Hyper Text Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
        <dt>JS</dt>
        <dd>JavaScript</dd>
        <dt>SQL</dt>
        <dd>Structured Query Language</dd>
    </dl>
</body>
```

##

<h3>HTML Images</h3>

- Images can improve the design and the appearance of a web page.
- Use the HTML `<img>` element to define an image.
- Use the HTML `src` attribute to define the URL of the image.
- Use the HTML `alt` attribute to define an alternate text for an image, if it cannot be displayed.
- Use the HTML `width` and `height` attributes or the CSS `width` and `height` properties to define the size of the image.
- To use an image as a link, put the `<img>` tag inside the `<a>` tag.
- Use the CSS `float` property to let the image float to the left or to the right.
- Loading large images takes time, and can slow down your web page. Use images carefully.

##

<h3>Example</h3>

```html
<body>
    <img src="https://i.postimg.cc/B6yBLRz4/file-1.png" alt="HTML Images" style="width: 200px; height: 200px;">
    <img src="https://i.postimg.cc/0Nnw17fm/file.png" alt="HTML Images" width="150px" height="150px">

    <!-- Image as a Link -->
    <a href="https://youtube.com/">
        <img src="https://i.postimg.cc/B6yBLRz4/file-1.png" alt="Image as a Link" width="120px" height="120px">
    </a>

    <!-- Using CSS Float -->
    <p>
        <img src="https://i.postimg.cc/0Nnw17fm/file.png" alt="HTML Images" style="float: left; width: 40px; height: 40px;">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Unde architecto enim tempore dicta,
        nemo laudantium alias facilis quo, omnis fugiat doloremque consectetur nobis quis facere
        repudiandae similique, nihil eveniet minima Lorem, ipsum omnis fugiat doloremque tempore
        Lorem, ipsum dolor sit amet consectetur adipisicing elit.
    </p>
</body>
```

##

<h3>HTML Background Images</h3>

- A background image can be specified for almost any HTML element.
- To add a background image on an HTML element, use the HTML `style` attribute and the CSS `background-image` property.
- If you want the entire page to have a background image, you must specify the background image on the `<body>` element.
- To avoid the background image from repeating itself, set the `background-repeat` property to `no-repeat` ;
- Also, to make sure the entire element is always covered, set the `background-attachment` property to `fixed` ;
- If you want the background image to cover the entire element, you can set the `background-size` property to `cover` ;

##

<h3>Example</h3>

```html
<style>
    body {
        background-image: url(https://i.postimg.cc/CLtCvyM8/iceland-g587395d02-1920.jpg);
        background-repeat: no-repeat;
        background-position: center;
        background-attachment: fixed;
        background-size: cover;
    }
</style>
```

## <br>

<h2 align="center">TOPIC 7<br>HTML Block and Inline Elements</h2>

<h3>Block-level Elements</h3>

- A block-level element always starts on a new line.
- The browsers automatically add some space (a margin) before and after the element.
- A block-level element always takes up the full width available.
- Two commonly used block elements are: `<p>` and `<div>`.
- The `<p>` element defines a paragraph in an HTML document.
- The `<div>` element defines a division or a section in an HTML document.

##

<h3>Inline Elements</h3>

- An inline element does not start on a new line.
- An inline element only takes up as much width as necessary.
- This is a `<span>` element inside a paragraph.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Block & Inline Elements</title>
</head>
<body>
    <!-- Block-level Elements -->
    <!-- Two commonly used block elements are: <p> and <div> -->
    <p style="border: 1px solid teal;">This is Paragraph</p>
    <div style="border: 1px solid tomato;">This is DIV</div>

    <!-- Inline Elements -->
    <!-- This is a <span> element inside a paragraph -->
    <p>This is an inline span <span style="border: 1px solid SlateBlue;">Hello World</span> element inside a paragraph.</p>
    <p>My mother has <span style="color: MediumSeaGreen; font-weight: bold;">green</span> eyes.</p>
</body>
</html>
```

## <br>

<h2 align="center">TOPIC 8<br>HTML Styles and Selectors</h2>

<h3>HTML Styles</h3>

- The HTML `style` attribute is used to add styles to an element, such as color, font, size, and more.
- Use the `style` attribute for styling HTML elements.
- Use `background-color` for background color.
- Use `color` for text colors.
- Use `font-family` for text fonts.
- Use `font-size` for text sizes.
- Use `text-align` for text alignment.

##

<h3>HTML Colors</h3>

- HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
- [HTML Color Codes](https://htmlcolorcodes.com/)
- [Color Hunt](https://colorhunt.co/)
- [Image Color Picker](ImageColorPicker)
- [ColorZilla](ColorZilla)

##

<h3>HTML Class Attribute</h3>

- The HTML `class` attribute is used to specify a class for an HTML element.
- Multiple HTML elements can share the same class.
- The `class` attribute can be used on any HTML element.
- To create a `class` ; write a period (.) character, followed by a `class` name.
- Then, define the CSS properties within curly braces {}.

##

<h3>HTML Id Attribute</h3>

- The HTML `id` attribute is used to specify a unique id for an HTML element.
- You cannot have more than one element with the same `id` in an HTML document.
- The syntax for `id` is: write a hash character (#), followed by an id name.
- Then, define the CSS properties within curly braces {}.

##

<h3>Difference Between Class and ID</h3>

- A `class` name can be used by multiple HTML elements.
- While an `id` name must only be used by one HTML element within the page.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML class & id Attribute</title>
    <style>
        .para{
            color: teal;
            font-size: 120%;
        }
        .align{
            text-align: center;
        }
        .city{
            font-family: cursive;
            background-color: tomato;
            color: black;
            border: 2px solid black;
            margin: 20px;
            padding: 20px;
        }
        #footer{
            background-color: black;
            color: white;
            padding: 40px;
            text-align: center;
        }
    </style>
</head>
<body>
    <!--Using The class Attribute-->
    <h1>My <span class="para">Important</span> Heading</h1>

    <!--Multiple Classes-->
    <div class="city align">
        <h2>Ankara</h2>
        <p>Ankara is the capital of Turkey</p>
    </div>

    <!--Using The class Attribute-->
    <div class="city">
        <h2>Algiers</h2>
        <p>Algiers is the capital of Algeria</p>
    </div>

    <!--Using The id Attribute-->
    <h1 id="footer">Footer Using ID Attribute</h1>
</body>
</html>
```

## <br>

<h2 align="center">TOPIC 9<br>HTML Forms</h2>

<h3>HTML Form Attributes</h3>

- The `action` attribute defines the action to be performed when the form is submitted.
- The `target` attribute specifies where to display the response that is received after submitting the form.
- The `method` attribute specifies the HTTP method to be used when submitting the form data.
- The `autocomplete` attribute specifies whether a form should have autocomplete on or off.
- The `novalidate` attribute is a boolean attribute. Specifies that the form should not be validated when submitted.

##

<h3>Example</h3>

```html
action="#"; target="_blank"; method="post"; autocomplete="on"; novalidate;
```

##

<h3>HTML Form Elements</h3>

- The `<input>` element can be displayed in several ways, depending on the `type` attribute.
- The `<label>` element defines a label for several form elements.
- The `for` attribute of the `<label>` tag should be equal to the `id` attribute of the `<input>` element to bind them together.
- The `<select>` element defines a drop-down list.
- The `<option>` elements defines an option that can be selected.
- Use the `size` attribute to specify the number of visible values.
- Use the `multiple` attribute to allow the user to select more than one value.
- The `<textarea>` element defines a multi-line input field (a text area).
- The `rows` attribute specifies the visible number of lines in a text area.
- The `cols` attribute specifies the visible width of a text area.
- The `<fieldset>` element is used to group related data in a form.
- The `<legend>` element defines a caption for the `<fieldset>` element.
- The `<datalist>` element specifies a list of pre-defined options for an `<input>` element.
- The `list` attribute of the `<input>` element, must refer to the `id` attribute of the `<datalist>` element.
- The `<output>` element represents the result of a calculation (like one performed by a script).

##

<h3>HTML Input Types</h3>

- `<input type="text">` defines a single-line text input field.
- `<input type="number">` defines a numeric input field.
- `<input type="image">` defines an image as a submit button.
- `<input type="password">` defines a password field.
- `<input type="button">` defines a button.
- `<input type="checkbox">` defines a checkbox.
- `<input type="radio">` defines a radio button.
- `<input type="reset">` defines a reset button that will reset all form values.
- `<input type="submit">` defines a button for submitting form data to a form-handler.
- `<input type="search">` is used for search fields.
- `<input type="file">` defines a file-select field.
- `<input type="email">` is used for input fields that should contain an e-mail address.
- `<input type="color">` is used for input fields that should contain a color.
- `<input type="month">` allows the user to select a month and year.
- `<input type="time">` allows the user to select a time.
- `<input type="date">` is used for input fields that should contain a date.
- `<input type="datetime-local">` specifies a date and time input field, with no time zone.
- `<input type="hidden">` defines a hidden input field.
- `<input type="week">` allows the user to select a week and year.
- `<input type="url">` is used for input fields that should contain a URL address.
- `<input type="tel">` is used for input fields that should contain a telephone number.
- `<input type="range">` defines a control for entering a number whose exact value is not important.

##

<h3>HTML Input Attributes</h3>

- The input `value` attribute specifies an initial value for an input field.
- The input `readonly` attribute specifies that an input field is read-only.
- The input `disabled` attribute specifies that an input field should be disabled.
- The input `size` attribute specifies the visible width, in characters, of an input field.
- The default value for `size` is 20.
- The input `maxlength` attribute specifies the maximum number of characters allowed in an input field.
- The input `min` and `max` attributes specify the minimum and maximum values for an input field.
- The input `multiple` attribute specifies that the user is allowed to enter more than one value in an input field.
- The input `pattern` attribute specifies a regular expression that the input field's value is checked against, when the form is submitted.
- The input `placeholder` attribute specifies a short hint that describes the expected value of an input field.
- The input `step` attribute specifies the legal number intervals for an input field.
- The input `required` attribute specifies that an input field must be filled out before submitting the form.
- The input `autofocus` attribute specifies that an input field should automatically get focus when the page loads.
- The input `height` and `width` attributes specify the height and width of an `<input type="image">` element.

##

<h3>HTML Accessible Forms</h3>

```html
<body>
    <form action="https://formspree.io/f/xdojepok" method="post">
        <div>
            <label for="name">Your Name:</label>
            <input name="name" id="name" type="text">
        </div><br>
        <div>
            <label for="email">Your Email:</label>
            <input name="email" id="email" type="email">
        </div><br>
        <div>
            <label for="message">Your Message:</label><br>
            <textarea name="message" id="message" cols="30" rows="10"></textarea>
        </div>
        <button type="submit">Submit</button>
    </form>
</body>
```

##

<h3>Example</h3>

```html
<body>
    <h1>Registration Form</h1>
    <form action="#" method="post" autocomplete="on" target="_blank">
        <div>
            <label for="firstname">First Name:</label>
            <input type="text" name="firstname" id="firstname" value="Gilani" readonly>
        </div><br>
        <div>
            <label for="lastname">Last Name:</label>
            <input type="text" name="lastname" id="lastname" value="Toufiq" disabled>
        </div><br>
        <div>
            <label for="myemail">Email:</label>
            <input type="email" name="myemail" id="myemail" size="25" autofocus>
        </div><br>
        <div>
            <label for="mypassword">Password:</label>
            <input type="password" name="mypassword" id="mypassword">
        </div><br>
        <div>
            <label for="phone">Phone:</label>
            <input type="tel" name="phone" id="phone" maxlength="15" placeholder="123-456-789">
        </div><br>
        <div>
            <label for="website">Your Website url:</label>
            <input type="url" name="website" id="website" required>
        </div><br>
        <div>
            <label for="age">Enter your Age:</label>
            <input type="number" name="age" id="age" min="18" max="35" value="25">
        </div><br>
        <div>
            <label for="mydate">Date of Birth:</label>
            <input type="date" name="mydate" id="mydate">
        </div><br>
        <div>
            <label for="month">Fav Month:</label>
            <input type="month" name="month" id="month">
        </div><br>
        <div>
            <label for="color">Select Fav Color:</label>
            <input type="color" name="color" id="color">
        </div><br>
        <div>
            <label for="anger">Anger Control:</label>
            <input type="range" name="anger" id="anger" min="0" max="50">
        </div><br>
        <div>
            <label for="file">Choose your File:</label>
            <input type="file" name="file" id="file">
        </div><br>
        <div>
            <h4>Choose your favorite Web language:</h4>
            <div>
                <input type="radio" name="language" id="html" value="html">
                <label for="html">HTML</label> <br>
                <input type="radio" name="language" id="css" value="css">
                <label for="css">CSS</label> <br>
                <input type="radio" name="language" id="java" value="java">
                <label for="java">JavaScript</label>
            </div>
        </div><br>
        <div>
            <h4>Choose your Religion:</h4>
            <div>
                <input type="checkbox" name="vehicle1" id="vehicle1" value="Bike">
                <label for="vehicle1">I have a bike</label> <br>
                <input type="checkbox" name="vehicle2" id="vehicle2" value="Car">
                <label for="vehicle2">I have a car</label> <br>
                <input type="checkbox" name="vehicle3" id="vehicle3" value="Boat">
                <label for="vehicle3">I have a boat</label>
            </div>
        </div><br>
        <div>
            <label for="department">Department:</label>
            <select name="department" id="department">
                <option value="CSE">CSE</option>
                <option value="EEE">EEE</option>
                <option value="LLB">LLB</option>
            </select>
        </div><br>
        <div>
            <label for="mycar">Car:</label>
            <select name="mycar" id="mycar">
                <option value="tes">Tesla</option>
                <option value="ben">Bentley</option>
            </select>
        </div><br>
        <div>
            <label for="message">Message:</label> <br>
            <textarea name="message" id="message" cols="50" rows="10"></textarea>
        </div><br>
        <div>
            <fieldset>
                <legend>Personalia:</legend>
                <label for="fname">First name:</label><br>
                <input type="text" id="fname" name="fname" value="John"><br>
                <label for="lname">Last name:</label><br>
                <input type="text" id="lname" name="lname" value="Doe"><br><br>
                <input type="submit" value="Submit">
                <input type="reset" value="Clear">
            </fieldset>
        </div>
    </form>
</body>
```

## <br>

<h2 align="center">TOPIC 10<br>HTML Quotation and Citation</h2>

<h3>HTML Quotation and Citation Elements</h3>

| HTML Tag       | Description                                                     |
| :------------- | :-------------------------------------------------------------- |
| `<abbr>`       | Defines an abbreviation or acronym.                             |
| `<address>`    | Defines contact information for the author/owner of a document. |
| `<bdo>`        | Defines the text direction.                                     |
| `<blockquote>` | Defines a section that is quoted from another source.           |
| `<cite>`       | Defines the title of a work.                                    |
| `<q>`          | Defines a short inline quotation.                               |

## <br>

<h2 align="center">TOPIC 11<br>HTML Favicon and Iframes</h2>

<h3>HTML Favicon</h3>

- A favicon is a small image displayed next to the page title in the browser tab.
- You can use any image you like as your favicon.
- You can also create your own favicon: [Favicon Link](https://www.favicon.cc/)
- Add a `<link>` element to your "index.html" file, after the `<title>` element.

##

<h3>HTML Iframes</h3>

- An HTML iframe is used to display a web page within a web page.
- The HTML `<iframe>` tag specifies an inline frame.
- The `src` attribute defines the URL of the page to embed.
- Always include a `title` attribute (for screen readers).
- The `height` and `width` attributes specify the size of the iframe.
- Use `"border: none;"` to remove the border around the iframe.

##

<h3>Example</h3>

```html
<body>
    <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/X2YnP50cwNU?autoplay=1&mute=1&controls=1"
    title="YouTube video player"
    style="border: 2px solid teal;"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen></iframe>
</body>
```

## <br>

<h2 align="center">TOPIC 12<br>HTML Media and Graphics</h2>

<h3>HTML Video</h3>

- The HTML `<video>` element is used to show a video on a web page.
- The `controls` attribute adds video controls, like play, pause, and volume.
- It is a good idea to always include `width` and `height` attributes.
- If `height` and `width` are not set, the page might flicker while the video loads.
- The `<source>` element allows you to specify alternative video files which the browser may choose from.
- The browser will use the first recognized format.
- The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element.
- To start a video automatically, use the `autoplay` attribute.
- Add `muted` after autoplay to let your video start playing automatically (but muted).

##

<h3>HTML Audio</h3>

- The HTML `<audio>` element is used to play an audio file on a web page.
- The `controls` attribute adds audio controls, like play, pause, and volume.
- The `<source>` element allows you to specify alternative audio files which the browser may choose from.
- The browser will use the first recognized format.
- The text between the `<audio>` and `</audio>` tags will only be displayed in browsers that do not support the `<audio>` element.
- To start an audio file automatically, use the `autoplay` attribute.
- Add `muted` after autoplay to let your audio file start playing automatically (but muted).

##

<h3>Example</h3>

```html
<body>
    <!-- HTML Video -->
    <video controls autoplay muted width="500px" height="350px">
        <source src="Aerial Video Of Coastline.mp4" type="video/mp4">
    </video>

    <!-- HTML Audio -->
    <audio controls autoplay muted>
        <source src="Next One Roa.mp3" type="audio/mpeg">
    </audio>
</body>
```

##

<h3>HTML Canvas</h3>

- The HTML `<canvas>` element is used to draw graphics on a web page.
- The `<canvas>` element is only a container for graphics. You must use JavaScript to actually draw the graphics.
- Canvas has several methods for drawing paths, boxes, circles, text, and adding images.
- A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content.

##

<h3>HTML SVG</h3>

- SVG stands for Scalable Vector Graphics.
- SVG is used to define graphics for the Web.
- SVG is a W3C recommendation.
- The HTML `<svg>` element is a container for SVG graphics.
- SVG has several methods for drawing paths, boxes, circles, text, and graphic images.

##

<h3>Example</h3>

```html
<body>
    <!-- HTML Canvas Graphics -->

    <!-- After creating the rectangular canvas area, you must add a JavaScript to do the drawing -->
    <!-- Canvas Examples - Draw Linear Gradient -->
    <canvas id="myCanvas" width="200" height="100" style="border: 1px solid #d3d3d3;">
        Your browser does not support the HTML canvas tag.
    </canvas>

    <script>
        var c = document.getElementById("myCanvas");
        var ctx = c.getContext("2d");
        // Create gradient
        var grd = ctx.createLinearGradient(0, 0, 200, 0);
        grd.addColorStop(0, "red");
        grd.addColorStop(1, "white");
        // Fill with gradient
        ctx.fillStyle = grd;
        ctx.fillRect(10, 10, 150, 80);
    </script>

    <!-- HTML SVG Graphics -->

    <!-- SVG Rounded Rectangle -->
    <svg width="400" height="180">
        <rect x="50" y="20" rx="20" ry="20" width="150" height="150" style="fill: teal; stroke: black; stroke-width: 5; opacity: 0.5;">
        Sorry, your browser does not support inline SVG.
    </svg>

    <!-- SVG Logo -->
    <svg height="130" width="500">
        <defs>
            <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
                <stop offset="0%" style="stop-color: rgb(255, 99, 71); stop-opacity: 1;"/>
                <stop offset="100%" style="stop-color: rgb(30, 144, 255); stop-opacity: 1;"/>
            </linearGradient>
        </defs>
        <ellipse cx="100" cy="70" rx="85" ry="55" fill="url(#grad1)"/>
        <text fill="#ffffff" font-size="45" font-family="Verdana" x="50" y="86">SVG</text>
        Sorry, your browser does not support inline SVG.
    </svg>
</body>
```

## <br>

<h2 align="center">TOPIC 13<br>HTML Computer Code and Progress Bars</h2>

<h3>HTML Computer Code</h3>

- The `<kbd>` element defines keyboard input.
- The `<samp>` element defines sample output from a computer program.
- The `<code>` element defines a piece of computer code.
- The content inside is displayed in the browser's default monospace font.
- The `<var>` element defines a variable in programming or in a mathematical expression.
- The content inside is typically displayed in italic.

##

<h3>Example of Progress Bars</h3>

```html
<body>
    <!-- Progress Bars -->
    <ol>
        <li>Python: <progress min="0" max="100" value="30"></progress></li>
        <li>Bootstrap: <progress min="0" max="100" value="70"></progress></li>
        <li>TypeScript: <progress min="0" max="100" value="60"></progress></li>
        <li>JavaScript: <progress min="0" max="100" value="80"></progress></li>
    </ol>
</body>
```

## <br>

<h2 align="center">TOPIC 14<br>HTML Entities and Symbol</h2>

<h3>HTML Entities</h3>

```html
&lt; &gt; &nbsp; &pound; &yen; &euro; &copy; &reg;
```

| Entities   | Details                             |
| :--------- | :---------------------------------- |
| `&lt;`     | Create Less Than Symbol.            |
| `&gt;`     | Create Greater Than Symbol.         |
| `&nbsp;`   | Create Non-Breaking Space Symbol.   |
| `&pound;`  | Create Pound Symbol.                |
| `&yen;`    | Create Yen Symbol.                  |
| `&euro;`   | Create Euro Symbol.                 |
| `&copy;`   | Create Copyright Symbol.            |
| `&reg;`    | Create Registered Trademark Symbol. |

##

<h3>HTML Symbol</h3>

- [UTF-8 Mathematical Operators](https://www.w3schools.com/charsets/ref_utf_math.asp)
- [UTF-8 Miscellaneous Symbols](https://www.w3schools.com/charsets/ref_utf_symbols.asp)
- [UTF-8 Arrows](https://www.w3schools.com/charsets/ref_utf_arrows.asp)
- [UTF-8 Currency Symbols](https://www.w3schools.com/charsets/ref_utf_currency.asp)
- [UTF-8 Greek and Coptic](https://www.w3schools.com/charsets/ref_utf_greek.asp)

## <br>

<h2 align="center">TOPIC 15<br>HTML Emojis and Icon</h2>

<h3>HTML Emojis and Icon</h3>

- **Emojis are characters from the UTF-8 character set:**
  - ⏪⏰☕⚽🌹🌻🍇🍅🏇⏩
- [Emoji Reference](https://www.w3schools.com/charsets/ref_emoji.asp)
- [Icon Finder](https://www.iconfinder.com/)
- [Unicode Character Table](https://unicode-table.com/en/)

## <br>

<h2 align="center">TOPIC 16<br>HTML Responsive Web Design</h2>

<h3>HTML Responsive Web Design</h3>

- Responsive web design is about creating web pages that look good on all devices!
- A responsive web design will automatically adjust for different screen sizes and viewports.

##

<h3>What is Responsive Web Design?</h3>

- Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones).

##

<h3>Responsive Images</h3>

- Responsive images are images that scale nicely to fit any browser size.
- If the CSS `width` property is set to 100%, the image will be responsive and scale up and down.
- If the `max-width` property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size.

##

<h3>Responsive Text Size</h3>

- The text size can be set with a `vw` unit, which means the `viewport width` ;
- Viewport is the browser window size. 1vw = 1% of viewport width.

##

<h3>Media Queries</h3>

- In addition to resize text and images, it is also common to use media queries in responsive web pages.
- With media queries you can define completely different styles for different browser sizes.
- Media queries are a powerful tool for creating responsive and adaptive web designs that work well across a wide range of devices and screen sizes.
- A responsive web page should look good on large desktop screens and on small mobile phones.

## <br>

<h2 align="center">TOPIC 17<br>HTML Links</h2>

<h3>HTML Links</h3>

- HTML links are hyperlinks.
- You can click on a link and jump to another document.
- When you move the mouse over a link, the mouse arrow will turn into a little hand.
- The HTML `<a>` tag defines a hyperlink.
- The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.
- The `target="_blank"` attribute specifies where to open the linked document.
- To use an image as a link, just put the `<img>` tag inside the `<a>` tag.
- Use `mailto:` inside the `href` attribute to create a link that opens the user's email program (to let them send a new email).
- To use an HTML `button` as a link, you have to add some JavaScript code.
- The `title` attribute specifies extra information about an element.

##

<h3>Example</h3>

```html
<body>
    <!--HTML Links, The Target Attribute-->
    <a href="https://www.youtube.com/" target="_blank">Youtube</a>

    <!--Link to an Email Address-->
    <a href="mailto:someone@gmail.com">Send Mail</a>

    <!--Use an Image as a Link-->
    <a href="https://pixabay.com/">
        <img src="https://i.postimg.cc/0Nnw17fm/file.png" alt="Images">
    </a>

    <!--Button as a Link-->
    <button onclick="document.location='default.asp'">HTML Tutorial</button>
</body>
```

##

<h3>Create Bookmarks</h3>

- HTML links can be used to create bookmarks, so that readers can jump to specific parts of a web page.
- Bookmarks can be useful if a web page is very long.
- To create a bookmark - first create the bookmark, then add a link to it.
- When the link is clicked, the page will scroll down or up to the location with the bookmark.
- First, use the `id` attribute to create a bookmark.
- Then, add a link to the bookmark ("Economy"), from within the same page.
- You can also add a link to a bookmark on another page.

##

<h3>Example</h3>

```html
<body>
    <p><a href="#T1">Geography</a></p>
    <p><a href="#T2">Economy</a></p>
    <p><a href="#T3">Education</a></p>
    <p><a href="#T4">Arts</a></p>
    <p><a href="#T5">Sports</a></p>

    <h2>Name</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>History</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Governance</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2 id="T1">Geography</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Climate</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Demographics</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Religion</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2 id="T2">Economy</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Tourism</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Infrastructure</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2 id="T3">Education</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Culture</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2 id="T4">Arts</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2>Cuisine</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>

    <h2 id="T5">Sports</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium, sit.</p>
</body>
```

## <br>

<h2 align="center">TOPIC 18<br>HTML Tables</h2>

<h3>HTML Tables</h3>

| HTML Tag     | Description                                                               |
| :----------- | :------------------------------------------------------------------------ |
| `<table>`    | Defines a table                                                           |
| `<caption>`  | Defines a table caption                                                   |
| `<thead>`    | Groups the header content in a table                                      |
| `<tbody>`    | Groups the body content in a table                                        |
| `<tfoot>`    | Groups the footer content in a table                                      |
| `<tr>`       | Defines a row in a table                                                  |
| `<th>`       | Defines a header cell in a table                                          |
| `<td>`       | Defines a cell in a table                                                 |
| `<colgroup>` | Specifies a group of one or more columns in a table for formatting        |
| `<col>`      | Specifies column properties for each column within a `<colgroup>` element |

##

<h3>HTML Table Borders</h3>

- HTML tables can have borders of different styles and shapes.
- When you add a border to a table, you also add borders around each table cell.
- To add a border, use the CSS `border` property on `table`, `th`, and `td` elements.

##

<h3>Collapsed Table Borders</h3>

- Set the CSS `border-collapse` property to `collapse`.
- This will make the borders collapse into a single border.

##

<h3>Style Table Borders</h3>

- If you set a background color of each cell, and give the border a white color, you get the impression of an invisible border.

##

<h3>Round Table Borders</h3>

- With the `border-radius` property, the borders get rounded corners.

##

<h3>Dotted Table Borders</h3>

- With the `border-style` property, you can set the appearance of the border.

##

<h3>Border Color</h3>

- With the `border-color` property, you can set the color of the border.

##

<h3>HTML Table - Cell Padding</h3>

- To add padding on table cells, use the CSS `padding` property.
- To add padding only above the content, use the `padding-top` property.
- And the others sides with the `padding-bottom`, `padding-left`, and `padding-right` properties.

##

<h3>HTML Table - Cell Spacing</h3>

- To change the space between table cells, use the CSS `border-spacing` property on the `table` element.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tables</title>
    <style>
        /* HTML Table Borders */
        table, th, td {
            border: 1px solid white;

            /* Collapsed Table Borders */
            border-collapse: collapse;

            /* Round Table Borders */
            border-radius: 5px;
        }

        /* table {border-spacing: 30px;} HTML Table - Cell Spacing */

        /* Style Table Borders */
        th, td {
            background-color: #96D4D4;

            /* Border Color */
            /* border-color: dodgerblue; */

            /* HTML Table - Cell Padding */
            padding: 10px;
        }
    </style>
</head>
<body>
    <table style="width:100%">
        <!-- Table Rows -->
        <tr>
            <!-- Table Headers -->
            <th>First Name</th>
            <th>Last Name</th>
            <th>Age</th>
        </tr>
        <tr>
            <!-- Table Cells -->
            <td>Khalid Ibn</td>
            <td>Al-Walid</td>
            <td>30</td>
        </tr>
        <tr>
            <td>Abu</td>
            <td>Bakr</td>
            <td>45</td>
        </tr>
        <tr>
            <td>Umar Ibn</td>
            <td>Al-Khattab</td>
            <td>40</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>HTML Table Sizes</h3>

- HTML tables can have different sizes for each column, row or the entire table.
- Use the `style` attribute with the `width` or `height` properties to specify the size of a table, row or column.

##

<h3>HTML Table Width</h3>

- To set the width of a table, add the `style` attribute to the `<table>` element.

##

<h3>HTML Table Column Width</h3>

- To set the size of a specific column, add the `style` attribute on a `<th>` or `<td>` element.

##

<h3>HTML Table Row Height</h3>

- To set the height of a specific row, add the `style` attribute on a table row element.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}

        th, td {padding: 5px;}
    </style>
</head>
<body>
    <!-- HTML Table Width -->
    <table style="width: 100%;">
        <tr>
            <!-- HTML Table Column Width -->
            <th style="width: 60%;">First Name</th>
            <th>Last Name</th>
            <th>Age</th>
        </tr>
        <!-- HTML Table Row Height -->
        <tr style="height: 100px;">
            <td>Khalid Ibn</td>
            <td>Al-Walid</td>
            <td>30</td>
        </tr>
        <tr>
            <td>Abu</td>
            <td>Bakr</td>
            <td>45</td>
        </tr>
        <tr>
            <td>Umar Ibn</td>
            <td>Al-Khattab</td>
            <td>40</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>HTML Table Headers</h3>

- HTML tables can have headers for each column or row, or for many columns or rows.
- Table headers are defined with `th` elements. Each `th` element represents a table cell.

##

<h3>Vertical Table Headers</h3>

- To use the first column as table headers, define the first cell in each row as a `<th>` element.

##

<h3>Align Table Headers</h3>

- By default, table headers are bold and centered.
- To left-align the table headers, use the CSS `text-align` property.

##

<h3>Table Caption</h3>

- To add a caption to a table, use the `<caption>` tag.
- The `<caption>` tag should be inserted immediately after the `<table>` tag.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tables</title>
    <style>
        table, th, td {border: 1px solid teal; border-collapse: collapse;}

        th, td {padding: 5px;}

        /* Align Table Headers */
        th {text-align: left;}
    </style>
</head>
<body>
    <!-- Vertical Table Headers -->
    <table style="width: 100%;">
        <!-- Table Caption -->
        <caption>Table Caption Here</caption>
        <tr>
            <th>First Name</th>
            <td>Khalid Ibn</td>
            <td>Abu</td>
            <td>Umar Ibn</td>
        </tr>
        <tr>
            <th>Last Name</th>
            <td>Al-Walid</td>
            <td>Bakr</td>
            <td>Al-Khattab</td>
        </tr>
        <tr>
            <th>Profession</th>
            <td>Commander</td>
            <td>1st Caliph</td>
            <td>2nd Caliph</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>HTML Table - Colspan</h3>

- To make a cell span over multiple columns, use the colspan attribute.
- The value of the colspan attribute represents the number of columns to span.

##

<h3>HTML Table - Rowspan</h3>

- To make a cell span over multiple rows, use the rowspan attribute.
- The value of the rowspan attribute represents the number of rows to span.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}

        th, td {padding: 5px;}
    </style>
</head>
<body>
    <h2>HTML Table - Colspan</h2>
    <table style="width: 100%;">
        <tr>
            <th colspan="2">Name</th>
            <th>Age</th>
        </tr>
        <tr>
            <td>Khalid Ibn</td>
            <td>Al-Walid</td>
            <td>43</td>
        </tr>
        <tr>
            <td>Umar Ibn</td>
            <td>Al-Khattab</td>
            <td>45</td>
        </tr>
    </table>

    <h2>HTML Table - Rowspan</h2>
    <table style="width: 100%;">
        <tr>
            <th>Name</th>
            <td>Umar</td>
        </tr>
        <tr>
            <th rowspan="2">Phone</th>
            <td>555-1234</td>
        </tr>
        <tr>
            <td>555-8745</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>HTML Table Styling</h3>

- Use CSS to make your tables look better.

##

<h3>HTML Table - Zebra Stripes</h3>

- If you add a background color on every other table row, you will get a nice zebra stripes effect.
- To style every other table row element, use the `:nth-child(even)` selector like this.
- If you use `(odd)` instead of `(even)`, the styling will occur on row 1,3,5 etc. instead of 2,4,6 etc.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table {border-collapse: collapse; width: 100%;}

        th, td {text-align: left; padding: 8px;}

        tr:nth-child(even) {background-color: #D6EEEE;}
    </style>
</head>
<body>
    <table>
        <tr>
            <th>First Name</th>
            <th>Last Name</th>
            <th>Points</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
            <td>$100</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
            <td>$150</td>
        </tr>
        <tr>
            <td>Joe</td>
            <td>Swanson</td>
            <td>$300</td>
        </tr>
        <tr>
            <td>Cleveland</td>
            <td>Brown</td>
            <td>$250</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>HTML Table - Vertical Zebra Stripes</h3>

- To make vertical zebra stripes, style every other column, instead of every other row.
- Set the `:nth-child(even)` for table data elements like this.
- Put the `:nth-child()` selector on both `th` and `td` elements if you want to have the styling on both headers and regular table cells.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}

        th:nth-child(even), td:nth-child(even) {background-color: #D6EEEE;}
    </style>
</head>
<body>
    <table style="width: 100%;">
        <tr>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THU</th>
            <th>FRI</th>
            <th>SAT</th>
            <th>SUN</th>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>Combine Vertical and Horizontal Zebra Stripes</h3>

- You can combine the styling from the two examples above and you will have stripes on every other row and every other column.
- If you use a transparent color you will get an overlapping effect.
- Use an `rgba()` color to specify the transparency of the color.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}

        tr:nth-child(even) {background-color: rgba(150, 212, 212, 0.4);}

        th:nth-child(even), td:nth-child(even) {background-color: rgba(150, 212, 212, 0.4);}
    </style>
</head>
<body>
    <table style="width: 100%;">
        <tr>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THU</th>
            <th>FRI</th>
            <th>SAT</th>
            <th>SUN</th>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
        <tr>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
            <td> </td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>Horizontal Dividers</h3>

- If you specify borders only at the bottom of each table row, you will have a table with horizontal dividers.
- Add the `border-bottom` property to all `tr` elements to get horizontal dividers.

##

<h3>Hoverable Table</h3>

- Use the `:hover` selector on `tr` to highlight table rows on mouse over.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table {border-collapse: collapse; width: 100%;}

        th, td {padding: 8px; text-align: left; border-bottom: 1px solid #ddd;}

        tr:hover {background-color: #D6EEEE;}
    </style>
</head>
<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
            <th>Savings</th>
        </tr>
        <tr>
            <td>Peter</td>
            <td>Griffin</td>
            <td>$100</td>
        </tr>
        <tr>
            <td>Lois</td>
            <td>Griffin</td>
            <td>$150</td>
        </tr>
        <tr>
            <td>Joe</td>
            <td>Swanson</td>
            <td>$300</td>
        </tr>
        <tr>
            <td>Cleveland</td>
            <td>Brown</td>
            <td>$250</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>HTML Table Colgroup</h3>

- The `<colgroup>` element is used to style specific columns of a table.
- If you want to style the two first columns of a table, use the `<colgroup>` and `<col>` elements.
- The `<colgroup>` element should be used as a container for the column specifications.
- Each group is specified with a `<col>` element.
- The `span` attribute specifies how many columns that get the style.
- The `style` attribute specifies the style to give the columns.

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}
    </style>
</head>
<body>
    <table style="width: 100%;">
        <colgroup>
            <col span="2" style="background-color: #D6EEEE;">
        </colgroup>
        <tr>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THU</th>
            <th>FRI</th>
            <th>SAT</th>
            <th>SUN</th>
        </tr>
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
        </tr>
        <tr>
            <td>8</td>
            <td>9</td>
            <td>10</td>
            <td>11</td>
            <td>12</td>
            <td>13</td>
            <td>14</td>
        </tr>
        <tr>
            <td>15</td>
            <td>16</td>
            <td>17</td>
            <td>18</td>
            <td>19</td>
            <td>20</td>
            <td>21</td>
        </tr>
        <tr>
            <td>22</td>
            <td>23</td>
            <td>24</td>
            <td>25</td>
            <td>26</td>
            <td>27</td>
            <td>28</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>Multiple Col Elements</h3>

- If you want to style more columns with different styles, use more `<col>` elements inside the `<colgroup>` ;

##

<h3>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}
    </style>
</head>
<body>
    <table style="width: 100%;">
        <colgroup>
            <col span="2" style="background-color: #D6EEEE;">
            <col span="3" style="background-color: pink;">
        </colgroup>
        <tr>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THU</th>
            <th>FRI</th>
            <th>SAT</th>
            <th>SUN</th>
        </tr>
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
        </tr>
        <tr>
            <td>8</td>
            <td>9</td>
            <td>10</td>
            <td>11</td>
            <td>12</td>
            <td>13</td>
            <td>14</td>
        </tr>
        <tr>
            <td>15</td>
            <td>16</td>
            <td>17</td>
            <td>18</td>
            <td>19</td>
            <td>20</td>
            <td>21</td>
        </tr>
        <tr>
            <td>22</td>
            <td>23</td>
            <td>24</td>
            <td>25</td>
            <td>26</td>
            <td>27</td>
            <td>28</td>
        </tr>
    </table>
</body>
</html>
```

##

<h3>Empty Colgroups<br>Hide Columns<br>Example</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table, th, td {border: 1px solid black; border-collapse: collapse;}
    </style>
</head>
<body>
    <table style="width: 100%;">
        <colgroup>
            <col span="3">
            <col span="2" style="background-color: pink;">
            <!-- <col span="3" style="visibility: collapse;"> Hide Columns -->
        </colgroup>
        <tr>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THU</th>
            <th>FRI</th>
            <th>SAT</th>
            <th>SUN</th>
        </tr>
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
        </tr>
        <tr>
            <td>8</td>
            <td>9</td>
            <td>10</td>
            <td>11</td>
            <td>12</td>
            <td>13</td>
            <td>14</td>
        </tr>
        <tr>
            <td>15</td>
            <td>16</td>
            <td>17</td>
            <td>18</td>
            <td>19</td>
            <td>20</td>
            <td>21</td>
        </tr>
        <tr>
            <td>22</td>
            <td>23</td>
            <td>24</td>
            <td>25</td>
            <td>26</td>
            <td>27</td>
            <td>28</td>
        </tr>
    </table>
</body>
</html>
```

## <br>

<h2 align="center">TOPIC 19<br>HTML Semantic Elements</h2>

<h3>HTML Semantic Elements</h3>

- A semantic element clearly describes its meaning to both the browser and the developer.
- Examples of **non-semantic** elements: `<div>` and `<span>` Tells nothing about its content.
- Examples of **semantic** elements: `<form>`, `<table>`, and `<article>` Clearly defines its content.

##

**In HTML there are some semantic elements that can be used to define different parts of a web page:**
| Tag            | Description                                                                  |
| :------------- | :--------------------------------------------------------------------------- |
| `<header>`     | Defines a header for a document or a section.                                |
| `<nav>`        | Defines a set of navigation links.                                           |
| `<section>`    | Defines a section in a document.                                             |
| `<article>`    | Defines an independent, self-contained content.                              |
| `<aside>`      | Defines content aside from the content (like a sidebar).                     |
| `<footer>`     | Defines a footer for a document or a section.                                |
| `<details>`    | Defines additional details that the user can open and close on demand.       |
| `<summary>`    | Defines a heading for the `<details>` element.                               |
| `<figcaption>` | Defines a caption for a `<figure>` element.                                  |
| `<figure>`     | Specifies self-contained content, like illustrations, diagrams, photos, etc. |
| `<main>`       | Specifies the main content of a document.                                    |
| `<mark>`       | Defines marked/highlighted text.                                             |
| `<time>`       | Defines a date/time.                                                         |
| `HTML Layout`  | ![](https://www.w3schools.com/html/img_sem_elements.gif)                     |

##

<h3>Two sections in a document</h3>

```html
<!DOCTYPE html>
<html>
<body>

<section>
    <h1>WWF</h1>
    <p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
    <h1>WWF's Panda symbol</h1>
    <p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>

</body>
</html>
```

##

<h3>Three articles with independent and self-contained content</h3>

```html
<!DOCTYPE html>
<html>
<body>

<h1>The article element</h1>

<article>
    <h2>Google Chrome</h2>
    <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
</article>

<article>
    <h2>Mozilla Firefox</h2>
    <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
</article>

<article>
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
</article>

</body>
</html>
```

##

<h3>Use CSS to style the article element</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .all-browsers {
            margin: 0;
            padding: 5px;
            background-color: lightgray;
        }

        .all-browsers > h1, .browser {
            margin: 10px;
            padding: 5px;
        }

        .browser {
            background: white;
        }

        .browser > h2, p {
            margin: 4px;
            font-size: 90%;
        }
    </style>
</head>
<body>
    <article class="all-browsers">
        <h1>Most Popular Browsers</h1>
        <article class="browser">
            <h2>Google Chrome</h2>
            <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
        </article>
        <article class="browser">
            <h2>Mozilla Firefox</h2>
            <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
        </article>
        <article class="browser">
            <h2>Microsoft Edge</h2>
            <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
        </article>
    </article>
</body>
</html>
```

##

<h3>A header for an article</h3>

```html
<!DOCTYPE html>
<html>
<body>

<article>
    <header>
        <h1>What Does WWF Do?</h1>
        <p>WWF's mission:</p>
    </header>
    <p>WWF's mission is to stop the degradation of our planet's natural environment, and build a future in which humans live in harmony with nature.</p>
</article>

</body>
</html>
```

##

<h3>A footer section in a document</h3>

```html
<!DOCTYPE html>
<html>
<body>

<footer>
    <p>Author: Hege Refsnes</p>
    <p><a href="mailto:hege@example.com">hege@example.com</a></p>
</footer>

</body>
</html>
```

##

<h3>A set of navigation links</h3>

```html
<!DOCTYPE html>
<html>
<body>

<nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/jquery/">jQuery</a>
</nav>

</body>
</html>
```

##

<h3>Use CSS to style the aside element</h3>

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        aside {
            width: 30%;
            padding-left: 15px;
            margin-left: 15px;
            float: right;
            font-style: italic;
            background-color: lightgray;
        }
    </style>
</head>
<body>
    <p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

    <aside>
        <p>The Epcot center is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
    </aside>

    <p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>
    <p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>
</body>
</html>
```

##

<h3>Example of figure and figcaption</h3>

```html
<!DOCTYPE html>
<html>
<body>
    <h2>Door wore linking and gloated.</h2>
    <p>Wandering leave while thy fearing thy silence and my gaunt in. By startled linking whom.</p>
    <figure>
        <img src="https://cdn-icons-png.flaticon.com/128/2321/2321775.png" alt="Photo" style="width: 30%">
        <figcaption>Fig.1 - This is figcaption</figcaption>
    </figure>
</body>
</html>
```

## <br>

<h2 align="center">TOPIC 20<br>Web Accessibility</h2>

<h3>Introduction to Web Accessibility</h3>

+ When websites and web tools are properly designed and coded, people with disabilities can use them.
+ However, currently many sites and tools are developed with accessibility barriers that make them difficult or impossible for some people to use.
+ Making the web accessible benefits individuals, businesses, and society.
+ International web standards define what is needed for accessibility.

##

<h3>Accessibility in Context</h3>

+ The Web is fundamentally designed to work for all people, whatever their hardware, software, language, location, or ability.
+ When the Web meets this goal, it is accessible to people with a diverse range of hearing, movement, sight, and cognitive ability.
+ Thus the impact of disability is radically changed on the Web because the Web removes barriers to communication and interaction that many people face in the physical world.
+ However, when websites, applications, technologies, or tools are badly designed, they can create barriers that exclude people from using the Web.
+ **Accessibility is essential for developers and organizations that want to create high-quality websites and web tools, and not exclude people from using their products and services.**

##

<h3>What is Web Accessibility</h3>

+ Web accessibility means that websites, tools, and technologies are designed and developed so that people with disabilities can use them. More specifically, people can:
  + perceive, understand, navigate, and interact with the Web.
  + contribute to the Web.
+ Web accessibility encompasses all disabilities that affect access to the Web, including:
  + auditory
  + cognitive
  + neurological
  + physical
  + speech
  + visual

## <br>

<h1 align="center">
    <a href="https://github.com/Toufiq-Gilani" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/5486/5486427.png" alt="Logo" width="200" height="200">
    </a>
</h1>
