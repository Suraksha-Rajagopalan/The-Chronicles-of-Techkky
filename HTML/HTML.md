<div align="center">
  <h1><strong><em>Hyper Text Markup Language</em>(HTML)</strong></h1>
  </div>
  
  <br>
  <h2><font face="arial">Contents</font></h2>
  <br>
  
  <ul>
  <li><a href="#intro">Introduction</a></li>
  <li><a href="#history">History of the Language</a></li>
  <li><a href="#language">Language</a></li>
  <ul>
    <li><a href ="#doctype">Doctype</a></li>
    <li><a href ="#html">HTML tag</a></li>
    <li><a href="#head">Head tag</a></li>
    <li><a href ="#meta">Meta tag</a></li>
    <li><a href ="#body">Body tag</a></li>
    <li><a href ="#para">Paragraph tag</a></li>
    <li><a href ="#heading">h tag</a></li>
    <li><a href ="#strongemstrike">Bold Italics and Underline</a></li>
    <li><a href ="#font">Font</a></li>
    <li><a href ="#list">List</a></li>
    <li><a href ="#image">Image</a></li>
    <li><a href ="#anchor">Anchor tag</a></li>
    <li><a href ="#table">Tables</a></li>
    <li><a href ="#forms">Forms</a></li>
  </ul>
  <li><a href="#project">Sample Project</a></li>
  </ul>
  
  <h2><a id="intro">Introduction</a></h2>
  
  The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. 
  It is often assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.

  Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. 
  HTML describes the structure of a web page semantically and originally included cues for its appearance. HTML elements are the building blocks of HTML pages. 
  With HTML constructs, images and other objects such as interactive forms may be embedded into the rendered page. HTML provides a means to create structured documents by denoting structural semantics 
  for text such as headings, paragraphs, lists, links, quotes, and other items. HTML elements are delineated by tags, written using angle brackets. 
  Tags such as ```<img />``` and ```<input />``` directly introduce content into the page. Other tags such as ```<p>``` and ```</p>``` surround and provide information about
  document text and may include sub-element tags. Browsers do not display the HTML tags but use them to interpret the content of the page.
  
  HTML can embed programs written in a scripting language such as JavaScript, which affects the behavior and content of web pages. The inclusion of CSS defines the 
  look and layout of content. The World Wide Web Consortium (W3C), former maintainer of the HTML and current maintainer of the CSS standards, has encouraged 
  the use of CSS over explicit presentational HTML since 1997. A form of HTML, known as HTML5, is used to display video and audio, primarily using the ```<canvas>```
  element, together with JavaScript.

  
  <h2><a id="history">History of the Language</a></h2>
    
  HTML (Hypertext Markup Language) is a markup language used to create web pages and applications for the World Wide Web. It was developed by physicist 
  ```Tim Berners-Lee``` in the late 1980s and early 1990s while he was working at CERN. The first publicly available description of HTML was a document called 
  ```HTML Tags```, which was published by Berners-Lee in late 1991.
    
  HTML is based on ```SGML (Standard Generalized Markup Language)```, a language for describing markup languages. SGML was widely used in the publishing industry 
  at the time and provided a powerful way to structure and describe content. HTML, like SGML, uses tags to describe the structure of a document, allowing web 
  browsers to interpret and display the content.

  HTML has evolved over time, with new versions and standards being developed to address the changing needs of the web. HTML 2.0 was the first HTML specification 
  intended to be treated as a standard against which future implementations should be based, and HTML 4.01 was published in late 1999 as the final version of HTML4.
  HTML5, which was developed by the Web Hypertext Application Technology Working Group (WHATWG) and later became a joint deliverable with the W3C, was completed and 
  standardized on 28 October 2014. HTML5 introduced many new features and capabilities, including improved multimedia support, enhanced semantic elements, and better
  accessibility for people with disabilities.
  Today, HTML is the foundation of the World Wide Web, and is used in conjunction with CSS (Cascading Style Sheets) and JavaScript to create 
  interactive and dynamic web pages and applications.
  
  <h2><a id="language">Language</a></h2>
  "Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. 
  By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.

  HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements" such as ```<head>```  ```<title>``` 
  ```<body>``` ```<header>``` ```<footer>``` ```<article>``` ```<section>``` ```<p>``` ```<div>``` ```<span>``` ```<img>``` ```<aside>``` ```<audio>``` ```<canvas>``` ```<datalist>``` ```<details>``` ```<embed>``` ```<nav>``` ```<output>``` 
  ```<progress>``` ```<video>``` ```<ul>``` ```<ol>``` ```<li>``` and many others.
  
   <h3><a id ="doctype">Doctype</a></h3>
   
   The HTML document type declaration, also known as DOCTYPE, is the first line of code required in every HTML or XHTML document. 
   The DOCTYPE declaration is an instruction to the web browser about what version of HTML the page is written in. The ```<!DOCTYPE html>``` declaration is 
   used to inform a website visitor’s browser that the document being rendered is an HTML document.
   In HTML 4.01, the DOCTYPE declaration refers to a document type definition (DTD). A DTD defines the structure and the legal elements of an XML document. 
   Because HTML 4.01 was based on the Standard Generalised Markup Language (SGML), referring to a DTD in the DOCTYPE declaration was necessary. Additionally, 
   doctypes for HTML 4.01 required the declaration of either ```strict``` ```transitional``` or ```frameset``` DTD, each with a different use case as outlined below.
   
   In contrast, the declaration of HTML5 DOCTYPE is much simpler: it no longer requires a reference to DTDs as it is no longer based on SGML.
    
   <h3><a id ="html">HTML tag</a></h3>
   
   The ```<html>``` HTML element represents the root (top-level element) of an HTML document, so it is also referred to as the root element. All other 
   elements must be descendants of this element.
   
   The start tag may be omitted if the first thing inside the ```<html>``` element is not a comment. The end tag may be omitted if the ```<html>``` element is not 
   immediately followed by a comment. While HTML does not require authors to specify ```<html>``` element start and ending tags, it is important for authors to do so as it will allow them to specify 
   the lang for the webpage. Providing a lang attribute with a valid language tag according to RFC 5646: Tags for Identifying Languages (also known as BCP 47) on 
   the ```<html>``` element will help screen reading technology determine the proper language to announce. The identifying language tag should describe the language
   used by the majority of the content of the page. Without it, screen readers will typically default to the operating system's set language, which may cause 
   mispronunciations. Including a valid lang declaration on the ```<html>``` element also ensures that important metadata contained in the page's ```<head>``` such as the 
   page's ```<title>``` are also announced properly.
   
   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
        <!-- … -->
     </head>
     <body>
        <!-- … -->
     </body>
   </html>
   ```
   
   <h3><a id="head">Head tag</a></h3>
   
   The ```<head>``` HTML element contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets.
   ```<head>``` primarily holds information for machine processing, not human-readability. For human-visible information, like top-level headings and listed 
   authors, see the <header> element.
  The start tag may be omitted if the first thing inside the ```<head>``` element is an element. The end tag may be omitted if the first thing following 
  the ```<head>``` element is not a space character or a comment.
  
  ```html
  <!DOCTYPE html>
  <html lang="en-US">
     <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width" />
        <title>Document title</title>
     </head>
  </html>
  ```
    
   <h3><a id ="meta">Meta tag</a></h3>
   
   Meta tags communicates with both the web browser and search engine about your page. If meta description is not provided then the search engine will automatically 
   generate one based on the content of the page.
   
   The attribute ```name``` has a specific meaning for the ```<meta>``` element, and the itemprop attribute must not be set on the same ```<meta>``` element that has 
   any existing ```name``` ```http-equiv``` or ```charset``` attributes.
  
  <strong>charset</strong>
  This attribute declares the document's character encoding. If the attribute is present, its value must be an ASCII case-insensitive match for the 
  string ```utf-8``` because UTF-8 is the only valid encoding for HTML5 documents. ```<meta>``` elements which declare a character encoding must be located 
  entirely within the first 1024 bytes of the document.
  
  <strong>content</strong>
  
  This attribute contains the value for the ```http-equiv``` or ```name``` attribute, depending on which is used.
  
  <strong>http-equiv</strong>
  
  Defines a pragma directive. The attribute is named http-equiv(alent) because all the allowed values are names of particular HTTP headers:
  
   - ```content-security-policy``` Allows page authors to define a content policy for the current page. Content policies mostly specify allowed server 
     origins and script endpoints which help guard against cross-site scripting attacks.
   - ```content-type``` Declares the MIME type and character encoding of the document. If specified, the content attribute must have the value 
  "text/html; charset=utf-8". This is equivalent to a <meta> element with the charset attribute specified, and carries the same restriction on placement 
  within the document. Note: Can only be used in documents served with a text/html — not in documents served with an XML MIME type.
   - ```default-style``` Sets the name of the default CSS style sheet set.
   - ```x-ua-compatible``` If specified, the content attribute must have the value "IE=edge". User agents are required to ignore this pragma.
   - ```refresh``` This instruction specifies:
      - The number of seconds until the page should be reloaded - only if the content attribute contains a non-negative integer.
      - The number of seconds until the page should redirect to another - only if the content attribute contains a non-negative integer followed by the string ';url=', and a valid URL.
   <strong>name</strong>
   The ```name``` and ```content``` attributes can be used together to provide document metadata in terms of name-value pairs, with the name attribute giving the metadata 
    ```name``` and the ```content``` attribute giving the value.

   ```html
   <meta charset="utf-8" />

   <!-- Redirect page after 3 seconds -->
   <meta http-equiv="refresh" content="3;url=https://www.mozilla.org" />
   ```
  
   <h3><a id="body">Body Tag</a></h3>
  
   The ```<body>``` HTML element represents the content of an HTML document. There can be only one ```<body>``` element in a document.
   The start tag may be omitted if the first thing inside it is not a space character, comment, ```<script>``` element or ```<style>``` element. The end tag may be        omitted if the ```<body>``` element has contents or has a start tag, and is not immediately followed by a comment.
  
  <strong><u>Some Attributes of the Body tag</u></strong>
  
  <img src="https://user-images.githubusercontent.com/91787553/223964573-6a34dab8-7822-4dea-8427-aac3405fec21.png" width="700" height="500">

    
   <h3><a id ="para">Paragraph tag</a></h3>
  
   The ```<p>``` HTML element represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank        lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields.

   Paragraphs are block-level elements, and notably will automatically close if another block-level element is parsed before the closing ```</p>``` tag.
   The start tag is required. The end tag may be omitted if the ```<p>``` element is immediately followed by an ```<address>``` ```<article>``` ```<aside>``` ```<blockquote>``` ```<div>``` ```<dl>``` ```<fieldset>``` ```<footer>``` ```<form>``` ```<h1>``` ```<h2>``` ```<h3>``` ```<h4>``` ```<h5>``` ```<h6>``` ```<header>``` ```<hr>``` ```<menu>``` ```<nav>``` ```<ol>``` ```<pre>``` ```<section>``` ```<table>``` ```<ul>``` or another ```<p>``` element, or if there is no more content in the parent element and the parent element is not an ```<a>``` element.
   
   <strong><u>Note:</u></strong>  The ```align``` attribute on ```<p>``` tags is obsolete and shouldn't be used.
   
   ```html
   <p>
    This is the first paragraph of text. This is the first paragraph of text. This
    is the first paragraph of text. This is the first paragraph of text.
  </p>
  <p>
    This is the second paragraph. This is the second paragraph. This is the second
    paragraph. This is the second paragraph.
  </p>
  ```
    
   <h3><a id ="heading">h tag</a></h3>
   
   The ```<h1>``` to ```<h6>``` HTML elements represent six levels of section headings. ```<h1>``` is the highest section level and ```<h6>``` is the lowest.
   
   ```html
   <h1>Heading level 1</h1>
   <h2>Heading level 2</h2>
   <h3>Heading level 3</h3>
   <h4>Heading level 4</h4>
   <h5>Heading level 5</h5>
   <h6>Heading level 6</h6>
   ```
    
   <h3><a id ="strongemstrike">Bold Italics and Underline</a></h3>
   
   The ```<strong>``` element is for content that is of "strong importance," including things of great seriousness or urgency (such as warnings). This could be a sentence that is of great importance to the whole page, or you could merely try to point out that some words are of greater importance compared to nearby content.

  Typically this element is rendered by default using a bold font weight. However, it should not be used to apply bold styling; use the CSS font-weight property for that purpose. Use the ```<b>``` element to draw attention to certain text without indicating a higher level of importance. Use the ```<em>``` element to mark text that has stress emphasis.

  Another accepted use for ```<strong>``` is to denote the labels of paragraphs which represent notes or warnings within the text of a page.
  
   ### ```<b>``` vs. ```<strong>``` 
   
   It is often confusing to new developers why there are so many ways to express the same thing on a rendered website. ```<b>``` and ```<strong>``` are perhaps one of the most common sources of confusion, causing developers to ask "Should I use ```<b>``` or ```<strong>```? Don't they both do the same thing?"

   Not exactly. The ```<strong>``` element is for content that is of greater importance, while the ```<b>``` element is used to draw attention to text without indicating that it's more important.

   It may help to realize that both are valid and semantic elements in HTML and that it's a coincidence that they both have the same default styling (boldface) in most browsers (although some older browsers actually underline ```<strong>```). Each element is meant to be used in certain types of scenarios, and if you want to bold text for decoration, you should instead actually use the CSS font-weight property.
   
   ### ```<em>``` vs. ```<strong>```
   
   Adding to the confusion is the fact that while HTML 4 defined ```<strong>``` as indicating a stronger emphasis, HTML 5 defines ```<strong>``` as representing "strong importance for its contents." This is an important distinction to make.

   While ```<em>``` is used to change the meaning of a sentence as spoken emphasis does ("I love carrots" vs. "I love carrots"), ```<strong>``` is used to give portions of a sentence added importance (e.g., "Warning! This is very dangerous.") Both ```<strong>``` and ```<em>``` can be nested to increase the relative degree of importance or stress emphasis, respectively.
   
   ```html
   <p>
     <strong>Important:</strong> Before proceeding, make sure you add plenty of butter.
     In HTML 5, what was previously called
     <em>block-level</em> content is now called <em>flow</em> content.
  </p>
  ```
    
   <h3><a id ="font">Font</a></h3>
   
   Font Tag in HTML is one of the most important attributes used to make webpage or HTML documents more attractive. It has the properties to change the size, color, and style of included text. With the help of a font tag, one can make a web page’s size, color, and face in the same text format. This tag mainly works on three major attributes like size, Face or Type and color. Font tag works as an inline element in HTML to change some features of block text in HTML documents. The text enclosed within ```<font>``` tag is used to define style to the text included in it.
   
   <img src="https://user-images.githubusercontent.com/91787553/223972638-89ef0c06-93c9-4940-85b4-98a1b0d68115.png">
   
   ```html
   <body>
   <p> <font size="2" color="blue" face="Calibri"> </font>
   </p>
   </body>
   ```
   
   <h3><a id ="list">List</a></h3>
   
   The ```<li>``` HTML element is used to represent an item in a list. It must be contained in a parent element: an ordered list (```<ol>```), an unordered list (```<ul>```), or a menu (```<menu>```). In menus and unordered lists, list items are usually displayed using bullet points. In ordered lists, they are usually displayed with an ascending counter on the left, such as a number or letter.
   
   ```html
   <ol>
     <li>first item</li>
     <li>second item</li>
     <li>third item</li>
   </ol>
   
   <ol type="I">
     <li value="3">third item</li>
     <li>fourth item</li>
     <li>fifth item</li>
   </ol>

   <ul>
     <li>first item</li>
     <li>second item</li>
     <li>third item</li>
   </ul>
   ```
   
   <h3><a id ="image">Image</a></h3>
   
   The ```src``` attribute is required, and contains the path to the image you want to embed.
   
   The ```alt``` attribute holds a text description of the image, which isn't mandatory but is incredibly useful for accessibility — screen readers read this description out to their users so they know what the image means. Alt text is also displayed on the page if the image can't be loaded for some reason: for example, network errors, content blocking, or linkrot.
   
   <img src = "https://user-images.githubusercontent.com/91787553/223975342-47d45713-9342-4c3c-a736-c67fc1e6bc55.png">
   
   ### Attributes of img tag:
   
   <img src = "https://user-images.githubusercontent.com/91787553/223976155-cb91ef3c-5f55-40de-bb36-48f4aabeb0c3.png" width = "75%">
   
   ```html
   <img src="https://user-images.githubusercontent.com/91787553/223976640-df14bef5-77d6-4ffe-9f8c-ba1093a4d348.png"
   alt = "Image tag"
   width = "50%"
   height = "45%"
   srcset="https://user-images.githubusercontent.com/91787553/223976640-df14bef5-77d6-4ffe-9f8c-ba1093a4d348.png 2x">
   ```
    
   <h3><a id ="anchor">Anchor tag</a></h3>
   
   The ```<a>``` HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

   Content within each ```<a>``` should indicate the link's destination. If the href attribute is present, pressing the enter key while focused on the ```<a>``` element will activate it.
   
   <img src="https://user-images.githubusercontent.com/91787553/223979481-7ebc94b0-6050-4dc1-ab58-f4a4c273709f.png">
   
   ```html
   <a href="https://user-images.githubusercontent.com/91787553/223979814-92b3ceec-bd6e-4e8a-bd36-5759337164d7.png">Attributes of anchor tag</a>
   ```

   <h3><a id ="table">Tables</a></h3>
   
   The ```<table>``` HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.
   
   <img src = "https://user-images.githubusercontent.com/91787553/223990214-ce7d9902-e361-4e50-87ee-a2fd73231853.png">
   
   ```html
   <p>Simple table with header</p>
