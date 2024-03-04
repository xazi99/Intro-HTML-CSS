# Intro-HTML-CSS    
#UNIT1
WHAT IS HTML?
HyperText mark-up language is a standard mark-up language for documents disigned to be displayed on a web brower.

UNIT2
#Taxt formatting and Syntax
HTML is a standard markup language usedto stracture web pages.It uses tags meaning it uses less than and greather than(><). We have two types of tags which are Opening tags <h> and closing tags </h>. In most cases the tags work together to define elements.Most important purpose for HTML is that it gives meaning of the content and help cumputers understand it.

#HTML ELEMENTS
#NESTED HTLM ELEMENTS & HTML PARAGRAPHS
We are a DOM tree stands for Document Object Model.
On HTML paragraphs we use tags to separate the paragraphs,when starting a paragraph we use an opening tag<p> then we end with a closng tag</p>.

#HTML HEADLINES
They help people to understand the page structure, also they can be the main content. They also act as a title that attract readers for more information. There are six elemets used for marking headlines(h1,h2,h3,h4,h5,h6).

The first element(h1) is the largest one while h6 is the small one and is not important, the rest of the elements fall in between in the orderof importance.

#HTML BOLD AND ITALICS
There are two elements for Bold and two elements for etalic. When we italicize a word we want it to have a strong meaning.
We use (<i>) element to italics and (<em>) element to emphasize, the are two elements in HTML that make a word or phrase Bold or Emphasize. We use <strong> element to show that something is important and serious and we use (<b>) element to make the phrase bold.

#HTML LISTS
We have three tyoes of lists, the are Ordered lists, un-ordered lists and definition lists. Unorderd lits are used everyday, they are enclosed with <li> element that represent that they are a list item and they are wrapoed with (<ul>) element that shows that this is an unoedred list.
On orderd list we use (<ol>) to wrap the entire list which shows that the list is ordered.
Definition list it is used to create list that resembles a key-value. They use specific elements, a term is enclosed in a <dt> tag stands for definition term. The description term is enclosed in a (<dd>) tag which stands for definition description. The entire list s wrapped up by a (<dl>) tag which stand for a definiion list.

#HTML QOUTES
On qoutes we enclose the paragraph with a (<p>) tag and we then make the qoute differ or other text with <blockqoute> element that will wrap the entired thing.
We have (<cite>) and <blockqoute> elements that notify other computers about a additinal information.
On HTML we use <q> element which stands for qoute and the browser automatically provide the right qoute mark.The are also block-level elements.

DATE ELEMENT
HTML uses this element to to set date and time in a way that computers will understand.
Syntax <time datetime="2024-01-12">January 12,2024</time>. Date and time have their specific format that machines can understand and as programmer we need to use them.

#HTML DATE AND TIME INPUTS
HTML use this single element <time>, this element is used to mark anything that specifies time,date,day,and duration. The is also a closing tag </time>.
In between the tags we use a readable human format.

#HTML CODE,PRE AND BR
HTML signs "&lt" which represent a less than sign and "&gt" that represent a greater than sign.
The br element is added at the end of each line, it is a simple tag without opening and closing tags. Pre and Code are combined in most cases to display block codes.

#HTML Superscripts,Subscripts and Small text
They are used to mark up certain bits of a content that you want it to have a different meaning than the rest of the content.
Subscripts are charactors that are normally set below the baseline for a text.Superscript are charactors that are set above the baseline of a text.

#UNIT 3
HTML CAPABILITIES
Troubleshooting and Debugging HTLM 
When writing a code and accidentally made a mistake the Dom will make the results to have extra because it believes that the should be an extra tag.

HTML ATTRIBUTES
The datetime attribute is used only to the time element,other attributes work with multiple elements but not all of them.Syntax for class attribute <p class="intro"> then the end tag </p>.
Syntax for Id attribute <p class="intro"id="article-intro"> then the end tag </p>.

GLOBAL ATTRIBUTES
Mostly used attribute is Class attribute and it allow to assign reusable name to any element, which can be styled using CSS.
ID attribute it is similar to the class attribute but we can only use unique and can be used for CSS targeting that are more specific and sometimes can cause issues.
Content editable attribute allow visitors to adit the content on the web page.
Lang attribute allow to specify the language of a content using short language code.
Dir attribute shows the direction on which the text flows using Left-to-right(LTR) script and Right-to-left(RTL) script.
Lang and dir are considered are global attributes and can be used to HTML attributes.

