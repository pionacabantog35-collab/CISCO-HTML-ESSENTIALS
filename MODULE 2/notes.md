MODULE 2 FORMATTING

Headings provide structure and hierarchy to a web page by indicating which sections are more important or subordinate to others. 

There are six levels of HTML headings h1 to h2.

To provide accessibility and improve the user experience by helping visitors understand the content and structure of a web page.

Headings are also important for search engines as they use them to understand the topic of a web page and index1 (categorize) it accordingly.  


h1: 32px The largest and most important heading on the page. This is typically used for the title of the page or the main heading.

h2: 24px This is often used for the main section headings on a page.

h3: 18px This is often used for subsection headings or less important main headings.

h4: 16px This is often used for subsection headings or less important main headings.

h5: 14px This is often used for subsection headings or less important main headings.

h6: 12px The smallest and least important heading on the page. This is often used for minor headings or subheadings.

<p>tag and inline formatting
<p> this indicates that enclosed text should be treated as a separate paragraph, with a blank line inserted above and below the text. The <p> tag is a block level element, which means that it takes up the entire width of the container.

<p> Hello, Word</p>

HTML provides several inline tags that can be used to format text within a paragraph. 

The <strong> tag 
Is used to make the enclosed text BOLD
<p>This is some <strong> important strong</strong>text<p>

The <em> tag
Used to make the enclosed text italic.
<p>This is some text that requires<em>emphasis</em>.</p>
 
The <u> tag
<p> This is some text needs to be <u>underlined</u>.</p>

The <sup> tag
Used to make the enclosed text superscript
<p>1<sup>st</sup></p>

The <sub> tag
Used to make the enclosed text subscript
<p>1<sup>st</sup></p>

The <del> tag
Is used to strike through text
<p>Special Price: <del>$200</del> $7.</p>

The <mark>tag
Used to highlight text with a background color
<p>The deadline for submitting the report is <mark>Monday, March 12th</mark>.</p>



PARAGRAPH AND TEXT FORMATTING
Quotations: the <q> and <blockqoute> tags

<q> tag
Used for short inline quotes
<p><q>The only way to great work is to love what you.</q>

<blockqoute> tag
Used for longer , block quotes
<p>As Albert Einstein once said:</p>
<blockquote>
  <p>"Imagination is more important than knowledge. Knowledge is limited. Imagination encircles the world. The true sign of intelligence is not knowledge but imagination."</p>
</blockquote>
<p>This quote speaks to the idea that creativity and original thinking are more important than simply accumulating knowledge. It suggests that being able to see beyond what is already known and to imagine new possibilities is a key characteristic of intelligence.</p>

The <cite> tag
Mark up the title or source
<p>I recently read <cite>The Great Gatsby</cite> by F. Scott Fitzgerald.</p>


The content within the <cite> element is typically displayed in italic style.

	The <cite> attribute
<p>As Steve Jobs once said, <q cite="https://www.brainyquote.com/quotes/steve_jobs_416096">Innovation distinguishes between a leader and a follower.</q></p>
The <cite> attribute typically doesn't have a visible effect in a web browser, but it can be used by screen readers to provide additional context.

The <footer> tag
To provide more context for quotation
<blockquote>
<p>The more that you read, the more things you will know. The more that you learn, the more places you'll go.</p>
<footer>- Dr. Seuss</footer>
</blockquote>


LINE BREAKS AND HORIZONTAL RULES
Line break is a simple element that creates a new line of text within a block level element. <br> it doesnt require a closing tag

HORIZONTAL RULES
Horizontal rule is a visual element that creates a horizontal line across the width of a block level element. <hr> tag wherever you want to add line.

The <code> tag is used to display inline code snippets
	It is displayed in a monospaced font.
	
	To display preformatted text like computer code, poetry or song lyrics in html.
	
	<pre> Hello, World!
	What a sight to see, 
	A vast and endless web,
	Connecting you and me.</pre>

<pre> tag preserves all white space characters and displays the text in a monospaced font.

<kbd> for displaying keyboard input 
<samp> for displaying sample output

	HTML LISTS
	Allow groups a set of related items or pieces of information together
	
3 TYPES OF LISTS IN HTML
- Unordered lists
-Ordered lists	
-definition lists

UNORDERED LISTS 
<ul> tag are used to display a list of items with no particular order. Each item in the list is represented by <li> tag.

ORDERED LISTS
<ol> are used to display a list of items in a specific order. Each item in an ordered list is a represented by the <li> tag.

DEFINITION LISTS
Created with the <dl> tag, used to display a list of terms and their definitions.


NESTED LISTS
Nest lists within other lists. Create a hierarchy of information, where sub lists are indented to show they belong to a parent list item.

To create a nested list, simply place a new <ul> or <ol> element within an existing <li>. element .

HTML TABLES
	Display data in rows and columns.
	In creating table you need three elements: <table>,<tr>,<td>
<table>
	<tr>
	<td>Row 1, Column 1 </td>
	<td>Row 1, Column 2 </td>
	</tr>
	<tr>
	<td>Row 2, Column 1</td>
	<td>Row 2, Column 2</td>
	</tr>
<table>

ADDING HEADERS
<th> header for your table
<table>
	<tr>
	      <th>Service</th>
	      <th>Price</th>
           </tr>
	 <tr>
	       <td>Web design</td>
	       <td>$500</td>
             </tr>
	  <tr>
	        <td>Content Writing
	        <td>$200</td>
	  </tr>
	  <tr>
		<td>Social Media Management</td>
	   </tr>
</table>









