# Intro---HTML & CSS

## Unit 1: Introduction
HTML which is (Hyper Text Markup Language) is an internet backbone used to create Apps and websites. It helps computers understand what human want to say and do. The web uses 3 main languages HTML for content, CSS for styles and Javascript that adds interactions. If there are issues in THML or CSS, browsers try its best to keep things working, making them their problrm solving meaning if there is a mistake, browser tries its best to make it function.

## Unit 2 Text-Formatting
HTML uses tages which are enclosed in less or greater than symbols to mark different elements. They are opening tags and closing tags <p> for opening and </p> for closing. These tags are both required, you can not use openning tag without closing it, vice vesa.

Tags that are as follows
Body tags <body> </body>, This defines the document's body. element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, lists.
Paragraph tag <p> <p/>,  When you write a paragraph you open the tag and when you have finished you close it. The paragraphs can be separated  whith the same tags.
Headline tags <h> </h>, Headlines come in six different types: h1, h2, h3, h4, h5, and h6. These tags are used in headlines, and in sub headlines. The element which is h1 is the largest, and h6 is the smallest.
Bold tags <strong></strong> and <b></b>, these tags <strong> make the text to be bold which shows importance. The <b> is the normal one and does not have any meaning but just simply allows developer to make text bold.
Italic <i></i> and emphasized <em></em>, <em> emphasises a taext that is typically displayes as italic. These 2 tags <em> amd <i> may be similar in appearance but have different meaning.
List tags <li></li> These tags are used to define a list that is ordered (<ol>) or unordered (<ul>

HTML Quotes
<cite>, <q> and <blockqoute>, These quotes are usually used in articles most of the times. <cite> is use to reference a source's qoute. defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.). Specifies the source of the quotation. The text in the <cite> element usually renders in italic.
<q> is commonly used to determine inline quotes and can be indicated by quotation marks in the browser.
<blockqoute> Defines a section that is quoted from another source

Date Element
<time>  tag defines a specific time (or datetime). It allows us to write dates in a ways tha can be understood by people. There is also an attribute used which is datetime, which has a specific format like 2024-01-30 that tells the computer the exact date. e.g you can write January 30th between the <time> tags but we actually use (datetime) attricute like this <time datetime="2024-01-30">January 30, 2024</time >, This si what understoond by the computer. It Represent a machine-readable format of the <time> element

HTML superscripts, subscripts and small text
superscript tag <sup></sup> these are used for text that should be displayed above the normal text line, often for things like maths exponents
subscript tags <sub></sub> are used for text that should be displayed below the normal text line, commonly used in chemical formular or maths notations.
small text tag <small></small> these tags are used to decrease the size of the text.

HTML Code, pre and br
When you want to show code on a webpage, you can use the "code" element to make the text look like code. By default, this code will appear within the text, like part of a sentence. To display symbols like "<" or ">", you can use special codes so they don't get confused with HTML tags.
If you want to show code on a webpage without it running as actual code, you can use "br" (line break) and "pre" (preformatted) elements. "br" is a tag that creates a line break, and "pre" preserves the formatting and spaces you put in your code.
When writing code, you can add spaces and line breaks for readability, but the web browser usually ignores them. To make those spaces and breaks visible, you can use "br" at the end of each line.

## Unit 3 HTML capabilities
Opening Developer Tools, Right click on a webpage & choose inspecter element or go to tools then web developer and select inspector, this will open up a set of tools
Inspector section, in the inspector you will see 3 sectionswhich are HTML on the left, CSS on the middle and more other options on the right the focus on HTML section on the left.
If you encounter issues like unordered list showing an unexpexted empty item, then you can use develper tools to inverstigste, the browser will try to fix the HTML mistake by adding an extra item
When evaluating markup, it is critical to visit other websites with similar information and utilize the HTML inspector to identify errors. For example, if the website was created by a team we admire, analyzing their work allows us to better grasp how to structure our own HTML. Additionally, the HTML inspector in the development tools can be utilized to debug errors.
One problematic code example is an unordered list with four elements that should be numbered one, two, three, four. However, the results display a blank list rather than five things. To resolve this, we can open the developer tools by right-clicking and looking closer. It turns out that the browser adds an additional set of tags while constructing the DOM tree

HTML Attributes
Attribute provide an additional information about the elament.
Class Attribute, is like giving name to a group of element  on a webpage. it is used to style multiple elements once using CSS. i.e if you want all youe headings to look the same you just give them the same class.
ID Attribute, this is similar to Class ID but can only be used once in a page. It is useful for creating links  that jump to a specific section on the page.

ARIA Roles
these are extra attributes added to HTML elements to help browser understand thier  meaning, and that ensure websites are accessible to everyone including those with dissabilities. Accessibility require website to be accesible to everyone.
ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. The goal is to rely on proper HTML elements to convey the right message about the content's meaning, without needing ARIA Roles
The accessibility tree, a component of the DOM tree, is essential for assistive devices like screen readers to improve user experience. It treats content as separate text containers, potentially causing poor reading experiences.

Formatting HTML
White space in HTML, HTML ignores extra spaces, tabs or linr breaks, however elements like <pre>, <code> and <extraarea> or when modified with CSS may consider extra spaced and indetations. If tou modify whitespace handling with CSS, it can affect how spaces and indetantions are displayed. In most cases browser do not care about more than a single space. 
Comments are added usibg <!--comment here-->, This is helpful for quickly identifying when con code is commented out, preventing confusion when it does not function well.
Using Uppercases for tags, like <LI></LI> does not affect the browser's rendering. Its a matter of conveting and readability.
To insert video we use <video src= "file.mov"></video>, for inserting an image <img src= "file.jpg"></img>, make sure you choose the correl url of that image or video.

## Unit 4 Navigation and Linking
Linking
<a href="url">link text</a> This will display the word written in "link text" which is the link that will navigate to another page.
The link's destination is specified in the href attribute.
The <link> tag defines the relationship between the current document and an external resource. i.e  <link rel="stylesheet" href="styles.css">

Navigation
The <nav> tag defines a set of navigation links
 When you make pages, each page i.e home, About, prices and contact. must be inside the <nav>, <ul> and <liL i.e  <nav> <ul> <li><a href="#">Home</a></li></ul> </nav>

HTML URL Pathways
There is a folder with files, like images and screens. Its file has its own location in that folder. Web addresses (URL) helps us finds the link of these files.  For example If the folder has a file name Images, then you are looking for a certain image in the file. You can not just type the URL of an image, you start looking for a file from the folder then then the image URL. Which means the image you are looking for might use the URL (/images/myself.jpg) or (../images/myself.jpg)
There are two types of URLs:  Absolute and Relative URL. An absolute URL provides the complete web address for a resource, including the protocol (usually "http" or "https"), the domain name (e.g., www.example.com), and the specific path to the resource on the server. A relative URL, on the other hand, specifies the location of a resource in relation to the current document. It doesn't include the full domain and protocol information but provides a path relative to the current page.

## Unit 5 Working with Graphics and Images
There are four attributes that need to be included for every image:
First, we have the source attribute (SRC), which tells the browser which image file to load. 
Then we have the alt attribute (ALT), which provides a text description of the image. 
Lastly, we have the width and height attributes, which determine the size of the image.
it can be coded using the ff code <img src="myself.jpg" alt="My self">
Use the figcaption element to wrap the text and designate it as a caption. Then, put the image and the caption together in a figure element. <figure><img src="vuyo.png" alt="Myself" width="250" Height="200"><figcaption>This is my self</figcaption></figure>

SVGs (Scalable Vector Graphics):
Ideal for logos, icons, and illustrations.
They use instructions to draw images, not pixels.
Can be resized to any size without losing quality.
Small file sizes.

GIFs (Graphics Interchange Format):
Good for illustrations with big areas of the same color.
Not great for photos because they only support 256 colors.
Transparent parts are possible, but edges might look jagged.

JPGs (Joint Photographic Experts Group):
Good for compressing photos.
Commonly used by cameras.
Resize and compress properly for faster website loading.
Adjust color info to find the right balance between quality and size.

PNGs (Portable Network Graphics):
Good for transparent photos.
Can sometimes compress images better than GIF or JPG.
Experiment with different options for the smallest file size.

General Tips:
When dealing with images, consider size, format, and compression for faster downloads.
HTML code remains the same regardless of the image format chosen.
In a nutshell, SVGs are great for logos and icons, GIFs are good for simple illustrations, JPGs are for photos but need careful resizing, and PNGs are good for transparent images. Always think about the size and compression to make your website load faster.

## Unitt 6 Working With Media
The audio element is different from the image element because it has both an opening and a closing tag, <audio controls src="audio.mp3"></audio>
Instead of relying on pre-built audio player controls, there is an option to create your own using JavaScript and the HTML media element API, <audio controls><source src="http/:example.com" type="audio/org:code">
In Videos, Just like the audio element, the video element has an opening and closing tag. To display a video, use the source attribute to specify the video file, <video controls><source src="http/:example.com" type="video/mp4"></video>

Use the track element and link it to a text file to add captions to the video. This element adds functionality to the video player, allowing viewers to toggle captions on and off or switch between different subtitle options. <video controls><source src="http/:example.com" type="video/mp4"><track src="https/:,..." kind="caption" label="english" srclang="en" default>

An iframe is like a mini-browser window embedded within your webpage.
You use an HTML tag called <iframe> and provide the web address (URL) of the content you want to show inside it.
You can embed things like videos, maps, social media posts, or any other content that can be displayed on a webpage.
Example: Embedding a YouTube video:
If you want to put a YouTube video on your webpage, you grab the video's URL and put it inside an <iframe> tag like this:
<iframe width="560" height="315" src="https://www.youtube.com/embed/your-video-id" frameborder="0" allowfullscreen></iframe>

## Unit 7 HTML Content Identification
 In HTML, there are tools to indicate the language of your content. By setting things up correctly, search engines will understand which language websites are in. Spell checkers will provide the appropriate dictionaries, and when a browser reads the content aloud, it will pronounce the words correctly. The lang attribute is used to specify the language of a webpage.<html lang="eng">

Meta charset="UTF-8" Imagine the text on the internet is like a big playground with lots of different characters, letters, and symbols. Now, to make sure everyone understands each other, we use something called Unicode, which is like a set of rules for all the characters to play nicely together.
UTF-8 is like a special rulebook within Unicode that helps handle a huge variety of characters, from regular letters to cool emojis.
Now, when you visit a website, your computer needs to know which rulebook (UTF-8 in this case) the website is using. If it doesn't know, things might get a bit mixed up, and the text could look strange or unreadable.
To avoid this confusion, websites use a little code called HTML, and within HTML, there's a tag (like a label) called "meta charset." By adding this tag and setting it to "UTF-8," it's like telling your computer, "Hey, we're using the UTF-8 rulebook here!" This tag is placed in the head section of each webpage, sort of like the instructions at the beginning of a book.
So, in simple terms, adding a meta charset tag with UTF-8 in HTML is like making sure everyone on the internet playground is reading from the same rulebook, preventing any confusion and making the text look right for everyone. 

<div>
It helps you group and organize content. You can put other elements like text, images, or even other <div> elements inside it.
It's like having separate sections on a page for different types of content.
<div>
   <p>This is some text inside a division.</p>
   <img src="image.jpg" alt="An image">
</div>
In the example above, the <div> is like a box containing a paragraph and an image.
 
3. <span>
<span> is like a small container but is used for inline elements, not big blocks like <div>.
It's handy when you want to apply styles or do something specific to a small piece of text or content within a larger block.
<p>This is <span style="color: blue;">blue</span> text.</p>
In this example, only the word "blue" will be colored blue.

<div> is like a big container or box, grouping larger chunks of content.
<span> is like a small container, used for specific bits of content within a larger block.
These elements help you structure and style your webpage, making it organized and visually appealing.

## Unit 8 HTML Integration

The header and footer elements mark the header and footer areas on the page. Do not confuse header with head though. Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.

Think of building a webpage like creating a special document. There are a few important things you need to include in every document to make sure it works well and looks right.
 Doctype Statement: It's like telling the computer, "Hey, this is a modern webpage, so use the latest rules and techniques." It's at the very beginning of the document.
HTML Element:This is like putting a frame around your entire document. You say, "Everything inside this frame is my webpage." There's an opening tag at the top and a closing tag at the bottom.
Language and Direction: Right after the HTML tag, you tell the computer some basic info about your document. It's like saying, "This is in English, and you read it from left to right."
Head and Body Elements:Inside the HTML frame, there are two important sections - the head and the body. The head is like the backstage where you give instructions to the computer, but the audience (your visitors) doesn't see it. The body is where you put all the actual content of your webpage, like text, pictures, and links. That's where the action happens

Alright, let's simplify this!

Inside the Head
Character Set Meta charset="UTF-8" : Think of it like the secret code your computer needs to understand the text on the webpage. The browser uses the meta tag to figure out this code, and it's placed in the head.
Title Element <tittle>Our Website></tittle>: Imagine the title as the name of your webpage. It's not something you see on the page, but it shows up on the browser tab or bookmark, helping you recognize the page.

**More Uses of Meta Element**
Responsive Design: The meta tag can tell the browser, "Hey, this webpage adjusts well on small screens," making it look good on phones.
Description for Search Engines: Ever wondered why some info shows up when you search for a website? The meta tag helps search engines display a short description.
Saving to Home Screen: When you save a webpage to your home screen, the meta tag helps name it.
Sharing on Social Media: Meta tags make links look cool when shared on platforms like Twitter or Slack.

**Link Element**
Connecting Assets: The link tag helps connect different things your webpage needs, like styles, fonts, and icons.
Rel Attribute: It tells the browser what kind of thing you're connecting (like a stylesheet).
Href Attribute:  It says where to find the connected thing (like the web address).

**Script Tag**
JavaScript Instructions: The script tag tells the browser to load a JavaScript file. Usually put at the end of the document but sometimes in the head.

## Unit 9 Working with Forms and Interactive Elements
<form>
    <label>Name</label> <input>
     <label>Email</label> <input>
     <button>SignIn</button>
</form>

Or 
<form action="success.html" method="get">
<label for="name">Name</label>
<input name ="name" id="name"type="text">

<label for="email">Email</labela>
<input name="email" id="email" type="email" required placeholder="example@gmail.com">

<label for ="phone">Phone Number</label>
<input name="phone" id="phone" type="tel">

<label for="textarea">Message</labal>
<textarea id="textarea" name="textarea" cols="10" rows="15"></textarea>

<button>Sign Up</Button>
</form>

Label Element: Labels are like tags for the fields in your form. For a newsletter signup, you might have fields like name and email. Labels help explain what goes where.
Input Element: This is where people type in their info. It's like a blank space waiting for your name or email. Unlike other things, it doesn't need a closing tag; it's just a marker for the computer to bring in the typing area.
Button Element: Every form needs a button to submit the info. It's like the "Go" button. You can write whatever you want on it.
Making It Work: Without a backend (the tech magic behind the scenes), it won't do much. You add attributes like "action" and "method" to connect it to the backend. 
Naming the Data: When you submit the form, the info doesn't show up on the response page. You add a "name" attribute to each input so the computer knows what's what.
Accessibility: Imagine someone using a screen reader or not using a mouse. You need to connect the label to the input so they know what to type where.
Two ways to do it:
      - Add a "for" attribute to the label that matches the "id" of the input.
      - Wrap the input with the label.
Testing Connection: Click on the label and make sure the typing area gets highlighted. This helps everyone, especially those who rely on it.

Specify Input Types: For the name field, you don't need to do anything special because it's for text (the default). So, it's like saying, "Hey browser, expect text here." For the email field, you tell the browser it's for email addresses by adding `type="email"`. This helps the browser check if what's typed is a valid email.
Make Email Field Required: Add `required` to the email field. It's like saying, "Hey, you must fill this out before moving on." The browser won't let them submit the form without an email.
Add Placeholder for Clarity: Make the email field friendlier by adding a suggestion inside it. Use `placeholder="Enter your email"` to give users a hint. It's like saying, "Hey, this is what I expect from you."

## Unit 10 Organizing Tabular Information in HTML

## Building HTML Tables
<table></table> ths is a table, it wraps all table
<tr></tr> is the table row, Wraps around set of elements defining them as belonging to the same row. it have attributes which are colspan, rowspan and headers
<td></td> is the table data, marks the actual bits of data. 
<th></th> these are table headers that defines a header for a column. it have attributes which are colspan, rowspan and scope
for example: 
<table>
  <tr>
    <th>Full Name</th>
    <th>Address</th>
    <th>contact</th>
  </tr>
  <tr>
    <td>Gogi Vuyo</td>
    <td>Vlei A/A</td>
    <td>0789318700</td>
  </tr>
  <tr>
    <td>Lutho Mbekwa</td>
    <td>Mkhambathi Res</td>
    <td>0733047979</td>
  </tr>
</table>

## CSS

## Intro to CSS
CSS, short for cascading style sheets, is the language that controls the pretty stuff on websites, it holds all the styles for your webpage, It describes how HTML elements should be displayed on the web page.. This adds visual appeal to your webpage. To connect the HTML and CSS, you simply link them togethe. HTML and CSS work hand in hand to create the visual aspects of a webpage.
In CSS, each style declaration consists of two parts: A property and A value. 

3 Types of CSS
Inline CSS: Putting the styling directly on the HTML element.
Example: Adding color directly to a paragraph in the HTML code using style atttribute, like <p style="color: blue;">This is a blue paragraph.</p>.

Internal or Embedded CSS: Putting the styling code within the HTML file, specifically in the head section.
Example: Writing styles in the <style> tag inside the <head> section of your HTML file.

External CSS: Storing styling in a separate CSS file. Usually the file is named as style.css
Example: Creating a separate file (e.g., style.css) with your styling rules and linking it to your HTML file using the <link> tag in the head section. (<link rel="stylesheet" href="mystyle.css">)

/* This is a single-line comment */ This is the CSS comment

## Uniti 2 Adding Selectors

#id: Selects the HTML element with a specific id.
Example: #firstname selects the element with id="firstname".

.class: Selects the HTML element with a specific class  
Exaple: .intro:	Selects all elements with class="intro"

element.class: Selects a specific type of HTML element with a specific class.
Example: p.intro selects only <p> elements with class="intro".

element: Selects a specific type of HTML element.
Example: p selects all <p> elements.

Class Selector: Used to select and style elements based on their class attribute.
Syntax: .classname { /* styles go here */ }
Example: If you have HTML elements with class="box", the corresponding CSS rule would be .box { /* styles go here */ }.

Grouping Selector/ Eelement,Element,...: Allows you to apply the same styles to multiple selectors by grouping them together.
Syntax: selector1, selector2, selector3 { /* styles go here */ }
Example: h1, h2, p { /* styles go here */ } will apply the specified styles to all <h1>, <h2>, and <p> elements.

Descendant Selector: Selects an element that is a descendant of another specified element, no matter how deeply nested.
Syntax: ancestor descendant { /* styles go here */ }
Example: div p { /* styles go here */ } selects all <p> elements that are descendants of a <div>.

Summary:
Class Selector is used for styling elements with a specific class.
Grouping Selector is used to apply the same styles to multiple selectors.
Descendant Selector is used to style elements that are descendants of a specified ancestor.

## Unit 3 Images and colors

Color Representation:
Keyword: Use predefined color names.
Example: color: red;

Hexadecimal: Represent colors using a hexadecimal code.
Example: color: #ff0000; (red)

RGB (Red, Green, Blue): Specify colors using values for red, green, and blue.
Example: color: rgb(255, 0, 0); (red)

RGBA (Red, Green, Blue, Alpha): Similar to RGB, but includes an alpha channel for transparency.
Example: color: rgba(255, 0, 0, 0.5); (semi-transparent red)


HSL (Hue, Saturation, Lightness): Define colors based on their hue, saturation, and lightness.
Example: color: hsl(0, 100%, 50%); (red)

HSLA (Hue, Saturation, Lightness, Alpha): Similar to HSL, but includes an alpha channel for transparency.
Example: color: hsla(0, 100%, 50%, 0.5); (semi-transparent red)

Background Color: background-color: value;
Example: background-color: #ffffff; (white background)

Border Color: border-color: value;
Example: border-color: rgb(0, 255, 0); (green border)

Text Color: color: value;
Example: color: #333333; (dark gray text)
Link Color: a:link { color: value; }
Example: a:link { color: #0000ff; } (blue unvisited link)
Hover Color: a:hover { color: value; }
Example: a:hover { color: #ff0000; } (red link on hover)

## Unit 4 CSS Boxes, types and sizes
Understanding Type in CSS

Serif Fonts: These have small lines at the ends of the letters, and they were traditionally used for printed materials with lots of text. The little lines (serifs) helped connect the letters and made reading easier.
Sans Serif Fonts: These don't have those small lines at the ends, and they look more modern. On the web, we often use sans serif fonts because they are clean and easy to read on screens.
font-style: italic (this makes the font to be italic

font faces are safe to use online without Google Fonts or similar online font repositories: Arial, Helvetica, and Verdana.

## absolute and relative units
Absolute units, like points or pixels, maintain a constant size, while relative units, such as percentages or "rem," adjust based on the page size, providing better flexibility.
The preferred font size unit, "rem," is explained, with 1 rem equal to 16 pixels. The Point to REM Converter tool is introduced to facilitate unit conversions, especially for those more familiar with pixels or points.
Each font is evaluated to see if it is available. The first one that is available displays. If no fonts are available, the stack defaults to the specified generic font (sans-serif, serif).
Margin: 30px (on all 4 sizes we want 30px), margin to separate the block from things outside it
padding: 10px 20px (to the left & right we want 10px, top and buttom we want 20px), space between the content and the border that may take on a background color, it is transparent
border: 1px solid yellow: ( 1px is how thick, solid is its style, yellow is its color), The border is the line that surrounds the padding and content, defining the boundaries of the element.
It separates the padding from the outer space (margin).
border-radius: 5px (circle on thr egdes)
box shoadow: 10px, 20px, 30px, blue. This is the box shadow (if you want left shadow use (-px) then color of the shadow here is blue)

## Uniit 5 Advanced CSS Properties and Concepts
To change link colors, the passage suggests targeting the "a" anchor tag in HTML.
The a:hover state allows customization when hovering over a link.
Example: Changing the color to #fe6100 (pink) and removing the underline with text-decoration: none
To have separate styles for visited and unvisited links, use a:link for unvisited and a:visited for visited.
Example: Defining a nice blue color for unvisited links and a purple shade (#785ef0) for visited links.

Changing Font: At the beginning, we decide to change the font of our webpage to Arial. This affects the whole page.
Inheriting Fonts: When we change the font for the main part of the page (the "body" element), all the stuff inside it, like headings and paragraphs, automatically get the same font. It's like a family sharing the same style.
Adding a Border: We also put a red border around the whole page. Unlike the font, this border doesn't automatically apply to everything inside. We have to be specific about where we want the border.
Example with "*" Selector: We show an extreme example using the "*" selector, which selects everything. If we put a border on everything, It demonstrates that not everything should inherit certain styles, especially borders.
Control Over Styles: We explain that sometimes we want control over what styles get inherited and what don't. For instance, we might want a border for the whole page but not for every little thing inside it.
Importance for Developers: For people who create websites (developers), understanding this helps in making sure the webpage looks good and isn't messy. It's like knowing how to organize things neatly.
Final Point:

## Debugging CSS with Borders and Background Colors
When you're working with CSS to style elements on a webpage, you might face challenges where your styles don't seem to work as expected. Debugging, or finding and fixing these issues, can be made easier with a helpful trick.
One way to debug is by adding a background color or a border to the element you're trying to style. For example, let's consider an unordered list (UL) in HTML. If you want to understand the position of the UL on the page, you can add a border with a CSS style like "border: 2px solid red." This border will reveal the full width of the UL, showing that it extends across the body element.

Now, comparing the UL to the link (A) within the list item (LI), setting the background color of the link to FFB000 shows that links are only as wide as their content. This highlights the difference between block elements (like UL and LI) that take up the full width of their container and inline elements (like links) that are only as wide as their content.
Suppose you want a hover effect that covers the entire width but only for the link. Changing the A (link) to an LI (list item), which is a block-level element, allows you to apply a hover effect using the "LI:hover" selector. The hover effect now covers the entire document width, revealing a potential problem—clicking at the edges of the document doesn't work with the link because it's only as wide as its text.
To solve this, a quick fix for advanced users is adding the CSS style "display: block" to the A selector, stretching the link across the page. Additionally, defining a hover state for the link using "A:hover" can change the background color and text color. This ensures that hovering over the edges indicates the link is clickable, and the hover state spans the entire list.


## Introduction to JavaScript

JavaScript is programming language in web development, responsible for creating interactive elements and animations on web pages. It plays a vital role alongside HTML and CSS, forming the three pillars of web development. JavaScript is specifically designed to integrate seamlessly with HTML and is widely supported by major web browsers, though users can choose to disable its support. Examples of JavaScript applications include search boxes, live sports scores, and video playback on websites.

Comments:
Comments in JavaScript are used to add explanatory notes or remarks within the code. They are ignored by the JavaScript interpreter and do not affect the execution of the code. Single-line comments are denoted by "//", and multiline comments are enclosed between "/" and "/".
// This is a single-line comment
/*
This is a
multiline comment
*/

## Variables:
Variables are containers for storing data values. In JavaScript, you can declare a variable using the var, let, or const keyword.
var age = 25;      // Declaring a variable using var
let name = "John"; // Declaring a variable using let
const pi = 3.14;   // Declaring a constant variable using const

## Operators:
Operators perform operations on variables and values. Common types of operators in JavaScript include arithmetic, assignment, comparison, logical, and more.
// Arithmetic operators
let sum = 5 + 10;
let product = 3 * 7;

// Assignment operator
let x = 20;

// Comparison operators
let isEqual = (x === 20); // Strict equality check

// Logical operators
let isTrue = (true && false); // Logical AND

Assignments:
Assignments involve giving values to variables. Variables can be assigned values using the assignment operator (=).
let message;        // Declare a variable
message = "Hello";  // Assign a value to the variable

// Combining declaration and assignment
let greeting = "Hi";

## Arithmetic operators
Unary Operatoras These operators require one operand for operation. Providing two or more can result in a syntax error for example The typeof operator returns the data type of a value. It requires only one operand. Here's an example: typeof "hello"
Binary Operator These operators require two operands for operation. If one or more than two operands are provided, such operators result in a syntax error. All arithmetic operators are binary operators. You have the first operand on the left of the operator, and the second operand on the right of the operator. 

Remainder (%) 
Binary operator. Returns the integer remainder of dividing the two operands, for example 12 % 5 returns 2. 

Increement operator (--) Unary operator. Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one. 
If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4. 

Decrement (--)  Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator. 
If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2. 

Unary negation (-) Unary operator. Returns the negation of its operand. If x is 3, then -x returns -3. 

Unary plus (+)  Unary operator. Attempts to convert the operand to a number, if it is not already.  +"3" returns 3.  +true returns 1. 

Exponentiation operator (**) Calculates the base to the exponent power, that is, baseexponent 
2 ** 3 returns 8. 
10 ** -1 returns 0.1

## Bitwise Operators
Bitwise AND 
a & b 
Returns a one in each bit position for which the corresponding bits of both operands are ones. 

Bitwise OR 
a | b 
Returns a zero in each bit position for which the corresponding bits of both operands are zeros. 

Bitwise XOR 
a ^ b 
Returns a zero in each bit position for which the corresponding bits are the same. 
[Returns a one in each bit position for which the corresponding bits are different.] 

Bitwise NOT 
~ a 
Inverts the bits of its operand. 

Left shift 
a << b 
Shifts a in binary representation b bits to the left, shifting in zeros from the right. 

Sign-propagating right shift 
a >> b 
Shifts a in binary representation b bits to the right, discarding bits shifted off. 

Zero-fill right shift 
a >>> b 
Shifts a in binary representation b bits to the right, discarding bits shifted off, and shifting in zeros from the left. 


### Strings & Arrays

## Strings:
A string is a sequence of characters, such as "hello" or "JavaScript".
Strings are immutable, meaning their values cannot be changed after they are created.
You can access individual characters in a string using bracket notation or methods like charAt() or substring().
Common string methods include toUpperCase(), toLowerCase(), trim(), split(), indexOf(), lastIndexOf(), startsWith(), endsWith(), replace(), and many others.

Example:
let myString = "Hello, world!";
console.log(myString[0]); // Output: "H"
console.log(myString.charAt(7)); // Output: "w"
console.log(myString.toUpperCase()); // Output: "HELLO, WORLD!"
console.log(myString.split(", ")); // Output: ["Hello", "world!"]

## Arrays:
An array is an ordered collection of values, which can be of any type, including strings, numbers, objects, or even other arrays.
Arrays are mutable, meaning you can change their elements.
You can access individual elements in an array using bracket notation and various methods like push(), pop(), shift(), unshift(), splice(), slice(), indexOf(), includes(), and many others.
Arrays have a length property that indicates the number of elements in the array.

Example:
let myArray = ["apple", "banana", "orange"];
console.log(myArray[1]); // Output: "banana"
myArray.push("grape"); // Adds "grape" to the end of the array
console.log(myArray); // Output: ["apple", "banana", "orange", "grape"]
console.log(myArray.length); // Output: 4

Converting between Strings and Arrays:
You can convert a string to an array using the split() method.
You can convert an array to a string using the join() method.

Example:
let myString = "Hello, world!";
let myArray = myString.split(", ");
console.log(myArray); // Output: ["Hello", "world!"]

let newArray = ["Hello", "world!"];
let newString = newArray.join(", ");
console.log(newString); // Output: "Hello, world!"
Understanding how to manipulate strings and arrays is crucial for working effectively with JavaScript and building dynamic web applications.

## Functions:
In JavaScript, functions are blocks of reusable code that perform a specific task. They allow you to encapsulate logic, making your code modular, easier to read, and easier to maintain. 

Function Declaration:
You can declare a function using the function keyword followed by the function name, parameters (if any), and the function body enclosed in curly braces {}.
function greet(name) {
  console.log("Hello, " + name + "!");
}

Function Expression:
You can also define functions using function expressions, where the function is assigned to a variable.
const greet = function(name) {
  console.log("Hello, " + name + "!");
};

Arrow Functions (ES6+):
Arrow functions provide a more concise syntax for writing functions.
const greet = (name) => {
  console.log("Hello, " + name + "!");
};

Function Invocation:
To execute a function, you simply call it by its name followed by parentheses ().
greet("Alice"); // Output: Hello, Alice!

Parameters and Arguments:
Parameters are placeholders for values that a function will receive when it's called. Arguments are the actual values passed to the function during the function call.
function add(a, b) {
  return a + b;
}
console.log(add(2, 3)); // Output: 5

Return Statement:
Functions can return values using the return statement. When a return statement is encountered, the function stops executing and returns the specified value.
function multiply(a, b) {
  return a * b;
}
console.log(multiply(2, 3)); // Output: 6

Function Scope:
Variables declared inside a function are scoped to that function and are not accessible from outside.
function scopeExample() {
  let x = 10;
  console.log(x); // Output: 10
}
scopeExample();
console.log(x); // Error: x is not defined

Anonymous Functions:
Functions without a name are called anonymous functions. They are often used as callback functions or immediately invoked function expressions (IIFE).
const result = (function() {
  return "Hello from IIFE!";
})();
console.log(result); // Output: Hello from IIFE!

Callback Functions:
Functions passed as arguments to another function are called callback functions. They are commonly used in asynchronous code, event handling, and array methods like map(), filter(), forEach(), etc.
function myCallback(value) {
  console.log(value);
}
const myArray = [1, 2, 3];
myArray.forEach(myCallback); // Output: 1 2 3

alert() causes an alert dialog box to appear over the page that launched it
write() writes content to a page
focus() causes the mouse cursor to be inserted into a form element.

## Booleans:
In JavaScript, booleans are a data type that represents one of two values: true or false. Booleans are commonly used in conditional statements, loops, and logical operations to control the flow of a program.

Boolean Values:
true: Represents a true condition.
false: Represents a false condition.

Boolean Context:
Many JavaScript expressions are automatically converted to booleans when evaluated in a boolean context. For example, in an if statement, the expression inside the parentheses is automatically coerced to a boolean value.
Values that are "falsy" are converted to false in a boolean context. These include false, 0, NaN, null, undefined, and the empty string ''. All other values are considered "truthy".

Boolean Operators:
JavaScript provides several operators for working with boolean values:
Logical AND (&&): Returns true if both operands are true, otherwise returns false.
Logical OR (||): Returns true if at least one of the operands is true, otherwise returns false.
Logical NOT (!): Returns the opposite boolean value of the operand.
These operators are commonly used in conditional statements and logical evaluations.

Boolean Functions and Methods:
JavaScript provides methods and functions that return boolean values or operate on boolean values:
Boolean(): Converts a value to a boolean. For example, Boolean(0) returns false.
isNaN(): Checks if a value is NaN (Not a Number). Returns true if the value is NaN, otherwise returns false.
typeof: Checks the data type of a value. For example, typeof x === 'boolean' checks if x is a boolean.

Example usage:
let x = 10;
let y = 5;

// Logical AND
console.log(x > 5 && y < 10); // Output: true

// Logical OR
console.log(x > 10 || y === 5); // Output: true

// Logical NOT
console.log(!(x === 5)); // Output: true

// Boolean Function
console.log(Boolean(0)); // Output: false

// isNaN function
console.log(isNaN("Hello")); // Output: true

// typeof operator
console.log(typeof true); // Output: "boolean"

## Javascript APIs:
JavaScript APIs (Application Programming Interfaces) provide a way for developers to interact with external systems, services, and functionality within the browser or on the server-side using JavaScript. These APIs allow developers to access various features and capabilities, such as manipulating the DOM (Document Object Model), making HTTP requests, accessing device hardware, and much more. Here are some commonly used 

1. DOM API (Document Object Model):
Allows manipulation of HTML and XML documents as structured trees of objects.
Provides methods and properties for accessing, creating, modifying, and deleting HTML elements and their attributes.
Example methods include getElementById(), querySelector(), addEventListener(), appendChild(), etc.

2. Web APIs:
These are APIs provided by web browsers to enable various functionalities.
Fetch API: Provides an interface for fetching resources (e.g., making HTTP requests).
Geolocation API: Allows retrieving the user's geographical location.
Storage APIs:
Web Storage API: Provides mechanisms for storing data in the browser, including localStorage and sessionStorage.
IndexedDB: A low-level API for client-side storage of significant amounts of structured data.
Canvas API: Allows dynamic rendering of 2D graphics, images, and shapes in the browser.
Web Audio API: Enables audio processing and synthesis in web applications.
Web Speech API: Allows integration of speech recognition and synthesis capabilities into web apps.

3. Third-Party APIs:
Many third-party services provide APIs that developers can use to integrate their services into web applications. For example:
Google Maps API: Provides mapping services and geolocation data.
Twitter API: Allows integration with Twitter's functionality, such as displaying tweets or posting tweets.
GitHub API: Allows programmatic access to GitHub repositories, issues, and other data.

4. Node.js APIs (for server-side JavaScript):
HTTP: Allows creating HTTP servers and making HTTP requests.
File System: Provides functionality for interacting with the file system.
Crypto: Offers cryptographic functionality, including encryption and decryption.
Events: Provides an event handling mechanism for asynchronous operations.
Process: Allows interacting with the current Node.js process.

5. Browser APIs:
APIs provided by the web browser environment itself, such as:
Window: Provides methods and properties for manipulating browser windows.
Console: Provides methods for logging messages to the browser console.
History: Allows manipulation of the browser's session history.

## Javascript Forms
In web development, forms are crucial for collecting user input and interacting with users. JavaScript plays a significant role in enhancing form functionality by adding interactivity, validation, and dynamic behavior. Below are some key aspects of working with forms in JavaScript:

Accessing Form Elements:
JavaScript provides several methods for accessing form elements:
getElementById(): Retrieves an element by its ID.
querySelector(): Allows selecting elements using CSS selectors.
getElementsByName(): Retrieves a collection of elements with a specific name attribute.
getElementsByTagName(): Retrieves a collection of elements with a specific tag name.

Form Submission:
JavaScript can handle form submission events to perform custom actions before or after submitting a form.
You can prevent the default form submission behavior using the preventDefault() method of the event object, allowing you to handle form submission using AJAX or perform client-side validation.

Form Validation:
JavaScript enables client-side form validation to ensure that user input meets certain criteria before submission.
Common validation techniques include checking for empty fields, validating email addresses, enforcing minimum/maximum lengths, and more.
You can use event listeners (e.g., addEventListener()) to listen for form submission events and validate form data accordingly.

Dynamic Form Manipulation:
JavaScript allows dynamic manipulation of form elements, such as adding or removing form fields based on user actions or application logic.
You can dynamically update form elements' properties, styles, and contents in response to user interactions.

Form Reset:
JavaScript provides a way to reset form fields to their initial values using the reset() method of the form element.

Working with Form Data:
You can retrieve form data using the FormData API or by accessing individual form elements' values.
With the FormData API, you can construct a set of key/value pairs representing form fields and their values, which can then be sent to the server using AJAX or other methods.

Event Handling:
JavaScript allows attaching event handlers to form elements to respond to various user interactions, such as clicking, typing, or submitting forms.
Common form-related events include submit, input, change, focus, and blur.
Example:
<form id="myForm">
  <input type="text" id="username" name="username" placeholder="Username">
  <input type="password" id="password" name="password" placeholder="Password">
  <button type="submit">Submit</button>
</form>

<script>
  const form = document.getElementById('myForm');

  form.addEventListener('submit', function(event) {
    event.preventDefault(); // Prevent default form submission

    // Perform form validation
    const username = document.getElementById('username').value;
    const password = document.getElementById('password').value;

    if (username === '' || password === '') {
      alert('Please fill in all fields');
      return;
    }

    // If validation passes, submit the form
    // Example: Send form data to the server using AJAX
    console.log('Form submitted:', { username, password });
  });
</script>

## Handlin Events

1. **String Operations**:
   - Strings can be created as primitives using string literals (`' '` or `" "`) or as objects using the `String()` constructor.
   - String primitives and objects can be used interchangeably in most situations.
   - Accessing individual characters in a string can be done using methods like `charAt()` or treating the string as an array-like object.
   - String comparison can be done using less-than and greater-than operators or the `localeCompare()` method for more complex comparisons.
   - JavaScript distinguishes between string primitives and `String` objects, with automatic conversion between them.
   - `eval()` treats string primitives as source code and `String` objects as regular objects.

2. **The onSubmit Event**:
   - `on-event` handlers are properties offered by DOM elements to manage their reactions to events like clicks, key presses, etc.
   - Handlers can be specified using HTML attributes or by setting corresponding properties from JavaScript.
   - The `addEventListener()` method is often preferred for attaching event handlers.
   - Event handlers are automatically called when events occur, with the option to manually trigger them.
   - The `this` keyword inside event handlers refers to the DOM element to which the handler is registered.
   - The return value of an event handler can determine whether the event is cancelled.

3. **Event Handlers**:
   - Event handlers can be specified as HTML attributes (`on...`) or properties in JavaScript.
   - Different HTML elements and objects support various event handlers for common events like clicks, key presses, media playback, etc.
   - Event handling can involve functions or objects registered via `addEventListener()` or set as properties.

4. **Multiparameter Function Coding**:
   - This part seems to be missing from the provided content.


## onkeyup:
This event is triggered when a key is released. It is commonly used to perform an action after the user releases a key. For example, you might use it to update a search field as the user types.
document.getElementById("myInput").onkeyup = function() {
  console.log("Key released!");
};
## onkeypress: 
This event is triggered when a key is pressed down. It is often used to prevent certain characters from being entered into an input field or to trigger actions as soon as a key is pressed down.
document.getElementById("myInput").onkeypress = function() {
  console.log("Key pressed!");
};

## The onload, onunload, and onresize events are related to the loading, unloading, and resizing of the window or document.

onload: This event is triggered when a page or an image is finished loading. It's commonly used to perform actions that need to happen after the entire page has loaded, such as initializing variables or setting up event listeners.
window.onload = function() {
  console.log("Page loaded!");
};

onunload: This event is triggered immediately before a page is unloaded, such as when the user navigates away from the page or closes the browser window. It's less commonly used, but can be helpful for performing cleanup tasks or confirming with the user before they leave the page.
window.onunload = function() {
  console.log("Page unloaded!");
};

onresize: This event is triggered when the size of the browser window or an element is changed. It's often used to adjust the layout of a webpage dynamically based on the window size.
window.onresize = function() {
  console.log("Window resized!");
};

## SlideShow
A slideshow is a popular feature in web design and presentation software that allows for the sequential display of a series of images or other content. In web development, slideshows are commonly implemented using HTML, CSS, and JavaScript. Here's a basic overview of how you can create a simple slideshow using these technologies:
HTML Structure: You'll need a container element to hold your slideshow images. Each image will typically be placed within a slide element.
for example: <div class="slideshow">
  <img src="image1.jpg" class="slide">
  <img src="image2.jpg" class="slide">
  <img src="image3.jpg" class="slide">
</div>
You can use CSS to style your slideshow, positioning the slides and defining their appearance.
eg .slideshow {
  position: relative;
  max-width: 100%;
  overflow: hidden;
}

.slide {
  display: none; /* Hide all slides by default */
  width: 100%; /* Ensure slides fill the container horizontally */
  height: auto; /* Maintain aspect ratio */
}
JavaScript Functionality: You'll use JavaScript to control the slideshow behavior, such as transitioning between slides automatically or in response to user interaction.
e.g  let slides = document.querySelectorAll('.slide');
     let currentSlide = 0;

function showSlide(n) {
  slides[currentSlide].style.display = 'none';
  currentSlide = (n + slides.length) % slides.length;
  slides[currentSlide].style.display = 'block';
}

function nextSlide() {
  showSlide(currentSlide + 1);
}

function prevSlide() {
  showSlide(currentSlide - 1);
}

// Automatically advance slides every 5 seconds
setInterval(nextSlide, 5000);

// Optionally, you can add event listeners for user interaction
// For example, to allow users to navigate using buttons:
document.getElementById('prevBtn').addEventListener('click', prevSlide);
document.getElementById('nextBtn').addEventListener('click', nextSlide);
Optional Controls: You can add buttons or other elements to allow users to navigate between slides manually. For example, you can add "Previous" and "Next" buttons.

<button id="prevBtn">Previous</button>
<button id="nextBtn">Next</button>

## Javascript For Loop
Loops in JavaScript are essential for executing a block of code repeatedly, typically when working with arrays or iterating over collections of data.

For Loop: Executes a block of code a specified number of times.
for (initialization; condition; iteration) {
  // code block to be executed
}
Example:
for (var i = 0; i < 5; i++) {
  console.log("The number is " + i);
}

For/In Loop: Loops through the properties of an object.
for (variable in object) {
  // code block to be executed
}

For/Of Loop: Loops through the values of an iterable object like arrays, strings, etc.

for (variable of iterable) {
  // code block to be executed
}

While Loop: Executes a block of code while a specified condition is true.
while (condition) {
  // code block to be executed
}

Do/While Loop: Similar to a while loop, but the condition is evaluated after executing the block of code.

do {
  // code block to be executed
} while (condition);

In these loops:
Statement 1 is optional and used for initializing variables.
Statement 2 defines the condition for executing the code block.
Statement 3 is optional and typically used for updating the loop control variable.

## Search Engines
Search engines function as answer machines, sorting through vast amounts of content via crawling, indexing, and ranking processes. Organic search results, which are earned through effective SEO rather than paid for, are crucial for website visibility.
Today's search engine results pages (SERPs) feature a mix of advertising and dynamic organic formats, known as SERP features. These include featured snippets, People Also Ask boxes, and local packs. While search engines prioritize solving search queries, they also aim to generate revenue from advertising.
SEO is essential because organic search results cover more digital real estate, appear more credible to users, and receive more clicks compared to paid advertisements. It offers significant traffic opportunities and can provide long-term benefits without continuous funding like advertising.
In essence, SEO helps ensure that search engines understand and rank your content appropriately, improving your visibility and driving organic traffic to your website over time.


