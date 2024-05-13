#### 1. Are the HTML tags and elements the same thing?

HTML tags and elements are related but not exactly the same thing.

**Tags:**

HTML Tags are the labels that create web pages. They are used to define the structure and content of web pages. Each tag provides special meaning for the content.

<u>Example</u>: `<p>` is paragraph tag.

**Elements:**

HTML element is a combination of start tag, content and an end tag. Mostly, website content is written inside start tag `<p>` and an end tag `</p>`.

<u>Example</u>: `<p>this is a paragraph</p>` represents HTML element.

---

#### 2. What are tags and attributes in HTML?

In HTML tags and attributes are fundamental components used to structure and define the content of a web page.

**Tags:**

Tags are the building blocks of HTML. They are enclosed in brackets < > and indicate the beginning and end of elements on a web page. Tags are used to define the structure and content of different elements such as headings, paragraphs, images, links, etc.

**Attributes:**

Attributes provide additional information about HTML elements and are always specified within the opening tag. They are made up of a name and a value, separated by an equals sign `=` and enclosed in quotes single `('')` or double `("")`. Attributes modify the behavior or appearance of an element.

---

#### 3. What are void elements in HTML? With Example.

Void elements in HTML are elements that do not have any content or closing tag. They are self-closing and typically used to insert or represent something without any content.

<u>Example</u>:

- This is a line.
  `<br />`
  this is another line.

- `<input type="text" name="username" id="id">`

---

#### 4. What are HTML Entities? With Example.

HTML entities are special codes used in HTML to represent characters that have a special meaning in HTML markup or characters that are not easily typed on a keyboard. They begin with an ampersand [&] and end with a semicolon [;].

<u>Example</u>:

- `&lt;` represents the less-than sign (<).
- `&gt;` represents the greater-than sign (>).
- `&amp;` represents the ampersand symbol (&).
- `&copy;` represents the copyright symbol (©).
- `&reg;` represents the registered trademark symbol (®).

---

#### 5. What are different types of lists in HTML? With Example.

In HTML, there are three main types of lists:

**1. Ordered Lists `(<ol>)`:**

Ordered lists are used to represent a list of items in a specific sequence or order. Each item in an ordered list is preceded by a number, typically starting from 1.

<u>Example</u>:

```html
<ol>
  <li>first item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

**2. Unordered Lists `(<ul>)`:**

Unordered lists are used to represent a collection of items that don't have a particular sequence or order. Each item in an unordered list is typically preceded by a bullet point.

<u>Example</u>:

```html
<ul>
  <li>Red</li>
  <li>Green</li>
  <li>Blue</li>
</ul>
```

**3. Definition Lists `(<dl>)`:**

Definition lists are used to define terms and their corresponding definitions. Each item in a definition list consists of a term `<dt>` followed by its definition `<dd>`.

<u>Example</u>:

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

---

#### 6. What is the ‘class’ attribute in HTML? With Example.

In HTML, the `class` attribute is used to assign one or more CSS classes to an HTML element. It allows you to apply styles defined in a CSS stylesheet to specific elements on your web page.

<u>Example</u>:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Class Attribute Example</title>
    <style>
      .red-text {
        color: red;
      }
      .bold {
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <p class="red-text">This text is red.</p>
    <p class="bold">This text is bold.</p>
    <p class="red-text bold">This text is both red and bold.</p>
  </body>
</html>
```

---

#### 7. What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements? With Example.

In HTML, both the 'id' and 'class' attributes are used to specify characteristics of elements, but they serve different purposes. while the 'id' attribute is used to uniquely identify an element, the 'class' attribute is used to group elements that share similar characteristics.

**ID Attribute:**

The 'id' attribute is used to uniquely identify an element within a document. Each ID value in a document must be unique; you can't have two elements with the same ID within the same HTML document. IDs are often used when you want to target a specific element with CSS or JavaScript.

<u>Example</u>:

```html
<html>
  <head>
    <title>Example using ID</title>
    <style>
      #unique-element {
        color: blue;
      }
    </style>
  </head>
  <body>
    <p id="unique-element">This paragraph has a unique ID.</p>
  </body>
</html>
```

(In this example, the CSS rule targets the element with the ID 'unique-element' and changes its color to blue.)

**Class Attribute:**

The 'class' attribute is used to define one or more classes for an element. Unlike IDs, classes can be shared by multiple elements on a page. This is useful when you want to apply the same styling or behavior to multiple elements.

<u>Example</u>:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Example using Class</title>
    <style>
      .highlight {
        background-color: yellow;
      }
    </style>
  </head>
  <body>
    <p class="highlight">This paragraph is highlighted.</p>
    <p>This paragraph is not highlighted.</p>
    <p class="highlight">This paragraph is also highlighted.</p>
  </body>
