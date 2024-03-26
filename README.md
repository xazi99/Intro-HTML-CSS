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
Unattractive and poorly designed web pages bother most people and they agree that there is something undeniably wrong with the way these pages look. Serif fonts have small lines at the ends of the letters called serifs. In the past, serif fonts were used for printed materials with long text blocks.
Sans serif fonts do not have serifs and have a more modern appearance.


UNIT 5
CSS PROPERTIES AND CONCEPTS
The concept of inheritance and specificity in CSS is quite complex.


#MODULE 3
#JAVA SCRIPt
#WEEK 1 DAY 1
#INTRODUCTION
VARIABLES
JavaScript is a programming language used to make web pages interactive. It is what gives a page life - the interactive elements and animations that engage the user.JavaScript was purposely designed to integrate into html.
Variables are containers for storing data ( var, let, const).
All JavaScript variables must be identified with unique names, these unique names are called identifiers.
JavaScript identifiers are case-sensitive.
OPERATORS
Javascript operators are used to perform different types of mathematical and logical computations. The Assignment Operator (=) assigns a value to a variable.
Different types of JavaScript operators:
Arithmetic Operators
Assignment Operators
Comparison Operators
String Operators
Logical Operators
Bitwise Operators
Ternary Operators
Type Operators

#DAY 2
STRINGS AND ARRAYS
String is a data type represssenting sequence of charactors which constists of numbers, letter, symbols, words or sentences. Strings are premitive data types meaning they cannot be changed,they can also be transformrd and process in various ways such as converting them to uppercases or lowercases, comparing them to determine if they equal etc.
Strings are written with quotes.
An array is a special variable, which can hold more than one value. It is used to store multiple values and elements to one varioubles.

#DAY 3
FUNCTIONS
A JavaScript function is a block of code designed to perform a particular task.It is executed when "something" invokes it (calls it).
JavaScript function is defined with the function keyword, followed by a name, followed by parentheses (). Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)
The code to be executed, by the function, is placed inside curly brackets: {}

Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:
When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)

Function Return
When JavaScript reaches a return statement, the function will stop executing.
If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
Functions often compute a return value. The return value is "returned" back to the "caller".

#DAY 4
BOOLEANS
JavaScript Boolean represents one of two values: true or false.
JavaScript booleans are primitive values created from literals.
#DAY 5
Sprint


#WEEK 2
#DAY 1 
WEB DESIGN
INTRO TO HTML,CSS & JS
The Document Object Model and JavaScript Syntax
The Document Object Model is an Application Programming Interface (API) for HTML and XML documents. It does two things for web developers: 
Provides a structural representation of the document
Defines the way that that structure is to be accessed from script
This allows you to get at the web page as a structured group of nodes. Essentially, it connects web pages to scripts or programming languages.
String Conversion
String conversion happens when we need the string form of a value. 
Numeric Conversion  
Numeric conversion happens in mathematical functions and expressions automatically.  
Boolean Conversion  
Boolean conversion is the simplest one.  
It happens in logical operations (later we’ll meet condition tests and other similar things) but can also be performed explicitly with a call to Boolean(value).  
The conversion rule:
Values that are intuitively “empty”, like 0, an empty string, null, undefined, and NaN, become false.  
Other values become true.

The Document Object Model and JavaScript Syntax
The Document Object Model is an Application Programming Interface (API) for HTML and XML documents. It does two things for web developers: 
Provides a structural representation of the document
Defines the way that that structure is to be accessed from script
This allows you to get at the web page as a structured group of nodes. Essentially, it connects web pages to scripts or programming languages.
The JavaScript syntax has to do with objects. To access an object, property, or method, its reference must include every object that contains it, separated by a dot. This is called the "dot syntax".

Object 
JavaScript object is any scriptable HTML element, that is, any HTML element within a document that may be accessed through the JavaScript language. Although the browser window is not an HTML element, it too is a scriptable object.
JavaScript objects:
window
document
form
image

Property
Objects have properties, which you can think of as characteristics of an object. A JavaScript property has a similar relationship to the object it belongs to that an HTML tag attribute has to the tag that contains it. For example, the JavaScript "value" property is to a text field object as the HTML "width" attribute is to a table tag.
Method
Methods are actions that can be applied directly to objects. Within a web page, methods cause a boring old HTML document to react to the end user. This results in a meaningful experience for the end user which would otherwise be completely one-sided.
Method Parameters
Syntactically speaking, methods are signified by parenthesis immediately following their name, e.g. "alert()".
These parenthesis sometimes hold values called parameters, which are required by some methods. 

