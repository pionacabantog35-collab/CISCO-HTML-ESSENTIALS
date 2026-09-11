MODULE 1
HTML = HyperText Markup Language

Hypertext - Refers to the text that contains links to the other documents or resources.
Markup - refers to the annotations or tags that are used to define the structure and formatting of content in a document.
Language - Refers to the system of rules and syntax used to write and interpret the markup in a consistent and standardized manner.

HTML and CSS - the core foundation of the web

HISTORY
Year: 1989
Inventor: Sir Tim Berners-Lee
First Version : HTML 1 (1993)
Current Version: HTML 5 (2014)
Organizations dedicated to maintain HTML standard WORLD WIDE WEB CONSORTIUM (W3C) and Web Hypertext Application Technology Working Group (WHATWG)

In summary, the future of HTML is full of exciting possibilities. From mobile-first design to VR integration and IoT compatibility, HTML is evolving to keep up with the ever-changing landscape of web development 

SETTING UP AN HTML DEVELOPMENT ENVIRONMENT

TEXT EDITOR
Text Editor - software that allows you to create and edit plain text files and to write and edit code. Notepad or TextEdit

-Visual Studio Code
-Sublime Text
-Notepad++

WEB BROWSER
Web browser - to open, view and test your html code.


-Google chrome
-Mozilla Firefox
-Microsoft Edge

STEP BY STEP TO CREATE AN HTML FILE

Step 1 - Create an HTML file
Open your test editor and create a new file. Use .html extension

Step 2 - Write the HTML code
Add the essential structure of an HTML document.

EXAMPLE:
<!DOCTYPE>
<html>
<head>
    	<title>My First Web Page</title>
</head>
<body>
	<h1>Hello, World</h1>
	<p>This is my first web page.</p>
</body?
</html>
Step 3 - Save and open the HTML fie
Save the HTML file and navigate to the location where you saved it. Double-click on the file, and like magic, it will open in your default web browser. Voila! You'll see your web page displayed beautifully. 

CHARACTER ENCODING
Character encoding is the method used to represent characters as numbers that computers can understand.

Bits - Binary digits “on” “off”(1 or 0) the basic building blocks of digital information.
Decimal - ten digits (0-9) to represent all numbers.
Hexadecimal - 16 digits and letters (0-9 and A-F)

ASCII (the american standard code for information interchange) - the most basic character encoding standard. Used 7 bits to represent 128 characters

UNICODE a more comprehensive character encoding standard that supports a much larger number of characters from different languages and scripts.

UTF-8 is a widely used character encoding standard that is compatible with ASCII. The most commonly used character encoding for web development today. The default encoding standard used by HTML 5.


HTML SYNTAX
Syntax is about following the rules of grammar to put words in the right order and use punctuation correctly so that sentences makes sense

HTML syntax refers to the rules, guidelines, and conventions that define how html code should be structured.

- DOCTYPE DECLARATION
An integral part of HTML syntax and an important element in an HTML document that helps web browsers understand how to interpret the documents. Trolls the web browser which version of html is being used in the document.

 		<!DOCTYPE html>

This tells the web browser that the document is written in HTML 5.

ELEMENTS AND TAGS
HTML  is made up of a series of elements, which are defined by tags.

HTML ELEMENTS
Part of a webpage, like a paragraph of text, an image or a form. The basic unif of content and structure within an HTML document.

HTML TAGS
Tags are the markers that define the start and end of an element. Written with angle brackets <tags> </tags>

Example paragraph <p></p>








Self Closing Tags
The image element <img?> dont contain content and therefore dont have a closing tags.

	<img src=”image.jpg” alt =”Description of the image”>

- Element  refers to the whole structure, including opening tag, the content, and the closing tag(if present).
- Tag refers specifically to the opening and closing markers that define the start and end of an element.


BLOCK LEVEL AND INLINE ELEMENTS
Two types of elements: block level elements and inline elements.

Block Level Elements
Used to create the main structure of a web page, such as headers, paragraphs and lists. They start on a  new line and take up the full width of the page.

<h1> through <h6> for headings
<p> for paragraphs
<ul> and <ol> for list 
<div> for grouping content.

Inline Elements
Used to style content within block level elements such as links and images.
They don’t start on a new line and only take up as much space as needed to display their content.

<a> for links
<img> for images 
<span> for styling content

HTML COMMENTS
Html comments are a way to add notes or remarks in a html documents that won’t be visible to the user.

	<!-- and -- !>
<!-- this is a comment.  – !>

ATTRIBUTES AND VALUES
Attributes provide additional information about element.
Example <img> are src attribute which specifies the path to the image file.
Alt attribute which provides a text description of the image that is displayed when the image cannot be loaded or seen.

