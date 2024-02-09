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