#DAY 2
JAVASCRIPT API's
Some Javascript API's
document.getElementById(id)
document.getElementsByTagName(name)
document.createElement(name)
parentNode.appendChild(node)
element.innerHTML
element.style.left
element.setAttribute
element.getAttribute
element.addEventListener

CALLING ONE FUNCTION FROM ANOTHER
Code inside a function behaves just like code anywhere else. This means you can call one function from inside another function. This allows you to "nest" functions so that you can create separate functions, which each perform a specific task, and then run them together as a complete process, one right after the other.

Creating objects with user-defined functions
JavaScript is based on objects: the window is an object, links are objects, forms are objects, even Netscape itself (or other browser) is an object. Using objects can help make programming easier and more streamlined.

Making a new object entails two steps:
Define the object in a user-defined function.
Use the new keyword to create (or instantiate) the object with a call to the object function.
Defining new properties to already-made objects
After an object has been created you can assign a value to it. But instead of just assigning a value to the object itself, you should define a new property for the object, and assign a value to the property. To create a new property and assign a value to it, simply write a variable expression like this:
        myobject is the name of the user-defined object.
        property is the name of the property you want to create.
        value is the value you want to assign.
Defining properties when you create the object
Another method of defining properties for objects is to include the property names in the object function. You can use this technique to simultaneously create a new object and define the property values. All it takes is a few more lines of code in the object function.

TYPES OF OPERATORS
Assignment operators
Comparison operators
Arithmetic operators
Bitwise operators
Logical operators
String operators
Conditional (ternary) operator
Comma operator
Unary operators
Relational operators
ssignment Operators
Return value and chaining

Assignment Operators
Like most expressions, assignments like x = y have a return value. It can be retrieved by e.g. assigning the expression or logging it: 
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x. 

Compound assignment operators
There are also compound assignment operators that are shorthand for the operations listed in the following table: 
Note that the return values are always based on the operands’ values before the operation.
When chaining these expressions, each assignment is evaluated right-to-left.

Destructuring
For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals. 
Comparison Operators 
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behaviour generally results in comparing the operands numerically.
Arithmetic operators
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity). 
Bitwise Operators
A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.

THE DOCUMENT OBJECT MODEL
EVENT BUBBLING
Bubbling is what the event itself does. 
An Event Listener would be attached to each element). Then, it bubbles up to each of it’s parent elements until it reaches the document. Any listeners on any of those parent elements would get triggered as it bubbles up. Causing all the events to occur on the page possibly slowing down your application. 
Event Delegation
Event delegation is a technique for listening to event where you delegate a parent element as the listener for all the events that happen inside it. 

#DAY 3 
JAVASCRIPT FORMS
Forms require PHP to send or receive messages. 
Accessing Object Methods 
You can access an object method using a dot notation. You can access a method by calling an objectName and a key for that method along with (). And you can access property only by calling an objectName and a key. 
Adding a Method to a JavaScript Object 
You can also add a method in an object.

JAVASCRIPT SWITCH STATEMENT
Switch statement is used to perform different actions based on different condition. 
Switching Details: 
If multiple cases matches a case value, the first case is selected. 
If no matching cases are found, the program continues to the default label. 
If no default label is found, the program continues to the statement(s) after the switch. 
Strict Comparison: 
Switch cases use strict comparison (===). 
The values must be of the same type to match. 
A strict comparison can only be true if the operands are of the same type. 



#WEEK 3
#DAY 1
#HANDLING EVENTS
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that clicks to is called an event. 
STRING OPERATIONS
Strings can be created as primitives, from string literals, or as objects, using the String() constructor. String primitives and string objects can be used interchangeably.
String literals can be specified using single or double quotes, which are treated identically, or using the backtick character. 
There are two ways to access individual charactors in a string:
 The first is the charAt() method.
 The other way (introduced in ECMAScript 5) is to treat the string as an array-like object, where individual characters correspond to a numerical index. 
String primitives and String objects also give different results when using eval(). Primitives passed to eval are treated as source code; String objects are treated as all other objects are, by returning the object.
The Onclick Event is the most frequently used event types which occur when a user clicks the left button of his mouse. You can put your validation, warning, etc., against this event type. 
An OnSubmit event is an event that occurs when you try to submit a form.

ON EVENT HANDLER
The on-event handlers are a group of properties offered by DOM elements to help manage how that element reacts to events. 
Elements can be interactive (e.g. links, buttons, images, forms) or non-interactive (e.g. the base document).
Events are actions like being clicked, detecting pressed keys, getting focus, etc.
The on-event handler is usually named according to the event it is designed to react to, such as onclick, onkeypress, onfocus, etc.