ARIA ROLES
They are extra attributes that can be added on HTML elements to make them more meaningful and and help browsers to understand what they represent.They came about when the web began and replace vative applications
It is a powerful used tool that greately enhances web accessibiity.

FORMATTING HTML
Comments are inserted by typing "<!--" at the start and type this "-->" at the end. The length of an element give the clue of how long it has been on existence. Some older elements have no closing tags while the new ones have both the opening and a closing tag.

UNUSUAL CHARACTERS
The symbol <,>,& are important characters of HTML. If we write them with spaces inbetween they become the real content. Non-breaking space has a unique role in Html,spaces in the text allow lines to break and words remain intact.
Non-breaking space also tell the browser not to break the lines between two words. It also create multiple spaces between te words.


#UNIT 4
HTML NAVIGATION AND LINKING
HTML LINKS
When creating a link we use an A element which stand for anchor,we add a href attribute with the URL enclosed on qoutes.The URL will take us to the link and the href stands for HyperText Reference.
Between the tags we can put imagies or textto make them clickable.

HTNL URL PATHWAYS
URL are options for formatting links,to for a URL you need to graps how files are organized.Forming a relative URL omit the domain name but include the initial slash in the beginning.
/image/logo.gif it creates URL that is relative from the root level,meaning the browser will look for the file from the root of the website.
../image/logo.gif it creates the URL that is relative from the location of thr filr where the URL is written. This means that you have to start from the location then move up.

NAVIGATION
Each link is wrapped in an element with the correct URL and then enclosed with "li" element to make a list for links. You have to wrap the entire link with "ul" element to show that it is an unordered list.
encompass the entire link with "nav" to show that the link is a navigation site, you have to apply the CSS styling because without the CSS styling it appears as a plain list.

#UNIT 5
GRAPHICS AND IMAGES
Element IMG id used to add images on the web page,we include four attributes for every image.
>Source attribute(SRC) tells the browser which image to load.
>Alternate attribute(alt) provides text descriptin of an image.
>Width and Height attribute they describe the size of an image, it is important for an image to have all four of the attributes.
IMAGE FORMATS
The are main commonly used image formats:GIF,SVG,JPG,NPG
>GIF-is used for compressing illustrations that have the large of the same color,they have transparent areas.
>SVG-they are perfect for logos,icons and other illustrations.They can be scaled to any sixe without losing any quality,and the size remains the same. It is the programming language for graphics
>JPG-they are popular choice for compressing photographs,they can also be compressed by reducing the color information,finding the right balance between size and quality.
>NPG-it is a new format that works well with transparency in a phography,it can also outperform the GIF and JPG on compressing certain images.

RESPONSIVE IMAGES
CSS can ofter to display the image in different sizes to accomodate small and large screens. HTML allows to diliver differents image files to different screen size.
To support different screens you need to create multple images with diffrent resolutions,then the device choose image to use based on sceen density,netwok connection.

#UNIT 6
Working with Media
Working with Audios
Audio element as both openning and closing tags,which makes it more morden and gives it power and flexibility.
Video Element
it has both tags(opening & closing), you used the source attribute(src) to specify the video file. When you add the control attribute the browser creates a video player.
Captions and Subtitle
We use track element to link the text file to add caption on a video,the track element adds functionality to the video player.
Captions and subtitle are not only powerful but they are required by law.By including then your content can be more accessible.
Embedding Media via Inframes
Embedding is when moving your content from one site and placing it in the middle of another site.

#UNIT 7
HTML CONTENT IDENTIFICATION
HTML Language Support
We use the lang attribute to specify the language of a web page, the lang attribute has many options it does not only indicate language but has other qualities like writing system. It does also specify the content's direction.
Lang attribute does not only used to specify the language it is also used for writing systems. Specify the direction of a content. Use the dv element to specify the direction of the language and it can be applied on any element.
Set the charset for the project.
HTML GENERIC ELEMENTS DIV & SPAN
Div is a block-level element while span is an inline element,they both do nothing until CSS and javascript ia applied to them.

#UNIT 8
HTML INTEGRATION
HTML PAGE
HTML,elements,attributes,roles and tools are used to mark up the content on websites and web apps.
HTML HEAD
Inside the head you put important information that the browser needs to know about the website,use the meta element and ensure that they are placed inside the head because they provide metadata about the web page.
Meta elements are commly used to inform the browser that the layout has been adjusted to fit small screens.
The script element is used on HTML documents head.
CONTENT STRUCTURING
The main element is used once per webpage and tells the browser where the main content is located.
The header and footer elements mark the header and footer areas on the page.
The footer signifies that there are extra things to convey, regardless of its position on the page.
An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header.
The section element is used to mark sections of content.
The aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow.

