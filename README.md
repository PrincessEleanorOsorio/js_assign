# js_assign

JavaScript can be implemented using JavaScript statements that are placed
within the <script>... </script> HTML tags in a web page.
You can place the <script> tags, containing your JavaScript, anywhere within
you web page, but it is normally recommended that you should keep it within
the <head> tags.

The script tag takes two important attributes:
 Language: This attribute specifies what scripting language you are using.
Typically, its value will be javascript. Although recent versions of HTML
(and XHTML, its successor) have phased out the use of this attribute.
 Type: This attribute is what is now recommended to indicate the scripting
language in use and its value should be set to "text/javascript".

JavaScript ignores spaces, tabs, and newlines that appear in JavaScript
programs. You can use spaces, tabs, and newlines freely in your program and
you are free to format and indent your programs in a neat and consistent way
that makes the code easy to read and understand.

Simple statements in JavaScript are generally followed by a semicolon character,
just as they are in C, C++, and Java. JavaScript, however, allows you to omit
this semicolon if each of your statements are placed on a separate line. 

JavaScript is a case-sensitive language. This means that the language keywords,
variables, function names, and any other identifiers must always be typed with a
consistent capitalization of letters.
So the identifiers Time and TIME will convey different meanings in JavaScript.
NOTE: Care should be taken while writing variable and function names in
JavaScript.

JavaScript supports both C-style and C++-style comments. Thus:
 Any text between a // and the end of a line is treated as a comment and
is ignored by JavaScript.
 Any text between the characters /* and */ is treated as a comment. This
may span multiple lines.
 JavaScript also recognizes the HTML comment opening sequence <!--.
JavaScript treats this as a single-line comment, just as it does the //
comment.
 The HTML comment closing sequence --> is not recognized by JavaScript
so it should be written as //-->.

There is a flexibility given to include JavaScript code anywhere in an HTML
document. However the most preferred ways to include JavaScript in an HTML
file are as follows:
 Script in <head>...</head> section.
 Script in <body>...</body> section.
 Script in <body>...</body> and <head>...</head> sections.
 Script in an external file and then include in <head>...</head> section.
In the following section, we will see how we can place JavaScript in an HTML file
in different ways.

If you need a script to run as the page loads so that the script generates content
in the page, then the script goes in the <body> portion of the document. In this
case, you would not have any function defined using JavaScript. 

As you begin to work more extensively with JavaScript, you will be likely to find
that there are cases where you are reusing identical JavaScript code on multiple
pages of a site.
You are not restricted to be maintaining identical code in multiple HTML files.
The script tag provides a mechanism to allow you to store JavaScript in an
external file and then include it into your HTML files.
Here is an example to show how you can include an external JavaScript file in
your HTML code using script tag and its src attribute.

To use JavaScript from an external file source, you need to write all your
JavaScript source code in a simple text file with the extension ".js" and then
include that file as shown above.
For example, you can keep the following content in filename.js file and then
you can use sayHello function in your HTML file after including the filename.js
file.

One of the most fundamental characteristics of a programming language is the
set of data types it supports. These are the type of values that can be
represented and manipulated in a programming language.
JavaScript allows you to work with three primitive data types:
 Numbers, e.g., 123, 120.50 etc.
 Strings of text, e.g. "This text string" etc.
 Boolean, e.g. true or false.
JavaScript also defines two trivial data types, null and undefined, each of
which defines only a single value. In addition to these primitive data types,
JavaScript supports a composite data type known as object. We will cover
objects in detail in a separate chapter.
Note: Java does not make a distinction between integer values and floatingpoint
values. All numbers in JavaScript are represented as floating-point values.
JavaScript represents numbers using the 64-bit floating-point format defined by
the IEEE 754 standard.

Like many other programming languages, JavaScript has variables. Variables
can be thought of as named containers. You can place data into these containers
and then refer to the data simply by naming the container.
