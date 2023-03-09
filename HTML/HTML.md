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
    <li><a href ="#para">Paragraph tag</a></li>
    <li><a href ="#heading">h tag</a></li>
    <li><a href ="#strongemstrike">Bold Italics and Underline</a></li>
    <li><a href ="#font">Font</a></li>
    <li><a href ="#image">Image</a></li>
    <li><a href ="#links">Links in html</a></li>
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
    
   <h3><a id ="para">Paragraph tag</a></h3>
    
   <h3><a id ="heading">h tag</a></h3>
    
   <h3><a id ="strongemstrike">Bold Italics and Underline</a></h3>
    
   <h3><a id ="font">Font</a></h3>
    
   <h3><a id ="image">Image</a></h3>
    
   <h3><a id ="links">Links in html</a></h3>
    
   <h3><a id ="table">Tables</a></h3>
    
   <h3><a id ="forms">Forms</a></h3>
    
  <h2><a id="project">Sample Project</a></h2>