#UNIT 9
WORKING WITH FORMS AND INTERACTIVE ELEMENTS
Form fields are used for various tasks like logging into websites, making purchases, conducting searches, and adding content. 
It is important to use semantic form elements in HTML instead of divs and spans because it allows us to leverage the built-in power of the browser.
MAKING A FORM
To create a form, we start with the form element, which informs the browser about the presence of a form using opening and closing tags.Fields name can be turned on labels using the label element.
After you use the input element to provide the users to input thei names and emails.Input element does not have the closing tag.
Use the button element to create the button for users to submit information.

#UNIT 10
ORGANIZNG TABULAR INFORMATION ON HTML
HTML TABLES
We use html tables when your information is a tabbular form,do not misuse html tables.The table conveys a relationship between the data cells and the header cells between one column or row and the next. 
Usu CSS to rearrange how the table shoud be displayed, change the layout for different sized screen. It doesn't have to look like a table, but if the information is in tabular form use the html tables.
BUILDING HTML TABLES
When creating html table you use different html elements suc as: table,TR,TD,TH.
<table></table> wraps the whole table.
<tr></tr> table row-wraps the set of elements defining them as they belong to the same row.
<th></th> table header-defining the header for the column.
<td></td> table data-marks the actual bits of data.


#INTRODUCTION TO CSS
#UNIT 1
#HTML & CSS
CSS is a style sheet that holds the style of the webpage, it also add the visual appeal of the webpage.
CSS has to parts: selector and declaration block.The selector specifies the pattern and if the pattern matches the style in the declaraction block it is applied to the corresponding HTML element.
CSS COMPONENTS
CSS declaraction stype consists of two parts which are value and property.
Writing first Comment & Selector
In CSS, we use a dot (.) before the class name to differentiate it from HTML element selectors.
Omn css we have selectors which are element,class,group and descendent selectors. To apply style on descendent selector you use the OL& LI elements without the tags,the space between the elements shows the descendent relationship.
CSS selectors that involve multiple items you read them from right-to-left,even thogh you write them from left-to-right.

#UNIT 2
SELECTORS
Is a pattern used to select and style html elements on a web page. The target specific elements based on their types,atribute, class or id allowing the user to apply style on them.
CLASS SELECTOR
When writing a class selector you prefix the class name with a dot. 
E.g   .navbar {
        color:red;
        }
GROUPING SELECTORS
You group selectors on CSS by separating them with commans, this allow the user to apply the same types to multiple selectors.
e.g
h1, h2, p {
color:blue,
}
DESCENDENT SELECTORS
Targets an element that is descendent of another specified element.

#UNIT 3
IDENTIFY A COLOR SCHEME
Formatting colors
Hex values are typically six-digits long and consist of numbers zero to nine and letters A to F. The first two digits represent red, the next two represent green, and the final two represent blue. These digits correspond to numbers ranging from zero to 255. 
RGB format, where colors are written out using Base 10 numbers to specify the red, green, and blue channels. This format can also be represented as an eight-digit hex number or RGBA. In both cases, the last number corresponds to Alpha, which relates to the opacity and transparency of the color. It determines how well we can see through the color. 
HSL or HSLA formats may also be used occasionally, particularly within platforms like Squarespace.
Background and text color in CSS
You can choose a color for the text and another for the background, whether it is a specific element or the entire page.
Image Formats
GIF: Had limited colors but could include transparency and animation. 
PNG: Had more colors and transparency but no animation. GIF and PNG were suitable for illustrations such as logos or cartoons. 
JPEG: Stands for Joint Photographic Experts Group, was optimized for photographs and supported millions of colors but lacked transparency and animation.
It is important to choose the right color when workig with images.
Recently, a new image format called WebP has emerged. WebP can be used for any image type and offers high compression for smaller file sizes, resulting in faster website loading times. It's expected that WebP will grow in popularity due to its versatility and efficiency in loading both photos and illustrations quickly with small file sizes.

#UNIT 4
UNDERSTANDING TYPE IN CSS

#MODULE 3
#JAVA SCRIPT
#INTRODUCTION
JavaScript is a programming language used to make web pages interactive. It is what gives a page life - the interactive elements and animations that engage the user.JavaScript was purposely designed to integrate into html.