<table>
  <tr>
    <th>First name</th>
    <th>Last name</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>

<p>Table with thead, tfoot, and tbody</p>
<table>
  <thead>
    <tr>
      <th>Header content 1</th>
      <th>Header content 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Body content 1</td>
      <td>Body content 2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Footer content 1</td>
      <td>Footer content 2</td>
    </tr>
  </tfoot>
</table>

<p>Table with colgroup</p>
<table>
  <colgroup span="4"></colgroup>
  <tr>
    <th>Countries</th>
    <th>Capitals</th>
    <th>Population</th>
    <th>Language</th>
  </tr>
  <tr>
    <td>USA</td>
    <td>Washington, D.C.</td>
    <td>309 million</td>
    <td>English</td>
  </tr>
  <tr>
    <td>Sweden</td>
    <td>Stockholm</td>
    <td>9 million</td>
    <td>Swedish</td>
  </tr>
</table>

<p>Table with colgroup and col</p>
<table>
  <colgroup>
    <col style="background-color: #0f0" />
    <col span="2" />
  </colgroup>
  <tr>
    <th>Lime</th>
    <th>Lemon</th>
    <th>Orange</th>
  </tr>
  <tr>
    <td>Green</td>
    <td>Yellow</td>
    <td>Orange</td>
  </tr>