</html>
```

(In this example, the CSS rule applies a yellow background to any element with the class 'highlight'. Both paragraphs with the class 'highlight' will have a yellow background, while the paragraph without the class remains unaffected.)

---

#### 8. What are the various formatting tags in HTML?

HTML provides various formatting tags to structure and style content. Here are some commonly used formatting tags:

**1. `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`:** Heading tags for different levels of headings.

**2. `<p>` :** Paragraph tag for defining paragraphs.

**3. `<br>` :** Line break tag for inserting line breaks within text.

**4. `<hr>` :** Horizontal rule tag for inserting a horizontal line.
**5. `<strong>` :** Strong emphasis tag for making text bold.
**6. `<u>` :** Underline tag for underlining text.
**7. `<b>` :** Bold tag for making text bold (though `<strong>` is preferred for semantic reasons).
**8. `<i>` :** Italic tag for italicizing text (though `<em>` is preferred for semantic reasons).

These are just some of the basic formatting tags in HTML. There are many more tags and attributes available for various purposes, including semantic markup, multimedia embedding, form elements, etc.

---

#### 9. How is Cell Padding different from Cell Spacing? With Example.

Cell padding and cell spacing are both properties used in HTML table elements to control the spacing and alignment of the content within the cells and the spacing between cells.

**Cell Padding:**

Cell padding refers to the space between the content of a cell and the cell border.
It controls the amount of space between the content of the cell and the cell's border.
Cell padding is specified using the `padding` attribute in CSS or the `cellpadding` attribute in HTML.

<u>Example</u>:

```html
<html>
  <head>
    <
    <title>Document</title>
  </head>
  <body>
    <table border="2" cellpadding="10">
      <tr>
        <td>Cell 1</td>
        <td>Cell 2</td>
      </tr>
    </table>
  </body>
</html>
```

(In this example, the cellpadding="10" attribute ensures that there is a padding of 10 pixels between the content of each cell and the cell's border.)

**Cell Spacing:**

Cell spacing refers to the space between adjacent cells in a table. Cell spacing is specified using the `border-spacing` property in CSS or the `cellspacing` attribute in HTML. Cell spacing affects the space between cells.

<u>Example</u>:

```html
<html>
  <head>
    <
    <title>Document</title>
  </head>
  <body>
    <table border="2" cellspacing="10">
      <tr>
        <td>Cell 1</td>
        <td>Cell 2</td>
      </tr>
    </table>
  </body>
</html>
```

(In this example, the cellspacing="10" attribute ensures that there is a spacing of 10 pixels between adjacent cells in the table.)

---

#### 10. How can we club two or more rows or columns into a single row or column in an HTML table? With Example.

n HTML, you can use the colspan and rowspan attributes to merge multiple rows or columns in a table. Here's an example demonstrating how to combine rows and columns in an HTML table:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Table Row and Column Span</title>
  </head>
  <body>
    <h4>HTML Table with Row and Column Span</h4>
    <table border="1">
      <tr>
        <th>Name</th>
        <th>Age</th>
        <th colspan="2">Details</th>
      </tr>
      <tr>
        <td rowspan="2">John</td>
        <td rowspan="2">23</td>
        <td>Occupation</td>
        <td>Location</td>
      </tr>
      <tr>
        <td>Engineer</td>
        <td>rajkot</td>
      </tr>
      <tr>
        <td>isha</td>
        <td>21</td>
        <td colspan="2">Student</td>
      </tr>
    </table>
  </body>
</html>
```

---

#### 11. What is the difference between a block-level element and an inline element?

Block-level elements and inline elements are two fundamental building blocks of HTML document structure, and they differ in how they behave in terms of layout and interaction on a web page.

**Block-level elements**:

Block-level elements typically start on a new line and occupy the full width available to them, pushing adjacent elements below them. They allow setting width, height, margins, padding, and borders. Examples of block-level elements include `<div>`, `<p>`, `<h1>` to `<h6>`, `<ul>`, `<ol>`, `<li>`, `<table>`, `<form>`, etc.

**Inline elements**:

Inline elements do not start on a new line and only occupy the space bounded by the tags that define them. They do not allow setting width, height, margins, padding, or borders (except for a few exceptions with padding and margin). Examples of inline elements include `<span>`, `<a>`, `<strong>`, `<em>`, `<img>`, `<input>`, `<label>`, `<br>`, `<i>`, `<b>`, etc.

<u>Example</u>:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .block {
        width: 200px;
        height: 100px;
        background-color: lightblue;
        margin-bottom: 10px;
      }
      .inline {
        background-color: lightgreen;
        padding: 5px;
        margin-right: 10px;
      }
    </style>
  </head>
  <body>
    <div class="block">Block-level element</div>
    <span class="inline">Inline element</span>
    <span class="inline">Another inline element</span>
    <span class="inline">Yet another inline element</span>
  </body>