You can specify an on<...> event handler for a particular event (such as click) for a given object in different ways:
Using an HTML attribute named on{eventtype} on an element, 
for example:
<button onclick="return handleClick(event);">,
Or by setting the corresponding property from JavaScript,
for example:
document.getElementById("mybutton").onclick = function(event) { ... }.
Each object can have only one on-event handler for a given event (though that handler could call multiple sub-handlers).
Also note that on-event handlers are called automatically, not at the programmer's will (although you can do so, such as with mybutton.onclick(myevent);) since they serve more as placeholders to which a real handler function can be assigned.

Event handler’s parameters, this binding, and the return value
When the event handler is specified as an HTML attribute, the specified code is wrapped into a function with the following parameters:
event - for all event handlers, except onerror.
event, source, lineno, colno, and error for the onerror event handler. 
The event parameter actually contains the error message as a string.

The term event handler may be used to refer to:
any function or object registered to be notified of events,
or, more specifically, to the mechanism of registering event listeners via on... 
attributes in HTML or properties in web APIs, such as <button onclick="alert(this)"> or window.onload = function() { /* ... */ }.

When discussing the various methods of listening to events,
event listener refers to a function or object registered via EventTarget.addEventListener(), 
whereas event handler refers to a function registered via on... attributes or properties
The EventTarget method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target.

#DAY 2 
#DYNAMIC HTML
CSS and JavaScript can be combined with HTML to create dynamic web pages, which is called dynamic HTML. 
Changes to the features of a website can be driven by events.
These changes can be from simple text font, colour, and style changes, to dynamically changing the content of the page and moving objects around the page.

HTML objects can be changed in two ways:
Changing the class of the object - thereby changing the style of the object
Using the style property of the object to change the style.

Different ways to design a function
An object is referenced directly in the JavaScript function using the id value. This function can then be used to change the style of only that particular object.
An object id being passed as an argument to the JavaScript function, so that the style of any object may be changed.
An object may be accessed by using the event to determine the object in which the event occurred

DATE OBJECT
The Date object is a built-in object in JavaScript that stores the date and time. It provides a number of built-in methods for formatting and managing that data.  
Epoch time, also referred to as zero time, is represented by the date string 01 January.
Epoch time was chosen as a standard for computers to measure time by in earlier days of programming, and it is the method that JavaScript uses. It is important to understand the concept of both the timestamp and the date string, as both may be used depending on the settings and purpose of an application.  

Retrieving the Date with get  
Once we have a date, we can access all the components of the date with various built-in methods. Retrieving the Date with get  
Once we have a date, we can access all the components of the date with various built-in methods.
The methods will return each part of the date relative to the local timezone. Each of these methods starts with get, and will return the relative number. Below is a detailed table of the get methods of the Date object.
Modifying the Date with set  
For all the get methods that we learned about above, there is a corresponding set method.
Where get is used to retrieve a specific component from a date, set is used to modify components of a date

Date Methods with UTC  
The get methods discussed above retrieve the date components based on the user’s local timezone settings.
For increased control over the dates and times, you can use the getUTC methods,
which are exactly the same as the get methods, except they calculate the time based on the UTC (Coordinated Universal Time) standard

 Adding and Subtracting from a Given Date  
 According to the documentation, Date setters expect an interval-appropriate value.
 The setDays() setter, for instance, expects a day from 1 to 31. 
 But really, these ranges are nothing more than helpful recommendations because day values that lie outside of this range are rolled over/back into the next/preceding month(s). 
 For example, attempting to assign a day of 30 to February causes the date to roll over into March

 #DAY 3
 KEYBOARD, FORM, DOCUMENT/WINDOW EVENTS
 A keyboard event is fired when the user presses or releases a key on the keyboard.
 A form event is fired when a form control receives or loses focus or when the user modifies a form control value.
 A document/window event is triggered in situations when, for example, the page has loaded or when a user resizes the browser window.

The Keydown Event (onkeydown)
The keydown event occurs when the user presses down a key on the keyboard. You can handle the keydown event with the onkeydown event handler.
The Keyup Event (onkeyup)
The keyup event occurs when the user releases a key on the keyboard. You can handle the keyup event with the onkeyup event handler.
The Keypress Event (onkeypress)
The keypress event occurs when a user presses down a key on the keyboard that has a character value associated with it
You can handle the keypress event with the onkeypress event handler.