</table>

<p>Simple table with caption</p>
<table>
  <caption>
    Awesome caption
  </caption>
  <tr>
    <td>Awesome data</td>
  </tr>
</table>
   ```
   
   ### Sorting Tables:
   
   There are no native methods for sorting the rows (```<tr>``` elements) of an HTML table. But using ```Array.prototype.slice()``` ```Array.prototype.sort()``` ```Node.removeChild()``` and ```Node.appendChild()``` you can implement your own ```sort()``` function to sort an HTMLCollection of ```<tr>``` elements.
   
   ```html
   <table>
  <tbody>
    <tr>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
    </tr>
    <tr>
      <td>1</td>
    </tr>
  </tbody>
</table>
```
```javascript
HTMLTableSectionElement.prototype.sort = function (cb) {
  Array.from(this.rows)
    .sort(cb)
    .forEach((e) => this.appendChild(this.removeChild(e)));
};

document
  .querySelector("table")
  .tBodies[0].sort((a, b) => a.textContent.localeCompare(b.textContent));
```
   ### Displaying large tables in small spaces
   
   A common issue with tables on the web is that they don't natively work very well on small screens when the amount of content is large, and the way to make them scrollable isn't obvious, especially when the markup may come from a CMS and cannot be modified to have a wrapper.
   
   ```css
   table,
