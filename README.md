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

## Unit 5 Working with Graphics and Images
There are four attributes that need to be included for every image:
First, we have the source attribute (SRC), which tells the browser which image file to load. 
Then we have the alt attribute (ALT), which provides a text description of the image. 
Lastly, we have the width and height attributes, which determine the size of the image.
it can be coded using the ff code <img src="myself.jpg" alt="My self">
Use the figcaption element to wrap the text and designate it as a caption. Then, put the image and the caption together in a figure element. <figure><img src="vuyo.png" alt="Myself" width="250" Height="200"><figcaption>This is my self</figcaption></figure>

SVGs are ideal for logos, icons, and illustrations because they are vector files, containing drawing instructions instead of pixels. This allows them to be scaled to any size without losing quality, and they have small file sizes. SVG is a graphics programming language, and you can learn more about it through dedicated courses. These files can be exported from design programs like Illustrator or Sketch and used like other web file formats. If you want to create a compact image that can display in large sizes without pixelation,
GIFs work well for illustrations with big areas of the same color, but not so much for photos. They only support 256 colors, so photos can look pixelated unless you want a retro look. GIFs can have transparent parts, but the edges might look jagged between transparent and solid areas.
JPGs are good for compressing photos, and many cameras save pictures in this format. However, when using them on websites, it's crucial to resize and compress them properly to avoid slowing down the loading speed. Don't use huge, partially compressed JPGs. You can make JPGs smaller by adjusting color info, finding the right quality-size balance. You can do this yourself or use online tools for help.
PNG is a newer image format good for transparent photos and can sometimes compress images better than GIF or JPG. When compressing files, try different options for the smallest size. New image formats may come in the future for better compression. When dealing with images, think about size, format, and compression for faster downloads. Surprisingly, the HTML code stays the same no matter the image format you pick.

## Unitt 7 Working With Media
The audio element is different from the image element because it has both an opening and a closing tag, <audio controls src="audio.mp3"></audio>
Instead of relying on pre-built audio player controls, there is an option to create your own using JavaScript and the HTML media element API, <audio controls><source src="http/:example.com" type="audio/org:code">
In Videos, Just like the audio element, the video element has an opening and closing tag. To display a video, use the source attribute to specify the video file, <video controls><source src="http/:example.com" type="video/mp4"></video>

Use the track element and link it to a text file to add captions to the video. This element adds functionality to the video player, allowing viewers to toggle captions on and off or switch between different subtitle options. <video controls><source src="http/:example.com" type="video/mp4"><track src="https/:,..." kind="caption" label="english" srclang="en" default>

HTML Content Identification
 In HTML, there are tools to indicate the language of your content. By setting things up correctly, search engines will understand which language websites are in. Spell checkers will provide the appropriate dictionaries, and when a browser reads the content aloud, it will pronounce the words correctly. The lang attribute is used to specify the language of a webpage.<html lang="eng">

Meta charset="UTF-8" Imagine the text on the internet is like a big playground with lots of different characters, letters, and symbols. Now, to make sure everyone understands each other, we use something called Unicode, which is like a set of rules for all the characters to play nicely together.
UTF-8 is like a special rulebook within Unicode that helps handle a huge variety of characters, from regular letters to cool emojis.
Now, when you visit a website, your computer needs to know which rulebook (UTF-8 in this case) the website is using. If it doesn't know, things might get a bit mixed up, and the text could look strange or unreadable.
To avoid this confusion, websites use a little code called HTML, and within HTML, there's a tag (like a label) called "meta charset." By adding this tag and setting it to "UTF-8," it's like telling your computer, "Hey, we're using the UTF-8 rulebook here!" This tag is placed in the head section of each webpage, sort of like the instructions at the beginning of a book.
So, in simple terms, adding a meta charset tag with UTF-8 in HTML is like making sure everyone on the internet playground is reading from the same rulebook, preventing any confusion and making the text look right for everyone. 