FORM EVENTS
A form event is fired when a form control receives or loses focus or when the user modify a form control value, such as by typing text in a text input, select any option in a select box etc. 
The Focus Event (onfocus)
The focus event occurs when the user gives focus to an element on a web page. You can handle the focus event with the onfocus event.
The Blur Event (onblur)
The blur event occurs when the user takes the focus away from a form element or a window. You can handle the blur event with the onblur event handler.
The Change Event (onchange)
The change event occurs when a user changes the value of a form element. You can handle the change event with the onchange event handler.
The Submit Event (onsubmit)
 The submit event only occurs when the user submits a form on a web page. You can handle the submit event with the onsubmit event handler.

 #DAY 4
 CREATING AN IMAGE SLIDER
 A great slideshow is identified by having good quality pictures of the same size, and having a proper animation. 
 It should allow the user to spend as much time as they need in one picture without rushing to the next one.

The image-slider-wrapper needs to set overflow: hidden cause ul will be a very long list in a line, but only one image can be seen.
There is no width set for ul( id=image_slider) because we will set it in Javascript. So when there are more/less images we don’t need to change css.
Webkit has default padding and margin for ul, so we will initialize it with 0px.
Set li to list-style: none and float left, so the images will be in a long line.


#WEEK 4
#DAY 1 
PROGRAMMING FLOWCHARTS, LOOPS AND DECISION STRUCTURES
Program Flowchart
The program flowchart illustrates the logic of the program and gives details on manipulating the data. A program flowchart is vital if the program is to be maintained easily,
and efficiently or if modifications are necessary.
PROGRAM FLOWCHART SYMBOLS
Program flowcharts are constructed with a set of standardised symbols that make it easier for persons other than the original programmer to read and maintain the program.
TERMINATOR-is used to illustrate the start and end of a program with the keywords BEGIN & END.
PROCESS-an instruction that is to be carried out by the program.
ARROW-indicates the flow of the algorithm pathway.
DECISION-is used to split the flowchart sequences into multiple paths inorder to represent SELECTION & REPETITION.
INPUT\OUTPUT-used to represent data entry by a user or display of data by the program.
SUBPROGRAM- is a program within another program.

JAVASCRIPT FOR LOOP
Loops can execute a block of code a number of times and are handy if you want to run the same code over and over again, each time with a different value.
JavaScript supports different kinds of loops:
for - loops through a block of code a number of times
for/in - loops through the properties of an object
for/of - loops through the values of an iterable object 
while - loops through a block of code while a specified condition is true
do/while - also loops through a block of code while a specified condition is true.

The For Loop
The for loop has the following syntax:
for (statement 1; statement 2; statement 3) {
 // code block to be executed
}
Statement 1 is executed (one time) before the execution of the code block.
Statement 2 defines the condition for executing the code block.
Statement 3 is executed (every time) after the code block has been executed.

#DAY 2
WEBSITE AND SEARCHH ENGINE OPTIMIZTION
Website optimization is a scientific approach to improving the performance of your website. SEO, is the practice of increasing both the quality and quantity of website traffic, 
as well as exposure to your brand, through non-paid (also known as "organic") search engine results.

IMAGE & VEDIO OPTIMIZATION
Gzip-is a file compression format that most browsers understand and that can run behind the scenes without requiring the user to even know it’s happening.
Depending on where you are hosting your application, gzipping may be as simple as flipping a configuration switch to specify that you want your server to gzip files when sending them out.
Minification is the process of removing unnecessary characters from code without affecting its functionality (whitespace, new-line characters, and so on). This allows you to decrease the size of the file you are transporting across the internet. It’s also useful for obfuscating your code, which makes it harder for sneaky hackers to detect security weak-points.
Content Distribution Network(CDN)
CDN, is a network that allows users from all over the world to be geographically closer to your content. A CDN allows you to take advantage of a bunch of proxy servers located all over the world, allowing your content to be loaded more quickly regardless of where your end-user is located.
SEARCH ENGINE OPTIMIZATION
Search engines are answer machines. They scour billions of pieces of content and evaluate thousands of factors to determine which content is most likely to answer your query.
Search engines do all of this by discovering and cataloguing all available content on the Internet (web pages, PDFs, images, videos, etc.) via a process known as “crawling and indexing,” and then ordering it by how well it matches the query in a process we refer to as “ranking.” 

Why SEO is important
While paid advertising, social media, and other online platforms can generate traffic to websites, the majority of online traffic is driven by search engines.
Organic search results cover more digital real estate, appear more credible to savvy searchers, and receive way more clicks than paid advertisements.




 

