th,
td {
  border: 1px solid;
}

table {
  width: 100%;
  max-width: 400px;
  height: 240px;
  margin: 0 auto;
  display: block;
  overflow-x: auto;
  border-spacing: 0;
}

tbody {
  white-space: nowrap;
}

th,
td {
  padding: 5px 10px;
  border-top-width: 0;
  border-left-width: 0;
}

th {
  position: sticky;
  top: 0;
  background: #fff;
  vertical-align: bottom;
}

th:last-child,
td:last-child {
  border-right-width: 0;
}

tr:last-child td {
  border-bottom-width: 0;
}
```
   
   <h3><a id ="forms">Forms</a></h3>
   
   The ```<form>``` is a HTML element that represents a document section containing interactive controls for submitting information.
   It is possible to use the ```:valid``` and ```:invalid``` CSS pseudo-classes to style a ```<form>``` element based on whether the elements inside the form are valid.
   
   <img src="https://user-images.githubusercontent.com/91787553/224036525-01662c59-8b67-4a8e-8923-eb15f9218f12.png">
   
   ```css
   <!-- Form which will send a GET request to the current URL -->
<form method="get">
  <label>Name:
    <input name="submitted-name" autocomplete="name" />
  </label>
  <button>Save</button>
</form>

<!-- Form which will send a POST request to the current URL -->
<form method="post">
  <label>Name:
    <input name="submitted-name" autocomplete="name" />
  </label>
  <button>Save</button>
</form>

<!-- Form with fieldset, legend, and label -->
<form method="post">
  <fieldset>
    <legend>Do you agree to the terms?</legend>
    <label><input type="radio" name="radio" value="yes" /> Yes</label>
    <label><input type="radio" name="radio" value="no" /> No</label>
  </fieldset>
</form>
```

  <h2><a id="project">Sample Project</a></h2>
