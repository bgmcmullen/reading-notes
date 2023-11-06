# Class 01 Reading Notes:
When searching for a website how does it begin?\
The browser must first find the web address on the DNS.\
The browser then sends an HTTP message to the server.\
This message requests the website be sent from the server to client.\
TCP/IP is the method for this.\
If this server approves it sends the website to the browser.\
The browser displays it in small pieces.\
\
It is very important to the order in which HTML, CSS and JS files are parsed in a browser.\
The first thing that the browser processes is the HTML file. As it does this it will probably find links to CSS files for the style and JS files for the functionality of the website. When it finds these links it will request the corresponding file from the server. The browser then needs to make a DOM tree from the HTML and CSSON structure from the CSS and it must complete the JS code. As it does this is will display a the website to the user and if the page has JS the user will be able to interact with the functionality of the website.\
\
The add images to a website first you have to search for one. Google is a good way to this. It is crucial to make sure you are not violating any copyright laws.\
\
In JS you must define String in single or double quotes. Number must not be in quotes.\
\
As the named suggests variables are the way we store data in JS and they can be changed. Without variables it would be basically impossible to write a functional program since we would not be able to store and modify data.\
\
HTML attributes are a way to add additional information to one HTML element\