                                                     -----------------------------------WHAT IS---------------------------------------------

\_\_FRONT-END:

\_\_BACK-END:

\_\_FULL-STACK:

**API:
**API:-----(A pplication -- P rogramming -- I nterface)-----Is a software intermediary that enables two or more computer programs or components to communicate with each other.-----It is a type of software interface that offers a service to other pieces of software.-----APIs are a set of functions and procedures that allow for the creation of applications.-----Developers use APIs to bridge the gaps between small, discrete chunks of code to create applications that are powerful, resilient, secure, and able to meet user needs.-----APIs are an accessible way to extract and share data within and across organizations.-----A document or standard that describes how to build or use such a connection or interface is called an API specification.-----Let's start with an analogy.
---------------Do you remember telephone directories?---------------

            ⇢ A telephone directory allows a human to request information from another human, by telephone.

---On the web, APIs play the same role as directories. Except that the telephone is replaced by the Internet and humans by computers.

            ⇢ An API allows a computer to request information from another computer, via the internet.

**CACHING :
**CACHING:------Is the process of storing data in a temporary storage location, such as a cache, so that future requests for the same data can be served faster.-----It aims to improve application and system performance by storing multiple copies of data or files in a cache, which is a temporary storage location used by servers, apps, and web browsers to speed up site loading.-----Caching reduces the time to acquire the data from persistent memory, which used to take considerable time, thus, slowing the process.-----Caching is a modest form of fast, costlier memory used to enhance the performance of frequently or often accessed data.-----The files in a cache are not that different from the files in the cache of someone else who visits the same websites as you.

**CLI :
**CLI:-----(C ommand -- L ine -- I nterface)-----Is a text-based user interface that allows users to interact with a computer system by typing text-based commands.-----It emerged in the mid-1960s as an interactive and more user-friendly alternative to the non-interactive interface available with punched cards.-----CLIs accept as input commands that are entered by keyboard, and the commands invoked at the command prompt are then run by the computer.-----Unlike other interfaces where graphical icons represent actions, a CLI relies solely on textual input and output, allowing for more detailed control and administration.-----CLIs are also known as command-line user interfaces, console user interfaces, and character user interfaces.

**ORM :
**ORM:-----(O bject -- R elational -- M apping)-----Is a type of software that serves as an interface between an application program and a relational database, simulating an object-oriented database.-----It defines mappings between the database schema and the application’s classes.-----ORM can be considered as a layer of abstraction between the object world and the relational world.-----ORM is used to convert relational data into objects and vice versa, which is necessary when using object-oriented programming with a relational database. This conversion often involves writing repetitive code for each object, which can be avoided by using ORM.

**HTTP :
**HTTP:-----(H yper -- T ext --T ransfer --P rotocol)-----Is one of the application protocols of TCP/IP, the suite of protocols that powers the Internet.-----It's the most successful and popular protocol, it makes the World Wide Web work, giving browsers a language to communicate to remote servers that host web pages.

\_\_"The protocol used between a web server and a web browser":
-----"The correct answer is HTTP. Key Points The protocol used between a web server and a web browser to transfer HTML pages is called HTTP.-----The Hypertext Transfer Protocol (HTTP) is an application layer protocol in the Internet protocol suite model for distributed, collaborative, hypermedia information systems.-----HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.-----Important Points Some important protocols:-----SMTP - Simple Mail Transfer Protocol.-----FTP - File Transfer Protocol.-----TCP - Transmission Control Protocol.-----UDP - User Datagram Protocol.-----OSI - Open Systems Interconnection."
-----COMPLETE OVERVIEW AT : https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview

**HTTP Methods :
**GET :-----This method is used to : -- REQUEST DATA -- from a specified resource.
-----This method is used to RETRIEVE or GET INFORMATION from a specified resource on the server using a given URL.-----It’s a READ OPERATION used in RESTful APIs and does not modify the resource.
Example:

fetch('https://jsonplaceholder.typicode.com/posts/1')
.then(response => response.json())
.then(json => console.log(json))

\_\_POST :-----This method is used to : send data to a server to -- CREATE -- a new resource.
-----This method is used to SEND DATA to the server TO CREATE a new resource or append to an existing one.----- It’s a WRITE OPERATION used in RESTful APIs.
Example:

fetch('https://jsonplaceholder.typicode.com/posts', {
method: 'POST',
body: JSON.stringify({
title: 'New Post',
body: 'This is a new post.',
userId: 1,
}),
headers: {
'Content-type': 'application/json; charset=UTF-8',
},
})
.then(response => response.json())
.then(json => console.log(json))

\_\_PUT :-----This method is used to : -- UPDATE -- an existing resource with new data.
-----This method is used to SEND DATA to the server to UPDATE THE ENTIRE RESOURCE.-----It’s a WRITE OPERATION used in RESTful APIs.
Example:

fetch('https://jsonplaceholder.typicode.com/posts/1', {
method: 'PUT',
body: JSON.stringify({
title: 'Updated Post',
body: 'This post has been updated.',
userId: 1,
}),
headers: {
'Content-type': 'application/json; charset=UTF-8',
},
})
.then(response => response.json())
.then(json => console.log(json))

\_\_DELETE :-----This method is used to : -- DELETE -- a resource.
-----This method is used to DELETE THE SPECIFIED RESOURCE ON THE SERVER.-----It’s a WRITE OPERATION used in RESTful APIs.
Example:

fetch('https://jsonplaceholder.typicode.com/posts/1', {
method: 'DELETE',
})
.then(response => response.json())
.then(json => console.log(json))

**HTML :
**HTML:-----(H yper -- T ext -- M arkup -- L anguage)-----Is the standard markup language used to structure web pages and their content by using a series of elements, which are enclosed or wrapped around different parts of the content to make it appear or behave in a specific way.-----Some key points about HTML:

                                 ●  It is a markup language that uses tags to define the structure of web pages.
                                 ●  HTML is a combination of Hypertext and Markup language.
                                 ●  Hypertext defines the link between web pages.
                                 ●  HTML is human-readable and uses tags to manipulate text, images, and other content to display                                      them in the required format.
                                 ●  HTML was created by Tim Berners-Lee in 1991, and the first standard version was HTML 2.0,                                                    published in 1995.

                             ----------------------------------------Example of basic HTML structure:----------------------------------------

                                                                               <!DOCTYPE html>
                                                                               <html>
                                                                                  <head>
                                                                                    <title>My First Web Page</title>
                                                                                  </head>
                                                                                  <body>
                                                                                    <h1>Welcome to my first web page!</h1>
                                                                                    <p>This is an example paragraph.</p>
                                                                                  </body>
                                                                               </html>

-----In this example, the:
<!DOCTYPE html> declaration defines the document type,
-----and the: <html> element is the root element of an HTML page.
-----the: <head> element contains meta-information about the HTML page, such as the title.
-----while the: <body> element contains the visible page content.
-----the: <h1> element represents the main heading.
-----and the: <p> element represents a paragraph of text.

---It is often assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.---
----------Learning HTML is easy, as it is a simple and straightforward language to understand and use.----------

**JavaScript :
**JavaScript:-----JavaScript is a dynamic, high-level, interpreted programming language that is widely used for web development-----It is primarily used to create interactive and dynamic web pages, enabling features such as animations, form validation, and real-time content updates.

                                                   ----------Here are some key points about JavaScript:----------

-----It is a lightweight, interpreted language, meaning it does not require a compiler to execute the code.
-----JavaScript is used both on the client-side (in web browsers) and the server-side (using Node.js).
-----It is a multi-paradigm language, supporting object-oriented, imperative, and functional programming styles.
-----JavaScript’s syntax is similar to C and Java, but it has its own unique features that make it a versatile language for web development.
-----JavaScript can be used for game development, mobile app development, and even creating desktop applications.

       -----Here is a simple example of JavaScript code that displays an alert message when a button is clicked:-----

<!DOCTYPE html>
<html>
<body>

<button onclick="myFunction()">Click me</button>

<script>
function myFunction() {
  alert("Hello World!");
}
</script>

</body>
</html>

-----In this example, the onclick attribute in the <button> tag calls the myFunction() function when the button is clicked.
-----The myFunction() function then displays an alert message with the text “Hello World!”.

-----JavaScript is an essential language for web developers, and it is used by millions of websites and web applications worldwide.-----Whether you are just starting out or have years of experience, JavaScript provides endless possibilities for creating engaging and interactive web experiences.

**JavaScript API :
**JavaScript API:-----Is a set of built-in objects and functions in JavaScript that allow developers to interact with different components of a web browser or a web application.-----These APIs are used to perform various tasks such as manipulating the Document Object Model (DOM), handling events, managing storage, and performing networking operations.-----Some commonly used JavaScript APIs include the DOM API, Fetch API, Storage API, Geolocation API, and Canvas API.-----These APIs can be used in conjunction with third-party APIs to create dynamic and interactive web applications.

               -----Here is a basic example of using the Fetch API to make a GET request to fetch data from an API:-----

fetch('https://jsonplaceholder.typicode.com/todos/1')
.then(response => response.json())
.then(data => console.log(data))
.catch(error => console.error(error));

-----In this example, the fetch() function is used to make a GET request to the specified URL.
-----The response is then converted to JSON format using the response.json() method.
-----The resulting data is logged to the console.
-----If an error occurs during the request, it will be caught and logged to the console.

