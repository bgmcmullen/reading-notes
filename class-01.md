# Class 01 Reading Notes:
When searching for a website how does it begin?\
The browser must first find the web address on the DNS.\
The browser then sends an HTTP message to the server.\
This message requests the website be sent from the server to client.\
TCP/IP is the method for this.\
If this server approves it sends the website to the browser.\
The browser displays it in small pieces.\
\
It is very important to know the order in which HTML, CSS and JS files are parsed in a browser.\
The first thing that the browser processes is the HTML file. As it does this it will probably find links to CSS files for the style and JS files for the functionality of the website. When it finds these links it will request the corresponding file from the server. The browser then needs to make a DOM tree from the HTML and CSSON structure from the CSS and it must complete the JS code. As it does this it will display a the website to the user and if the page has JS the user will be able to interact with the functionality of the website.\
\
To add images to a website first you have to search for one. Google images is a good way to do this. It is crucial to make sure you are not violating any copyright laws.\
\
In JS you must define a String in single or double quotes. Numbers must not be in quotes.\
\
As the named suggests variables are the way we store data in JS and they can be changed. Without variables it would be basically impossible to write a functional program since we would not be able to store and modify data.\
\
HTML attributes are a way to add additional information to one HTML element\
\
An HTML element begins with an open tag and ends with closing tag which is identical to the opening tag but with a slash. The element's content will go between the tags.\
\
The article element is used to make a block of independent content on a webpage. The section element does something similar but as the name suggests it is intended for dividing the page into independent sections.\
\
A typical website will need a header likely a nav for the navigation bar, a main for the content, possibly an aside for the sidebar and a footer. There will most likely be article, section or div elements in the main element.\
\
Metadata is data telling us about other data. The meta element is used in the head for information like the character set, language, author, or other information about the page.\
\
When designing a website before jumping into the technical work it is important to determine the purpose and goals of the website and how those will be achieved. The most important question is what are you trying to accomplish.\
\
h1 has a particular purpose. It is a top level heading and should be used specifically for that. If you are writing customized text that is not the heading span would be a better choice.\
\
Semantic tags have some benefits both when communicating with computers and with other humans. Good use of semantic tags will give other developers a clearer idea of the purpose of the content of the tags. Also search engines and screen readers will see the content of semantic tags as important.\
\
JavaScript is used in almost all websites. It is needed for things like animated graphics and interactive games.\
\
JS is added to the a HTML document with the script element typically with a link to another file but it can be written directly into the content of the element.

## Things I want to know more about.
I want to learn more about the nuances of how different HTML elements are used since many have similar functions but are not interchangeable.