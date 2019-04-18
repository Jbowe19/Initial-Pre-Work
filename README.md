# TG-Pre-Work

### While we do want our developers to work smarter, not harder, please refrain from plagiarizing.  It is completely fine to reword information you have gleaned from internet sources, however, please be prepared to redo the work should you submit a directly copied/pasted answer.  If you must copy/paste, cite your sources (this citation doesn't need to be fancy - just state directly where you found the information or provide a link).  Additionally, some of the questions below are tricky.  The answers were not necessarily covered in the reading we assigned.  They are not intended to be straightforward because we expect you to do some research to discover the answers to the best of your ability.  If you cannot find an answer, explain what you do know and what you are stuck on.  

## When we hit https://www.techtonic.com/ what happens? Don’t focus too much on architecture (Monolithic, SOA, Microservices, etc.). Try to focus more on how the web functions in general terms/steps.

	When you click on a hyperlink or type a web address into your browser, the browser calls to the DNS server and finds the real address. The browser then send an HTTP request to the server asking it to send a copy to the user’s browser. If the server approves then tiny bytes of data called data packets are sent to the browser. The browser then reads the data and compiles it into a code that is then displayed to the client in the browser.

## From start to finish, how does data reach you to be rendered in the browser?

HTML code is parsed and turned into a DOM (Document Object Model) tree by the rendering engine. CSS attributes are also parsed and combined with the DOM tree to create a “render tree”. This tree contains all visual elements of your page such as width and height and color. They are arranged in hierarchal order and will be displayed accordingly in the browser.
Once the render tree is finished being constructed the rendering engine read the HTML and the layout process begins. This in turn is how the HTML elements are placed on the screen. Following the layout process – the painting process begins. This process involves each node of the render which is drawn out on the screen and contains the design and style elements.
Lastly, JavaScript is executed after the web page has been rendered and painted. 

## What code is rendered in the browser?

HTML and CSS

## What is the server-side code’s main function?

Server-side-code allows developers to be able to tailor website content to individual users and the action takes place on a web server which cannot be seen by the user. It allows websites to store persistent data about individual visitors. Server-side-code’s main function is to control what information is sent to the user.

## What is the client-side code’s main function?

Server-side-code allows developers to be able to tailor website content to individual users and the action takes place on a web server which cannot be seen by the user. It allows websites to store persistent data about individual visitors. Server-side-code’s main function is to control what information is sent to the user.

## What is runtime?

	Runtime is a period of time in which a program is running. It begins when the program is opened and it ends when the program is closed.

## How many instances of the client-side assets (HTML, CSS, JS, Images, etc.) are created?

There are three static assets HTML, CSS and JavaScript

## How many instances of the server-side code are available at any given time?

	An instance is one occurrence of a class or object. A class or object may have many instances.

## How many instances of the databases connected to the server application are created?

 There might be multiple instances of the same database for different purposes.