</html>
```

(In this example, the block-level element `<div>` occupies the full width available and starts on a new line, whereas the inline elements `<span>` are displayed on the same line and only occupy the space they need.)

---

#### 12. How to create a Hyperlink in HTML? With Example.

Creating a hyperlink in HTML is simple. You use the `<a>` tag, which stands for anchor, and specify the URL you want to link to in the `href` attribute.

<u>Example</u>:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Hyperlink Example</title>
  </head>
  <body>
    <a href="https://www.tops-int.com/">Tops Technologies</a>
  </body>
</html>
```

---

#### 13. What is the use of an iframe tag? With Example.

`<iframe>` (short for inline frame) tag in HTML is used to embed another document within the current HTML document. This can be a webpage, a video, a map, or any other type of content that can be displayed in a browser.

<u>Example</u>:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>IFrame Example</title>
  </head>
  <body>
    <h2>Embedding a Google Map using an iframe</h2>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d27514.743941900742!2d78.0558404796894!3d30.45472168201723!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3908d0cfa61cda5b%3A0x197fd47d980e85b1!2sMussoorie%2C%20Uttarakhand!5e0!3m2!1sen!2sin!4v1714399378676!5m2!1sen!2sin"
      width="600"
      height="450"
      style="border: 0"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>
  </body>
</html>
```

---

#### 14. What is the use of a span tag? Explain with example?

The `<span>` tag in HTML is a generic inline container used to group elements and apply styles or scripting to them. It's primarily used for applying styles, such as font styles, colors, or inline formatting, to a specific portion of text within a larger block of content.

<u>Example</u>:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Span Tag Example</title>
    <style>
      .highlight {
        color: red;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <p>This is a <span class="highlight">highlighted</span> text.</p>
    <p><span style="font-style: italic;">This is italicized text.</span></p>
  </body>
</html>
```

---

#### 15. How to insert a picture into a background image of a web page? With Example.

To insert a picture into the background of a web page, you can use background in body tag.

<u>Example</u>:

```html
<html>
  <head>
    <title>Document</title>
    <style>
      body {
        background-repeat: no-repeat;
      }
    </style>
  </head>
  <body
    background="https://resize.indiatvnews.com/en/resize/newbucket/400_-/2021/03/github-1585316201-1616751698.jpg"
  >
    <h2>GitHub</h2>
    <p>
      GitHub Copilot empowers developers to complete tasks 55% faster with
      contextualized AI coding assistance across workflows.
    </p>
  </body>
</html>
```

---

#### 16. How are active links different from normal links?

Active links and normal links refer to different states of hyperlinks on a web page. while normal links represent the default appearance of hyperlinks on a webpage, active links represent the appearance of hyperlinks while they are being clicked or interacted with by the user.

---

#### 17. What are the different tags to separate sections of text?

There are several HTML tags you can use to separate sections of text on a webpage. Here are some commonly used ones:

1. `<div>`
2. `<p>`
3. `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
4. `<section>`
5. `<article>`
6. `<header>`

---

#### 18. What is SVG?

SVG stands for Scalable Vector Graphics. It's a widely used format for describing two-dimensional vector graphics. Unlike raster image formats like JPEG or PNG, which use grids of pixels to represent images, SVG uses mathematical equations to define shapes and lines, making it resolution-independent and ideal for graphics that need to be scaled to different sizes without losing quality. SVG files can be created and edited with text editors or specialized graphic design software and are commonly used for icons, logos, illustrations, and interactive graphics on websites.

---

#### 19. What is difference between HTML and XHTML?

HTML (Hypertext Markup Language) and XHTML (Extensible Hypertext Markup Language) are both markup languages used to create web pages. XHTML is stricter and more standardized than HTML, requiring well-formed XML syntax, while HTML is more forgiving and widely supported by web browsers. However, with HTML 5 many features of XHTML have been incorporated into HTML, reducing the practical differences between the two.

---

#### 20. What are logical and physical tags in HTML?

In HTML, there aren't explicit "logical" and "physical" tags, but there are structural elements and presentational elements, which are often conflated with logical and physical tags respectively.

**Structural Elements (Logical Tags):**

These elements define the structure and semantics of a webpage. They convey the meaning of the content without regard to its presentation.Examples include `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`, `<aside>`, `<figure>`, `<figcaption>`, etc. They help in organizing the content in a meaningful and semantically correct manner, which is beneficial for accessibility and maintainability.

**Presentational Elements (Physical Tags):**

These elements are concerned with how content looks or is presented on the webpage. Historically, HTML had many presentational elements like `<b>`, `<i>`, `<font>`, `<center>`, etc., but they are now deprecated in favor of CSS for styling.

---