<img src=”image.jpg” alt =”A detached house”>

Src - attribute
“image.jpg “ - value
Alt - attribute
“A detached house” - value

GLOBAL AND ELEMENT SPECIFIC ATTRIBUTES
 -Global Attributes  which can be applied to any HTML element. They are useful for a wide range of purposes, such as assigning unique identifiers, adding classes for styling, or providing additional information about an element. Examples include id, class, style, and title. 

-Element-specific attributes, which are specific to particular HTML elements and cannot be used with all elements. They provide functionality or modify the behavior of specific elements, making them essential for proper usage of those elements. Examples include href (specific to <a> elements), src (specific to <img> and media elements), and type (specific to <input> elements).

HTML HEAD AND BODY

The HTML tag

The HTML tag (<html>) is one of the most important tags in an HTML document, as it defines the entire web page and serves as the starting point for every HTML document. It informs the browser that the document is an HTML document, and it is the first tag in every HTML document. 

<!DOCTYPE html>
<html>
<!-- The hidden content of an HTML document: the head section will go here. --> <!-- The visible content of an HTML document: the body section will go here. -->
</html>

Note: The HTML tag appears after the <!DOCTYPE html> declaration, and it's opened with the <html> tag. The HTML tag encompasses the entire document, and all the content on the web page appears between the opening and closing HTML tags. The closing HTML tag is denoted by </html> and appears at the end of the document. 

THE HEAD SECTION
The head section is an important component of an HTML document that contains information used by the browser to display and interact with the web page. It can optimize the web page for search engines and furnish additional context to users. 

Page title, i.e. the title of the web page that appears in the title bar of the browser and is used by search engines to display the page title in search results.

Example: <title>My Web Page</title>

Metadata, which includes the description and keywords that are used by search engines to index and rank the web page, instructions for web crawlers how to index and display the web page, or information about the author and creation date of the page.

Example: <meta name="author" content="Peter Jackson">

Links to external files, which includes CSS stylesheets and JavaScript files that add styling and functionality to the web page.

Example: <link rel="stylesheet" href="styles.css"> <script src="script.js"></script>

Character encoding, which tells the browser what character set to use when displaying the web page. (You already know that, don’t you?)

Example: <meta charset="UTF-8">
<!DOCTYPE html>
<html>
	<head>
		<title>My Web Page</title>
		<meta name=”description” content=”This is a website about soccer!”>
		<link rel=”stylesheet” href=”styles.css”>
		<script src= “script.js”></script>
	<head>
<!--labflasg–!>
</html>

THE BODY SECTION
The body section is the part of an HTML document that contains the visible content of the web page (i.e. text, images, videos, forms, links, etc.) and it's the area where you can get creative with your design and layout. 

Text - heading, paragraphs, and other text elements to present your content to the user.
Images - all types of images, such as photos, icons and logos.
Videos - Add video content such as tutorials and product demos to provide more information to the user.
Forms - Create elements that allow users to submit information such as text, boxes, dropdown menus, and buttons to gather data from the user.
Links - links to other pages on the web or within the same website, making  it easer for the user to navigate through your content
Lists - list to organized content; unordered and ordered lists 
Tables -  use tables to present data in a structured way

<!DOCTYPE html>
<html>
	<head>
		<title>John Smith photography</title>
		<meta name=”description” content=”John Smith Photography                specialized in capturing authentic>
<link rel=”stylesheet”> href=”styles.css”
<script src=”script.js></script>
	</head>
	<body>
	<h1>Bringing your brand to life with striking visuals</h1>
		<p>lorem ipsum dolor sit amet</p>
		<img src=”/resources/media/html-ess-1-7-1-apple-photo.jpg” alt =”Apple Photo”>
</body>
</html>

RELATIONSHIP BETWEEN HTML, CSS, JAVASCRIPT
- HTML provides the basic structure and content of the web page
- CSS defines the presentation of html content, including its layout, colors and fonts.
- JAVASCRIPT adds interactivity to the webpage, making it more engaging and dynamic for the user.


HTML- structure, content and markup
CSS - presentation, style, formatting
JAVASCRIPT - interactivity, functionality, behavior

DOCUMENT OBJECT MODEL (DOM)
Powerful tool that allows web developers to change the content and structure of an html document using javascript code.

DOM is created as a memory representation of the web pages content and structure.

DOM represents the html document as a treelike structure which consists of various types of nodes.
<!DOCTYPE html>
<html>
	<head>
		<title> this is the title of my page</title>
	</head>
	<body>
		<h1>this is a heading</h1>
		<p>lorem ipsum dolor sit amet</p>
	<body>
</html>









