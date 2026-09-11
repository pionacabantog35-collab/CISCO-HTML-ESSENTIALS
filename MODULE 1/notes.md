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




