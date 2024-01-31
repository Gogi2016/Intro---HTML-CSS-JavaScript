# Intro---HTML & CSS

## Unit 1: Introduction
HTML which is (Hyper Text Markup Language) is lick a an internet backbone used to create Apps and websites. It helps computers understand what human want to say and do. The web uses 3 main languages HTML for content, CSS for styles and Javascript tha adds interactions. If there are issues in THML or CSS, browsers try its best to keep things working, making them their problrm solving meaning if there is a mistake, browser tries its best to make it function.

## Unit 2 Text-Formatting
HTML uses tages which are enclosed in less or greater than symbols to mark different elements. They are opening tags and closing tags <p> for opening and </p> for closing. These tags are both required, you can not use openning tag without closing it, vice vesa.

Tags that are as follows
Paragraph tag <p> <p/>,  When you write a paragraph you open the tag and when you have finished you close it. The paragraphs can be separated  whith the same tags.
Headline tags <h> </h>, Headlines come in six different types: h1, h2, h3, h4, h5, and h6. These tags are used in headlines, and in sub headlines. The element which is h1 is the largest, and h6 is the smallest.
Bold tags <strong></strong> and <b></b>, these tags <strong> make the text to be bold which shows importance. The <b> is the normal one and does not have any meaning but just simply allows developer to make text bold.
Italic <i></i> and emphasized <em></em>, <em> emphasises a taext that is typically displayes as italic. These 2 tags <em> amd <i> may be similar in appearance but have different meaning.
List tags <li></li> These tags are used to define a list that is ordered (<ol>) or unordered (<ul>

HTML Quotes
<cite>, <q> and <blockqoute>, These quotes are usually used in articles most of the times. <cite> is use to reference a source's qoute. 
<q> is commonly used to determine inline quotes and can be indicated by quotation marks in the browser.
<blockqoute> indicates that the text is no longer qouted from another source.

Date Element
<time> this element help us deals with both date and time in this tag it will show the users what you actually wrote between these tags. It allows us to write dates in a ways tha can be understood by people. There is also an attribute used which is datetime, which has a specific format like 2024-01-30 that tells the computer the exact date. e.g you can write January 30th between the <time> tags but we actually use (datetime) attricute like this <time datetime="2024-01-30">January 30, 2024</time >, This si what understoond by the computer.

HTML superscripts, subscripts and small text
superscript tag <sup></sup> these are used for text that should be displayed above the normal text line, often for things like maths exponents
subscript tags <sub></sub> are used for text that should be displayed below the normal text line, commonly used in chemical formular or maths notations.
small text tag <small></small> these tags are used to decrease the size of the text.

## Unit 3 HTML capabilities
Opening Developer Tools, Right click on a webpage & choose inspecter element or go to tools then web developer and select inspector, this will open up a set of tools
Inspector section, in the inspector you will see 3 sectionswhich are HTML on the left, CSS on the middle and more other options on the right the focus on HTML section on the left.
If you encounter issues like unordered list showing an unexpexted empty item, then you can use develper tools to inverstigste, the browser will try to fix the HTML mistake by adding an extra item

HTML Attributes
Class Attribute, is like giving name to a group of element  on a webpage. it is used to style multiple elements once using CSS. i.e if you want all youe headings to look the same you just give them the same class.
ID Attribute, this is similar to Class ID but can only be used once in a page. It is useful for creating links  that jump to a specific section on the page.

ARIA Roles
these are extra attributes added to HTML elements to help browser understand thier  meaning, and that ensure websites are accessible to everyone including those with dissabilities. Accessibility require website to be accesible to everyone.

Formatting HTML
White space in HTML, HTML ignores extra spaces, tabs or linr breaks, however elements like <pre>, <code> and <extraarea> or when modified with CSS may consider extra spaced and indetations. If tou modify whitespace handling with CSS, it can affect how spaces and indetantions are displayed. In most cases browser do not care about more than a single space. 
Comments are added usibg <!--comment here-->, This is helpful for quickly identifying when con code is commented out, preventing confusion when it does not function well.
Using Uppercases for tags, like <LI></LI> does not affect the browser's rendering. Its a matter of conveting and readability.
To insert video we use <video src= "file.mov"></video>, for inserting an image <img src= "file.jpg"></img>, make sure you choose the correl url of that image or video.

Linking
<a href="url">link text</a> This will display the word written in "link text" which is the link that will navigate to another page.

The link's destination is specified in the href attribute.

Navigation
The <nav> tag defines a set of navigation links
 When you make pages, each page i.e home, About, prices and contact. must be inside the <nav>, <ul> and <liL i.e  <nav> <ul> <li><a href="#">Home</a></li></ul> </nav>

HTML URL Pathways
There is a folder with files, like images and screens. Its file has its own location in that folder. Web addresses (URL) helps us finds the link of these files.  For example If the folder has a file name Images, then you are looking for a certain image in the file. You can not just type the URL of an image, you start looking for a file from the folder then then the image URL. Which means the image you are looking for might use the URL (/images/myself.jpg) or (../images/myself.jpg)