-----Remember to always consult the official documentation of the APIs you’re using to ensure correct usage and to stay updated on any changes or updates.

**JavaScript SDK :
**JavaScript SDK:-----(S oftware -- D evelopment -- K it)-----Is a “Software Development Kit” specifically designed for JavaScript.-----In simpler terms, an SDK is a set of tools, libraries, relevant examples, documentation, and guidelines that assist developers in creating applications for a specific platform or using a particular service.-----The JavaScript SDK, therefore, is a collection of JavaScript-based tools and resources that empower developers to interact with APIs, REST services, or other web-based services seamlessly.

              -----Here is a basic example of how a JavaScript SDK might be used to make a request to an API:-----

// import the SDK
const SDK = require('my-sdk');

// initialize the SDK with your API key
const sdk = new SDK('your-api-key');

// make a request to the API
sdk.makeRequest('endpoint', 'method', 'params')
.then(response => {
console.log(response);
})
.catch(error => {
console.error(error);
});

-----In this example, my-sdk is a hypothetical JavaScript SDK that provides an API client interface for making requests to a specific service or platform.
-----The SDK is initialized with the user’s API key, and then a request is made to a particular endpoint using the makeRequest method.
-----The SDK handles the details of the HTTP request, including authentication and data serialization, allowing the developer to focus on the specifics of their application.

-----Remember that each JavaScript SDK will have its own unique methods and functionality, and the exact usage will depend on the specific SDK you are working with.-----Always refer to the official documentation and examples provided by the SDK authors for the most accurate and up-to-date information.

**MARKDOWN :
**MARKDOWN:-----Is a lightweight markup language used to format text for easy readability and efficient writing on the web. It was created by John Gruber and Aaron Swartz in 2004 and is designed to be easy to read and write in its source code form.

                                       -----Here are some key features and components of Markdown:-----

-----Headers:----- You can create headers of different levels (h1, h2, h3, etc.) by using one to six “#” symbols at the beginning of a line, followed by a space and the header text.
-----Bold and Italic Text:----- To make a text bold, surround it with two asterisks (text) or two underscores (text). For italic text, surround it with one asterisk (text) or one underscore (text).
-----Lists:----- You can create unordered lists using “-”, “\*”, or “+”, followed by a space and the list item. Ordered lists are created by using numbers followed by a period and a space before each list item.
-----Links:----- To create a hyperlink, surround the link text with square brackets [ ], and then immediately follow the link text with the URL in parentheses ( ).
-----Images:----- To insert an image, use an exclamation mark (!), followed by alt text in square brackets [ ], and then the image URL in parentheses ( ).

**CRUD :
**CRUD:-----(C reate -- R ead (view) -- U pdate -- D elete).

**SaaS app :
**SaaS app:-----(S oftware -- A s -- A -- S ervice)-----Is a software licensing model that allows access to software on a subscription basis using external servers.-----SaaS apps are hosted on a cloud server and distributed to users via the internet, rather than having to install the software on the user's computer.-----The code, servers, and database that make up an application are hosted and maintained by software providers like Amazon Web Services or Google Cloud.-----SaaS has many business applications, including file sharing, email, calendars, customer retention management, and human resources.

**SMTP server :
**SMTP:-----(S imple -- M ail -- T ransfer -- P rotocol)-----Is a communication protocol used by mail servers to send, receive, and relay outgoing emails between senders and receivers.-----SMTP servers are applications that provide a service to other applications within a network, called clients.-----Without SMTP, email communication would be nonexistent since it determines which servers will receive relay messages.-----SMTP servers typically use TCP on port 25 or 587, which identifies specific processes when an internet or network message is forwarded to a server.-----User-level email clients typically use SMTP only for sending messages to a mail server for relaying, and typically submit outgoing email to the mail server on port 587 or 465 per RFC 8314.

**PORT:
**PORT:-----Is a virtual point where network connections start and end, managed by a computer's operating system.-----It is a 16-bit unsigned integer number from 1 to 65535 that allows multiple programs to use the same IP address. A specific network port is required to transmit or receive data from network devices.-----Ports allow computers to differentiate between different kinds of traffic, such as emails going to a different port than webpages, even though both reach a computer over the same Internet connection.

**RFC 8314:
**RFC 8314:-----This specification outlines current recommendations for the use of Transport Layer Security (TLS) to provide confidentiality of email traffic between a Mail User Agent (MUA) and a Mail Submission Server or Mail Access Server.-----This document updates RFCs 1939, 2595, 3501, 5068, 6186, and 6409.

**MUA:
**MUA:-----(M ail -- U ser -- A gent)-----Is

**SPA :
**SPA:-----(S ingle -- P age -- A pplication)-----Is

**TLS:
**TLS:-----(T ransport -- L ayer -- S ecurity)-----Is
