---
title: Important NODE-EXPRESSS-MONGODB question
excerpt: Node,express and mongodb is the most important programming language for backend development. You probably don't know it well enough!
image: backend.png
isFeatured: false
date: '2024-08-21'
---

1. What is node js ?

Node. js is a single-threaded, open-source, cross-platform runtime environment for building fast and scalable server-side and networking applications. It runs on the V8 JavaScript runtime engine, and it uses event-driven, non-blocking I/O architecture, which makes it efficient and suitable for real-time applications.

2. Features : -
- Single Threaded. Node. ...
- Asynchronous. Node. ...
- Event Driven. The event-driven concept is similar to the concept of a callback function in asynchronous programming. ...
- Open Source. Node. ...
- Performance. ...
- Highly Scalable. ...
- Node Package Manager(NPM) ...
- No Buffering.
3. Advantage & disadvantage : -

Its event-driven nature, microservices architecture, and MongoDB support allows businesses to grow and scale their products easily. However, be careful with heavy CPU bound tasks, as Node. js can reduce the performance of your application

4. Node vs javascript : -

NodeJS is a Javascript runtime environment. Javascript is a computer programming language that is used to build scripts for websites. With the support of NodeJS, Javascript can be executed outside of the browser. Only browsers are capable of running Javascript.

5. Uses and benefits : -

Node. js allows programmers to develop server-side JavaScript and frontend JavaScript codes with simplicity. One of the major node. js advantages is that it eliminates the need for two resource teams, saving time, money, and energy for overall project development.

6. Node vs angular : -

The Angular features allow programmers to build interactive, client-side web applications, making the framework widely used by JavaScript developers nowadays. Node. js, on the other hand, is mainly used by JavaScript developers to create fast & scalable networking and server-side applications.

7. Why node is single threaded : -

Node. js is Single Threaded, i.e. it executes the code in a single sequence or direction. At a given time, only a single task/ call is executed. Asynchronous and Single-Threaded: Execution doesn't wait for the current request to complete and moves to the next request/call

8. Different api function : -

**The two types of API functions in Node.js are:**

- Asynchronous, non-blocking functions.
- Synchronous, blocking functions.
9. Synchronous and asynchronous function : -

Asynchronous is a non-blocking architecture, so the execution of one task isn't dependent on another. Tasks can run simultaneously. Synchronous is a blocking architecture, so the execution of each operation is dependent on the completion of the one before it.

10. Control flow function : -

A control flow function is a lightweight, generic piece of code which runs in between several asynchronous function calls and which take care of the necessary housekeeping to: control the order of execution, collect data, limit concurrency and.

11. Event loop : -

An event loop is an endless loop, which waits for tasks, executes them, and then sleeps until it receives more tasks. The event loop executes tasks from the event queue only when the call stack is empty i.e. there is no ongoing task. The event loop allows us to use callbacks and promises.

Node. js has two types of threads: one Event Loop and k Workers. The Event Loop is responsible for JavaScript callbacks and non-blocking I/O, and a Worker executes tasks corresponding to C++ code that completes an asynchronous request, including blocking I/O and CPU-intensive work.

12. Order of execution in control flow statement : -

**These are following the order in which control flow statements are used to process function calls:**

- Handling execution and queue.
- Data collection and storage.
- Concurrency handling and limiting.
- Execution of the next piece of code.

Control flow in Node. js is typically managed using one of three methods: callbacks, promises, and async/await. 1. Callbacks: Callbacks are functions that are passed as arguments to other functions and are executed when that function completes its task.

13. Event based model : -

Node. js uses event driven programming. It means as soon as Node starts its server, it simply initiates its variables, declares functions and then simply waits for event to occur. It is the one of the reason why Node. js is pretty fast compared to other similar technologies.

14. Ajax vs node : -

Node. js allows code to be written on the server side. AJAX is apart of the front-end of website development. This means that you can use AJAX to send off requests to the server, but node can be written to process those requests and shoot back responses.

15. Framework : -

Express.js Meteor

Sails.js Angular

Next.js

16. Test pyramid : -

The test pyramid in Node. js is a conceptual model that guides software developers in structuring their test suites. It emphasizes a balanced distribution of different types of tests, such as unit, integration, and end-to-end tests.

17. Libuv : -

Libuv is a library written in the programming language C that helps nodejs to improve efficiency while running tasks parallelly. However, nodejs already have async API's. It uses Libuvs's thread pools if async API is not available in nodejs and processes are blocking the operations.

18. Spawn vs fork method : -

Fork creates a child process that is a copy of the parent process, while spawn creates a new process from scratch. Exec is typically used for short-lived processes, while fork and spawn are typically used for long-lived processes

19. Middleware : -

The middleware in node. js is a function that will have all the access for requesting an object, responding to an object, and moving to the next middleware function in the application request-response cycle.

The main purpose of the middleware is to modify the req and res objects, and then compile and execute any code that is required. It also helps to terminate the request-response session and call for the next middleware in the stack.

20. Global object : -

Node. js Global Objects are the objects that are available in all modules. Global Objects are built-in objects that are part of the JavaScript and can be used directly in the application without importing any particular module.

21. Assert : -

The assert module provides a way of testing expressions. If the expression evaluates to 0, or false, an assertion failure is being caused, and the program is terminated. This module was built to be used internally by Node.

The assert() method tests if a given expression is true or not. If the expression evaluates to 0, or false, an assertion failure is being caused, and the program is terminated. The assert() method is an alias of the assert. ok() method.

22. Stubs : -

Stubs are functions or programs that affect the behavior of components or modules. Stubs are dummy objects for testing. Stubs implement a pre-programmed response.

23. Buffer class : -

The Buffer class in Node. js is used to perform operations on raw binary data. Generally, Buffer refers to the particular memory location in memory. Buffer and array have some similarities, but the difference is array can be any type, and it can be resizable.

In Node Js, buffers are used to store raw binary data. A buffer represents a

chunk of memory that is allocated on our computer. The size of the buffer, once set, cannot be changed. A buffer is used to store bytes.

24. Why express js used ?

Express is a node js web application framework that provides broad features for building web and mobile applications. It is used to build a single page, multipage, and hybrid web application. It's a layer built on the top of the Node js that helps manage servers and routes

25. Connect module : -

Connect-flash module for Node. js allows the developers to send a message whenever a user is redirecting to a specified web-page.

26. Streams : -

A stream is an abstract interface for working with streaming data in Node.js. The node:stream module provides an API for implementing the stream interface. There are many stream objects provided by Node.js. For instance, a request to an HTTP server and process.stdout are both stream instances.

Streams are objects that allows developers to read/write data to and from a source in a continuous manner. There are four main types of streams in Node. js; readable, writable, duplex and transform. Each stream is an eventEmitter instance that emits different events at several intervals.

27. Use of repl : -

Note: REPL stands for Read Evaluate Print Loop, and it is a programming language environment (basically a console window) that takes single expression as user input and returns the result back to the console after execution. The REPL session provides a convenient way to quickly test simple JavaScript code.

28. Tracing : -

Tracing is a convenient way for developers to monitor and analyze application performance at runtime. Node. js offers a few options to generate and diagnose custom trace data in JavaScript applications. The built-in trace mechanism supports centralized tracing for not only V8 and Node. js core, but also userspace code.

You can also use the flag --trace-warnings , which will give you the stack trace of where the warning is coming from whenever you encounter a warning. This warning is showing something that might not work in the future: a deprecation warning .

29. Packages.json : -

Your package. json holds important information about the project. It contains human-readable metadata about the project (like the project name and description) as well as functional metadata like the package version number and a list of dependencies required by the application.

30. Difference between read file and create file : -

readfile loads the whole file into the memory you pointed out, the fs. createReadStream, on the other hand, reads the entire file in chunks of sizes that you specified. The client will also receive the data faster with fs

31. Crypto module : -

This module can be used for encrypting, decrypting, or hashing any type of data. This encryption and decryption basically help to secure and add a layer of authentication to the data. The main use case of the crypto module is to convert the plain readable text to an encrypted format and decrypt it when required

32. Passport : -

The Passport is a node package, or library which we can install in any nodeJs project. The Passport provides the functionality for authentication in the app. Also, it provides different encryption strategies to encrypt user information, such as a password.

33. how to get file information in node js ?

To get information about a file, we can use the fs. Stats object, which is returned by the fs. stat() , fs.

34. DNS lookup function : -

lookup() Method. The dns. lookup() method resolves the host name (e.g., tutorialspoint.com) into the first found A IPv4) or AAAA (IPv6) record. The properties available under the options are optional.

The node:dns module enables name resolution. For example, use it to look up IP addresses of host names. Although named for the Domain Name System (DNS), it does not always use the DNS protocol for lookups. dns. lookup() uses the operating system facilities to perform name resolution.

35. Eventemitter : -

The EventEmitter class can be used to create and handle custom events module. The syntax to Import the events module are given below: Syntax: const EventEmitter = require('events'); All EventEmitters emit the event newListener when new listeners are added and removeListener when existing listeners are removed.

36. Settimeout() vs setimmediate() : -

setImmediate() and setTimeout() are similar, but behave in different ways depending on when they are called. setImmediate() is designed to execute a script once the current poll phase completes. setTimeout() schedules a script to be run after a minimum threshold in ms has elapsed.

37. Module exports purpose : -

module. Exports is the object that is returned to the require() call. By module. exports, we can export functions, objects, and their references from one file and can use them in other files by importing them by require() method.

38. What is the difference between asynchronous and non-blocking Nodejs?

    Non-Blocking: It refers to the program that does not block the execution of further operations. Non-Blocking methods are executed asynchronously. Asynchronously means that the program may not necessarily execute line by line

39. Error first callback : -

Error-First Callback in Node. js is a function which either returns an error object or any successful data returned by the function. The first argument in the function is reserved for the error object. If any error has occurred during the execution of the function, it will be returned by the first argument.

40. Url module : -

The URL module in Node. js is used when working with URLs in our Node. js file. It provides functions to access different parts of our URL. We use this module in web development when we work with URLs to make HTTP requests to external APIs and handle file paths.

41. Use of NODE\_ENV : -

NODE\_ENV is an environment variable that stands for node environment in the express server. The NODE\_ENV environment variable specifies the environment in which an application is running (usually, development or production)

42. **What are the various timing features of Node. js ?**
- callback: This parameter holds the function that to be executed.
- delay: This parameter holds the number of milliseconds to wait before calling the callback function.
- args: This parameter holds the optional parameter.
43. **Below is the list of the tasks which must be done asynchronously using the event loop:**
- I/O operations.
- Heavy computation.
- Anything requiring blocking.

Asynchronous flow refers to the way Node. js handles and executes ensuring that the main program flow remains unblocked. As a server-side runtime environment built on Chrome's V8 JavaScript engine, Node. js efficiently manages concurrent tasks and optimizes resource utilization.

44. Reactor pattern : -

Note: Node. js is Asynchronous in nature. Reactor Pattern comprises of: Resources: They are shared by multiple applications for I/O operations, generally slower in executions. Synchronous Event De-multiplexer/Event Notifier: This uses Event Loop for blocking on all resources.

45. Frontend vs backend development : -

Node. js can also be used with popular frontend frameworks like React, Vue, and Angular, to create scalable and high-performance applications. On the backend, Node. js is used to develop server-side applications that handle network requests, data processing, and database operations.

46. Major security implementation : -

Establishing practices like validating user input, implementing authentication, limiting request sizes, and setting up logging and monitoring are good first steps to securing Node. js. For specific concerns about code injection attacks, here are five ways to prevent code injection in Node.

- Allow Using Secure Passwords Only. ...
- Secure Your Stored Passwords with Encryption. ...
- Limit the Number of Login Attempts per User per Unit of Time. ...
- Keep Your Node. ...
- Do Not Install Questionable Packages. ...
- Always Validate Input and Output Data. ...
- Always Replace Default Cookie Names.
47. ESLint : -

ESLint is the dominant tool for linting Node. JS packages. It is a pluggable and configurable linter tool for identifying and reporting on patterns in JavaScript. It uses the AST (Abstract Syntax Tree) to evaluate patterns in code.

One of the main benefits of using ESLint for software security is that it automates the detection of potential vulnerabilities. This can save you time and effort that would be spent manually reviewing your code, and can help you catch issues early on in the development process before they become a bigger problem.

48. Stubs : -

Stubs are functions or programs that affect the behavior of components or modules. Stubs are dummy objects for testing. Stubs implement a pre-programmed response.

49. process.nexttick vs setimmediate in node js : -

It is interesting to note that setImmediate adds callbacks to the event queue that are executed during the check phase, whereas process. nextTick executes callbacks immediately after the current phase.

setImmediate() is processed in the Check handlers phase, while process. nextTick() is processed at the starting of the event loop and between each phase of the event loop.

50. How does NodeJS handle child threads?

Node. js is a single-threaded runtime, which means that it does not have the ability to create child threads or to delegate work to them. However, it is designed to be highly scalable and can perform non-blocking I/O operations, allowing it to handle many concurrent connections without the need for child threads.

It does not expose child threads and thread management methods to the developer. Technically, Node. js does spawn child threads for certain tasks such as asynchronous I/O, but these run behind the scenes and do not execute any application JavaScript code, nor block the main event loop.

51. Punycode : -

Punycode is a character encoding scheme defined by RFC 3492 that is primarily intended for use in Internationalized Domain Names. Because host names in URLs are limited to ASCII characters only, Domain Names that contain non-ASCII characters must be converted into ASCII using the Punycode scheme.

Punycode is a special encoding for converting Unicode characters in different languages to ASCII. It is used to correctly transcode a domain name containing non-Latin characters into addresses that comply with DNS standards.

52. Exit code of node : -

The following is the list of exit codes in Node.js along with its descriptions:

- **Exit Code 0:** Node.js normally ends with a status code of 0 whenever there are no more open async operations and the code doesn’t produce any uncaught exceptions.
- **Exit Code 1, Uncaught Fatal Exception:** If an uncaught exception occurs and it is not resolved by a domain or a “uncaughtException” event handler, Node.js exits with an exit code of 1.
- **Exit Code 2:** The exit code 2 is reserved by Bash for abuse of built-in features.
- **Exit Code 3, Internal JavaScript Parse Error:** When internal code cannot be effectively interpreted, this exit code might be utilised in development. This is highly uncommon and often only occurs while Node.js is being developed.
- **Exit Code 4, Internal JavaScript Evaluation Failure:** It is also applied in situations where the JavaScript code fails to return the function value during development.
- **Exit Code 5, Fatal Error:** When a fatal, unrecoverable error occurred in V8, this exit code is utilised. Usually, stderr will produce a message with the prefix FATAL ERROR.
- **Exit Code 6, Non-function Internal Exception Handler:** When an internal fatal exception handler function is set to a non-function and unable to be invoked, it is helpful.
- **Exit Code 7, Internal Exception Handler Run-Time Failure:** This error code is used when the internal fatal exception handler code itself issued an error when attempting to handle the uncaught exception. This may occur, for instance, if a domain.on(‘error’) handler or a “uncaughtException” returns an error.
- **Exit Code 8:** Exit code 8 in earlier versions of Node.js was sometimes used to denote an uncaught error.
- **Exit Code 9, Invalid Argument:** This is employed when an unspecified option was given or when a value-required option was given without one..
- **Exit Code 10, Internal JavaScript Run-Time Failure:** When the bootstrapping function was invoked, the JavaScript source code internal to Node.js’s bootstrapping procedure threw an error.
- **Exit Code 12, Invalid Debug Argument:** The ports specified were either unavailable or invalid, yet the —debug, —inspect, and/or —debug-brk options were set.
- **Exit Code >128, Signal Exits:** Node.js’s exit code is 128 plus the signal code’s value if it gets a fatal signal like SIGKILL or SIGHUP. This is a common Unix practice since signal exits set the high-order bit before containing the signal code’s value and exit codes are often specified as 7-bit integers.
53. Is crypto available in node JS?

Crypto is a module in Node. js which deals with an algorithm that performs data encryption and decryption. This is used for security purpose like user authentication where storing the password in Database in the encrypted form. Crypto module provides set of classes like hash, HMAC, cipher, decipher, sign, and verify.

54. how install update and delete a dependency in node js ?
- We can update the project dependencies using the update command: npm update.
- We can update any particular project dependency using the following command: npm update <packagename>
- We can uninstall a project dependency using the following command: npm uninstall <package\_name>
55. Create simple server : -
- Step 1: Import HTTP module. ...
- Step 2: Create Variables For Host And Port. ...
- Step 3: Create A Server Process. ...
- Step 4: Implement the requestListener function. ...
- Step 5: Start And Test The HTTP Server.

●

var http = require('http'); http.createServer(function (req, res) {

res.writeHead(200, {'Content-Type': 'text/html'}); res.write('Hello World!');

res.end();

}).listen(8080);

56. Implement async : -

The asynchronous function can be written in Node. js using 'async' preceding the function name. The asynchronous function returns an implicit Promise as a result. The async function helps to write promise-based code asynchronously via the event loop

57. Types of http request : -

HTTP (Hypertext Transfer Protocol) specifies a collection of request methods to specify what action is to be performed on a particular resource. The most commonly used HTTP request methods are GET, POST, PUT, PATCH, and DELETE.

58. Npm : -

What is NPM? NPM is a package manager for Node.js packages, or modules if you like. www.npmjs.com hosts thousands of free packages to download and use. The NPM program is installed on your computer when you install Node.js. NPM is already ready to run on your computer!

59. Piping : -

Piping in NodeJS is the process by which byte data from one stream is sent to another stream. What are streams? Streams in NodeJS are a sequence of bytes. When a program processes some data it needs to read all the data into memory and then process it and write out the data back into some location.

60. Flag used in read/write operation : -



||||
| :- | :- | :- |
||r|Open file for reading. An exception occurs if the file does not exist.|
|r+|Open file for reading and writing. An exception occurs if the file does not exist.||
|rs|Open file for reading in synchronous mode.||
|rs+|Open file for reading and writing, telling the OS to open it synchronously. See notes for 'rs' about using this with caution.||
|w|Open file for writing. The file is created (if it does not exist) or truncated (if it exists).||
|wx|Like 'w' but fails if path exists.||
|w+|Open file for reading and writing. The file is created (if it does not exist) or truncated (if it exists).||



|wx+|Like 'w+' but fails if path exists.|
| - | - |
|a|Open file for appending. The file is created if it does not exist.|
|ax|Like 'a' but fails if path exists.|
|a+|Open file for reading and appending. The file is created if it does not exist.|
|ax+|Like 'a+' but fails if path exists.|

61. Process model : -

Contrary to the traditional web server model, NodeJS uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. The NodeJS process model can be explained with three architectural features of NodeJS. Single-threaded event loop. Non-Blocking I/O Model. Event-driven and Asynchronous by default

62. Chaining : -

In Node.js, chaining refers to the practice of calling multiple functions on the same object in a single statement.

63. CLI in node js : -

Command-line interfaces (CLIs) built-in Node. js authorize automating repetitive tasks while leveraging the Node. js ecosystem. Package managers like npm and yarn are distributed and ingested across multiple platforms.

js. We use command-line utilities every day, whether it be git, grep, awk, npm, or any other terminal app. CLIs are super useful and usually the fastest way to get something done.

64. require() method : -

The require() function is a built-in CommonJS module function supported in Node.js that lets you include modules within your project. This is because, by default, Node.js treats JavaScript code as CommonJS modules.

65. Why node js use v8 : -

V8 is a high-performance JavaScript engine developed by Google and used in Google Chrome, the open-source browser from Google. It was designed to improve the performance of web applications by compiling JavaScript into native machine code rather than interpreting it, which makes it faster

66. Template engine : -

Template engine helps to create an HTML template with minimal code. Also, it can inject data into an HTML template on the client side and produce the final HTML. EJS is a simple templating language that is used to generate HTML markup with plain JavaScript. It also helps to embed JavaScript into HTML pages.

67. Express generator : -

Express-generator is an all-in-one tool that allows you to quickly create a node-js application using the express library. Thanks to this generator, it will be possible to specify the template (view), the CSS preprocessor, etc.

68. Template literals : -

Template literals are literals delimited with backtick ( ` ) characters, allowing for multi-line strings, string interpolation with embedded expressions, and special constructs called tagged templates

69. CSRF attack : -

Cross-site request forgery attacks (CSRF or XSRF for short) works by an attacker gaining access to a victim's browser — typically through a malicious link.

js prevents the Cross-Site Request Forgery(CSRF) attack on an application. By using this module, when a browser renders up a page from the server, it sends a randomly generated string as a CSRF token. Therefore, when the POST request is performed, it will send the random CSRF token as a cookie.

70. Microservice : -

Node. js Microservices are self-contained and independent of each other. This means that every service is developed, deployed, and scaled as a separate and standalone unit. They do not have any dependency on other services even though these services combine to form the application. This is called as loose-coupling.

Node. js is ideal for building microservices due to its non-blocking I/O model, event-driven architecture, and lightweight design. As a result, it enables developers to create high-performance, real-time applications that can scale easily and remain resilient in the face of failure.

71. Docker hub : -

Docker will create containerized applications that run on any type of environment that have all the dependencies within it. So setting up the development environment is just one command away. Docker has many use cases – this scenario is just one of them

Docker Hub is a collaboration tool and a marketplace for community developers, open source contributors, and independent software vendors (ISVs) to distribute their code publicly. Docker Hub provides a consistent, secure, and trusted experience, making it easy for developers to access software they need.

**EXPRESS-JS**

1. What is express ?

It is used for designing and building web applications quickly and easily. Web applications are web apps that you can run on a web browser. Since Express. js only requires javascript, it becomes easier for programmers and developers to build web applications and API without any effort.

2. Features : -

Express. js can be used for various purposes, including building single-page applications, mobile applications, RESTful APIs, server-side rendering, real-time applications, and microservices. Express. js provides various key features, including routing, middleware, templates, error handling, security, and ease of use.

3. Advantage and disadvantage : -

**Advantages of ExpressJS:**

- Minimal and Lightweight. Express. ...
- Easy to Learn and Use. Express. ...
- Middleware Support. One of the key features of Express. ...
- Routing. Express. ...
- Template Engines. Express. ...
- Database Support. Express. ...
- Scalability. Express. ...
- Lack of Structure and Convention. One of the primary limitations of using Express.

**disadvantages of express. js?**

- Event-driven nature (callbacks)
- Code organization.
- Its not big on security.
- Its error messages are usually unhelpful.
4. how express handle routing ?

You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD.

5. Middleware : -

Middleware functions are functions that have access to the request object ( req ), the response object ( res ), and the next function in the application's request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.

**An Express application can use the following types of middleware:**

- Application-level middleware.
- Router-level middleware.
- Error-handling middleware.
- Built-in middleware.
- Third-party middleware.

●

You can enable your custom middleware in your Express server by applying the built-in Express. js middleware, . use() . const express = require('express'); const setCurrentUser = require('./middleware/setCurrentUser.

Middleware Chaining: Middleware can be chained from one to another, Hence creating a chain of functions that are executed in order. The last function sends the response back to the browser. So, before sending the response back to the browser the different middleware process the request.

6. how can you handle form data in express js ?

Getting form data with the post method in Express. js. First, we need to install the express and body-parser packages. body-parser is used to process the data sent through an HTTP request.

const express = require('express'); const app = express();

app.post('/submit-form', (req, res) => {

const name = req.body.name;

const email = req.body.email;

//Do some processing and validation on the data //Store the data in a database or send it as an email

res.send('Form submitted successfully!');

});

app.listen(3000, () => console.log('Server running on port 3000')); const bodyParser = require('body-parser'); app.use(bodyParser.urlencoded({ extended: false }));

7. How can you handle static file ?

To serve static files such as images, CSS files, and JavaScript files, use the express.static built-in middleware function in Express. The root argument specifies the root directory from which to serve static assets. For more information on the options argument, see express.static.

Serving static files in Expressjs: ExpressJS provides a built-in middleware function called express. static() that allows you to serve static files in your application. This middleware takes a directory path as an argument and serves any files in that directory at their respective URL paths.

Using express. static() method, you can server static resources directly by specifying the folder name where you have stored your static resources. The following example serves static resources from the public folder under the root folder of your application.

8. purpose of next() in express js : -

The next() function is a function in the Express router that, when invoked, executes the next middleware in the middleware stack. If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.

The next() function returns the next item in an iterator. You can add a default return value, to return if the iterable has reached to its end.

9. how can you handle route parameter in express js ?

Route parameters are accessible in the route handling function on the params property of the Request object. Recall from the previous tutorials that both a Request and Response object are passed as input of the route handling function by the Express.

10. how can you implement authentication ?

Authentication is a process in which the credentials provided are compared to those on file in a database of authorized users' information on a local operating system or within an authentication server. If the credentials match, the process is completed and the user is granted authorization for access.

**Implementing User Authentication in Express Apps**

- Step 1: Setting Up Development Environment. First, create a project folder and cd into it by running: mkdir user-authentication. ...
- Step 2: Connecting Your Application to a Database. ...
- Step 3: Creating User Model. ...
- Step 4: Implementing Sign-in and Sign-up Routes.
11. How can you handle error ?

The simplest way of handling errors in Express applications is by putting the error handling logic in the individual route handler functions. We can either check for specific error conditions or use a try-catch block for intercepting the error condition before invoking the logic for handling the error.

12. What is route handler in Express JS?

As a generic term, a route handler is code that is looking for a request to a specific incoming URL such as /login and often a specific HTTP verb such as POST and has specific code for handling that precise URL and verb. Some examples: Serve a specific web page.

13. how can you access request query parameters ?

Your query parameters can be retrieved from the query object on the request object sent to your route. It is in the form of an object in which you can directly access the query parameters you care about. In this case Express handles all of the URL parsing for you and exposes the retrieved parameters as this object.

We can access these route parameters on our req. params object using the syntax shown below. app. get(/:id, (req, res) => { const id = req.params.id; });

14. How can you send json response ?

json() function sends a JSON response. This method sends a response (with the correct content-type) that is the parameter converted to a JSON string using the JSON. stringify() method. Parameters: The body parameter is the body that is to be sent in the response.

To send data as a response to a client we typically use res. send() method, and to send static files we use the res. sendFile() method. In the same way, to send JSON data, the Express module has a method res

15. How can you handle file upload ?

To handle file uploads in Express. js, you can use middleware such as Multer, a Node. js middleware used for handling multipart/form-data, which is mainly used for file uploads.

16. Difference between app.get() and app.use() : -

app. use → It is generally used for introducing middlewares in your application and can handle all type of HTTP requests. app. get → It is only for handling GET HTTP requests.

app. get is called when the HTTP method is set to GET, whereas app. use is called regardless of the HTTP method, and therefore defines a layer which is on top of all the other RESTful types which the express packages gives you access to.

17. How can you set response header ?

Select the web site where you want to add the custom HTTP response header. In the web site pane, double-click HTTP Response Headers in the IIS section. In the actions pane, select Add. In the Name box, type the custom HTTP header name

We can use the set method to set response headers before sending a response. app. listen(3000); Then when we make a request to / , we get that the Content-Length header is set to 100 and the Content-Type is set to text/plain .

18. Purpose of app.locals object : -

The app. locals object defines the properties that are local variables inside an application. Once the value of app. locals property is set, it persists throughout the life of the application

19. how can you implement session management ?

You can install and configure these middleware options using npm . Once installed, we can require it in our Node. js application and configure it as follows: const express = require('express'); const session = require('express-session'); const app = express(); app.

20. how can you handle cors ?

Cross-origin resource sharing (CORS) allows AJAX requests to skip the Same-origin policy and access resources from remote hosts.

The easiest way to get CORS working in Express is by using the cors npm module. That's it. CORS is now enabled. The Access-Control-Allow-Origin header determines which origins are allowed to access server resources over CORS (the \* wildcard allows access from any origin).

You need to configure the server to only allow one origin to serve, and block all the others. Using the same cors Node library, here's how you would do it: const cors = require('cors') const corsOptions = { origin: 'https://yourdomain.com', } app. get('/products/:id', cors(corsOptions), (req, res, next) => { //... })

21. Route prefix : -

A prefix is found within the routing table and composes part of the route. A route is a particular entry in the routing table. A route is composed of a prefix, and either a next hop IP, an exit interface, or both.

22. How can you implement rate limiting ?

**To set up a rate limiter, we need to define two parameters:**

- The consumer ID: It is the unique identifier associated with a client consuming our API. The IP address is the most used, and we will use it in our case.
- Request per window: The maximum number of requests to execute in a specific timeframe.

Express Rate Limit: Rate limiting prevents the same IP address from making too many requests that will help us prevent attacks like brute force. Required Dependency: npm install express-rate-limit. Project Setup: Run the following sets of commands to create a folder and initialize the project.

**This approach to rate limiting is easy to build in a NodeJS-Express app, with just a few steps.**

- Step 1: Setting Up a Development Environment. First, you'll need to create and initialize an Express application. ...
- Step 2: Creating an Express Application. ...
- Step 3: Creating Route Handlers. ...
- Step 4: Implementing Rate Limiting.
23. Purpose of view engine : -

View engines allow us to render web pages using template files. These templates are filled with actual data and served to the client. There are multiple view engines, the most popular of which is Embedded Javascript (EJS).

The Express application generator uses Jade as its default, but it also supports several others. See Template Engines (Express wiki) for a list of template engines you can use with Express. See also Comparing JavaScript Templating Engines: Jade, Mustache, Dust and More. Note: Jade has been renamed to Pug.

24. how can you handle redirects ?

The res. redirect() method in ExpressJS can be used to execute a redirect. The client is given navigation instructions by this function, which accepts a URL as a parameter.

ExpressJS provides the facility to redirect to any URL with any status code. By default, the status code is set to 302. We can change the status code in the res. redirect() function by passing the new status code as the first parameter.

25. How can you access request headers ?

In express, we can use request. headers['header-name'], For example if you have set up a Bearer token in authorization header and want to retrieve the token, then you should write req. headers['authorization'], and you will get the string containing 'Bearer tokenString'.

26. how can you enable compression ?

you can use the module in your application after you initialize your server, like with Express. js: const compression = require('compression'); const express = require('express'); const app = express(); // compress all responses app. use(compression()); app

Compression encodes information into a smaller size than the original, decreasing the bandwidth usage of an application and providing faster download speeds for clients.

27. Purpose of app.route method : -

The app. route() function returns an instance of a single route, which you can then use to handle HTTP verbs with optional middleware. Use app. route() to avoid duplicate route names (and thus typo errors)

28. how can you implement input validation ?

**How to Validate and Sanitize an ExpressJS Form**

- Install the express-validator library for use with an ExpressJS server.
- Validate user input from a login form.
- Sanitize user input from a login form.
- Return validation errors to the user to improve the UX.

Steps to use express-validator to implement the logic:

Install express-validator middleware. Create a validator. js file to code all the validation logic. Validate input by validateInputField: check(input field name) and chain on the validation equals() with '

29. How do you handle cookies : -

**Express.js Cookies Example**

- var express = require('express');
- var cookieParser = require('cookie-parser');
- var app = express();
- app.use(cookieParser());
- app.get('/cookieset',function(req, res){
- res.cookie('cookie\_name', 'cookie\_value');
- res.cookie('company', 'javatpoint');
- res.cookie('name', 'sonoo');

var cookieSession = require('cookie-session') var express = require('express') var app = express() app. use(cookieSession({ name: 'session', keys: ['key1', 'key2'] })) // Update a value in the cookie so that the set-cookie will be sent. // Only changes every minute so that it's not sent with every request.

30. How do you implement Caching : -

**Create an Express Node JS application**

- npx express expressNodeCaching --hbs. BASIC.
- npm i. Bash.
- npm i node-cache npm i isomorphic-fetch. Bash.
- app.use('/getCached', require('./routes/getCached')); Bash.
- new nodecache({ stdTTL : 3599}); BASIC.
- npm start. BASIC.
31. Concept of view rendering : -

The function used to render an HTML view and to send the rendered HTML data to the client is known as the res. render() function. In Express, this function has two parameters in it, that are, Locals: It is an object whose properties would define the view. Callback: A callback function as an optional parameter.

Express has two methods to render views: app. render() , which is used to render the view and then pass the HTML to a callback function, and the more common res. render() , which renders the view locally and sends the HTML as a response.

32. How can you implement logging ?

**Process a User Login Form with ExpressJS**

- Create an example HTML login form.
- Set up GET routes using ExpressJS.
- Set up a POST route to get form data into Node.
- Learn about route paths and handlers.

morgan middleware

The morgan middleware can be used as many times as needed, enabling combinations like: Log entry on request and one on response. Log all requests to file, but errors to console.

33. How can you handle async await : -

Async/Await is used to work with promises in asynchronous functions. It is basically syntactic sugar for promises. It is just a wrapper to restyle code and make promises easier to read and use. It makes asynchronous code look more like synchronous/procedural code, which is easier to understand. To use async/await, you need to use the async keyword when you define a request handler. (Note: These request handlers are also called “controllers”. I prefer calling them request handlers because “request handlers” is more explicit). Once you have the async keyword, you can await something immediately in your code

34. Purpose of express.router() : -

The express. Router() function is used to create a new router object. This function is used when you want to create a new router object in your program to handle requests. Multiple requests can be easily differentiated with the help of the Router() function in Express.

35. Websocket communication : -

WebSocket is a full-duplex, bidirectional protocol as opposed to HTTP. Since it is a stateful protocol, it will maintain a connection between the client and server until one of them decides to break it. Because the connection is constant, real-time communication between the client and the server is possible

To open a websocket connection, we need to create new WebSocket using the special protocol ws in the url: let socket = new WebSocket ( "ws://javascript.info" ) ; There's also encrypted wss:// protocol. It's like HTTPS for websockets.

In theory, a server can handle up to 65,536 sockets per single IP address.

36. Input sanitizer : -

Input Sanitization with Validator.

Validator. js is a library that provides various string validation and sanitization functions. We can leverage it to sanitize user input and remove potentially harmful characters. // Example: Sanitizing user input with Validator.js const validator = require('validator'); app.

**How to Validate and Sanitize an ExpressJS Form**

- Install the express-validator library for use with an ExpressJS server.
- Validate user input from a login form.
- Sanitize user input from a login form.
- Return validation errors to the user to improve the UX.
37. RBAC : -

Role-based access control (RBAC) is a security approach that restricts network access and assigns permissions to users based on their role within an organization

**How to Implement RBAC in 8 Steps**

- Audit your current status. The first thing you need to do is audit your current status. ...
- Define roles. ...
- Query-level implementation. ...
- Interface-level implementation. ...
- Component-level implementation. ...
- Testing roles and implementation. ...
- Role assignment. ...
- Monitoring and auditing.
38. Session timeout : -

The session timeout determines the time a user can remain idle before the session is terminated and the user must log in again. The session time out includes administrators logged in through the portal service.

To expire the session after 1 min of inactivity in the express-session of Express. js we use expires: 60000 in the middleware function.

listen() to make sure our server is running. Here we set different options in session. In the cookie. maxAge is used to determine the specific time after which the session expires due to inactivity, and the secret is used to store the secret key for the session.

39. SSR : -

Server-side rendering (SSR) is a popular technique for rendering a normally client-side-only single-page app (SPA) on the server and then sending a fully rendered page to the client. The client's JavaScript bundle can then take over and the SPA can operate as normal.

With server-side rendering, you need a server side application which handles the initial rendering of your React application. The server application will import your React applications root component and render it into a HTML document which is then returned to the client.

40. Throttling : -

Throttling is the process of limiting the number of requests you (or your authorized developer) can submit to a given operation in a given amount of time.

Throttling is often used to manage API traffic and prevent overloading—by ensuring that a server can handle requests from multiple clients without slowing down or crashing.

41. Api versioning : -

API versioning is a crucial aspect of developing and maintaining RESTful APIs, as it allows developers to introduce new features, fix bugs, and make changes without breaking the existing functionality for clients.

**There are 5 main ways to version REST APIs:**

- Versioning using URI Path. URI Path versioning strategy puts the version number in the path of the URI. ...
- Versioning using Query Parameters. ...
- Versioning using Custom Request Headers. ...
- Versioning via Media type. ...
- Versioning using multiple strategies.
42. Pagination : -

Pagination is where a user can use links such as “next”, “previous”, and page numbers to navigate between pages that display one page of results at a time. Pagination in Node. js involves splitting a large dataset into smaller chunks, known as pages, and displaying them one page at a time.

After installing the express and mongoose packages, we can build a primary express server and connect to our MongoDB database, gradually making the pagination. const express = require("express"); const mongoose = require("mongoose"); const app = express(); mongoose . connect("mongodb://localhost:27017/pgtest")

43. Can WebSocket and HTTP run on same port?

Nginx will let you receive both your HTTP and websocket traffic on a single domain and port, and then forward each one on to the correct app. It can do this because websockets starts out as a regular HTTP GET request

44. SSE : -

Server-Sent Events (SSE) is a Web standard that allows a server application to send data to the client. Concretely, a browser can subscribe to a stream of events generated by a server, receiving updates whenever a new event occurs. This feature makes it possible to build a more reactive application

The server-sent events streaming can be started by the client's GET request to Server. Accept: text/event-stream indicates the client waiting for event stream from the server, Cache-Control: no-cache indicates that disabling the caching and Connection: keep-alive indicates the persistent connection.

45. how do you handle file download ?

download() function which takes two parameters the path of the file and a function to handle if any error occurs. Downloading multiple files as a zipped folder for this we would use the “express-zip” npm package which creates a zipped folder using the zip() function which takes an array of objects as a parameter.

46. Convert json int string : -

The JSON.stringify() static method converts a JavaScript value to a JSON string, optionally replacing values if a replacer function is specified or optionally including only the specified properties if a replacer array is specified

47. Create http server using express : -

const express = require('express')

const app = express()

const port = 3000

app.get('/', (req, res) => {

res.send('Hello World!')

})

app.listen(port, () => {

console.log(`Example app listening on port ${port}`) })

48. Templates : -

Template engine is a part of Express that enables us to use static files in our applications. Template engine converts variables to values and changes the template to HTML files to send to the client. The default template engine of Express is Jade, but EJS is the most commonly used engine

**—MONGO-DB—**

1. WHAT IS MONGODB ?

MongoDB is built on a scale-out architecture that has become popular with developers of all kinds for developing scalable applications with evolving data schemas. As a document database, MongoDB makes it easy for developers to store structured or unstructured data. It uses a JSON-like format to store documents.

2. Features : -
- Support ad hoc queries. ...
- Indexing. ...
- Replication. ...
- Duplication of data. ...
- Load balancing. ...
- Supports map reduce and aggregation tools.
- Uses JavaScript instead of Procedures.
- It is a schema-less database written in C++.
3. Advantage and disadvantage : -
- Advantages of MongoDB. Performance Levels. High Speed and Higher Availability. Simplicity. Easy Environment and a Quick Set-up. Flexibility. Sharding. Scalability. ...
- Disadvantages of MongoDB. Transactions. Joins. Indexing. Limited Data Size and Nesting. Duplicates. High Memory Usage.
4. What is a document ?

A record in MongoDB is a document, which is a data structure composed of field and value pairs. MongoDB documents are similar to JSON objects. The values of fields may include other documents, arrays, and arrays of documents.

5. Collection : -

A collection is a grouping of MongoDB documents. Documents within a collection can have different fields. A collection is the equivalent of a table in a relational database system. A collection exists within a single database.

6. Replica set : -

A replica set in MongoDB is a group of mongod processes that maintain the same data set. Replica sets provide redundancy and high availability, and are the basis for all production deployments. This section introduces replication in MongoDB as well as the components and architecture of replica sets.

7. Primary replica set : -

The primary is the only member in the replica set that receives write operations. MongoDB applies write operations on the primary and then records the operations on the primary's oplog. Secondary members replicate this log and apply the operations to their data sets.

You can force a replica set member to become primary by giving it a higher members[n]. priority value than any other member in the set. Optionally, you also can force a member never to become primary by setting its members[n]. priority value to 0 , which means the member can never seek election as primary.

8. Secondary replica set : -

A secondary maintains a copy of the primary's data set. To replicate data, a secondary applies operations from the primary's oplog to its own data set in an asynchronous process. [1] A replica set can have one or more secondaries.

9. Replica set oplog : -

The oplog (operations log) is a special capped collection that keeps a rolling record of all operations that modify the data stored in your databases. Unlike other capped collections, the oplog can grow past its configured size limit to avoid deleting the majority commit point .

10. Sharding : -

Sharding is a method for distributing data across multiple machines. MongoDB uses sharding to support deployments with very large data sets and high throughput operations. Database systems with large data sets or high throughput applications can challenge the capacity of a single server.

11. What is the difference between sharding and partitioning in MongoDB?

    Sharding and partitioning are both about breaking up a large data set into smaller subsets. The difference is that sharding implies the data is spread across multiple computers while partitioning does not. Partitioning is about grouping subsets of data within a single database instance.

12. Indexing : -

Indexes are data structures that support the efficient execution of queries in MongoDB. They contain copies of parts of the data in documents to make queries more efficient. Without indexes, MongoDB must scan every document in a collection to find the documents that match each query.

13. Types of indexing : -
1. **Single field Index:** A single field index means index on a single field of a document. This index is helpful for fetching data in ascending as well as descending order.
1. **Compound Index:** This is a user-defined index supported in MongoDB where multiple fields can be indexed. To create a compound index, the query is db.collection.createIndex( { <fieldname1: 1/-1, fieldname2: 1/-1, … }). Here, the compound index query is similar to a normal index query but with multiple fields.
1. **MultiKey Indexing:** Now this is one indexing that works on values stored in an array. Here, for each element in an array, MongoDB creates an index.
1. **Text Indexing:** For the purpose of searching the string content or an array of string, ina collection, indexing over the test is supported in MongoDB.
1. **Hashed Index:** Using the hashes of the indexed fields’ values, Hashed Indexing in MongoDB is achieved. MongoDB also supports sharding based on the hash. The aim is to reduce the size of the index. Range queries are not supported here.
14. Mapreduce : -

Map-reduce is a data processing paradigm for condensing large volumes of data into useful aggregated results. To perform map-reduce operations, MongoDB provides the mapReduce database command.

MapReduce is a programming model and an associated implementation for processing and generating big data sets with a parallel, distributed algorithm on a cluster.

15. Aggregation and aggregation pipeline : -

Aggregation is a way of processing a large number of documents in a collection by means of passing them through different stages. The stages make up what is known as a pipeline. The stages in a pipeline can filter, sort, group, reshape and modify documents that pass through the pipeline.

The aggregation pipeline refers to a specific flow of operations that processes, transforms, and returns results. In a pipeline, successive operations are informed by the previous result. Let's take a typical pipeline: Input -> $match -> $group -> $sort -> output.

Aggregation operations allow you to group, sort, perform calculations, analyze data, and much more. Aggregation pipelines can have one or more "stages". The order of these stages are important. Each stage acts upon the results of the previous stage.

16. Update vs save : -

MongoDB's update() and save() methods are used to update document into a collection. The update() method updates the values in the existing document while the save() method replaces the existing document with the document passed in save() method.

17. gridFs : -

GridFS is the MongoDB specification for storing and retrieving large files such as images, audio files, video files, etc. It is kind of a file system to store files but its data is stored within MongoDB collections. GridFS has the capability to store files even greater than its document size limit of 16MB.

18. Primary vs secondary key : -

A primary key is the field in a database that is the primary key used to uniquely identify a record in a database. A secondary key is an additional key, or alternate key, which can be use in addition to the primary key to locate specific data.

19. how does mongodb ensure data consistency ?

If the primary member fails, MongoDB preserves consistency by suspending writes until a new primary is elected. Any writes to the failed primary that have not been replicated are rolled back when it returns to the cluster as a secondary.

MongoDB allows multiple clients to read and write the same data. To ensure consistency, MongoDB uses locking and concurrency control to prevent clients from modifying the same data simultaneously. Writes to a single document occur either in full or not at all, and clients always see consistent data.

20. how does mongodb ensure high availiability of data ?

Replication is performed in MongoDB to maintain data redundancy and high availability. It is performed by creating multiple copies of your data across multiple servers. Replication is achieved by the replica sets that contain primary and secondary nodes.

21. how does mongodb handle schema changes ?

You can use MongoDB's flexible schema model, which supports differently shaped documents in the same collection, to gradually update your collection's schema. As you update your schema model, the Schema Versioning pattern allows you to track these updates with version numbers.

22. How transactions are handled in MongoDB?

Transactions use the transaction-level write concern to commit the write operations. Write operations inside transactions must be issued without explicit write concern specification and use the default write concern. At commit time, the writes are then commited using the transaction-level write concern.

The locks in MongoDB are acquired at the transaction level. However only write operations will lock the associated document. Read operations will not lock them. Hence the locks will be released only when the transaction is completed.

23. Role of mongodb process : -

MongoDB grants access to data and commands through role-based authorization and provides built-in roles that provide the different levels of access commonly needed in a database system. You can additionally create user-defined roles. A role grants privileges to perform sets of actions on defined resources.

What is the role of the Mongod process in MongoDB?

mongod is the primary daemon process for the MongoDB system. It handles data requests, manages data format, and performs background management operations. This document provides a complete overview of all command line options for mongod . These options are primarily useful for testing purposes.

24. Role of mongodb shell : -

The mongo shell is an interactive JavaScript interface to MongoDB. You can use the mongo shell to query and update data as well as perform administrative operations.

25. Role of mongodb handle security : -

MongoDB offers built-in security controls for all your data – with databases managed in a customer environment or MongoDB Atlas, a fully-managed cloud service. MongoDB enables enterprise-grade security features and simplifies deploying and managing your databases.

**MongoDB Security Best Practices**

- Create Separate Security Credentials. To enable authentication, create login credentials for each user or process that accesses MongoDB. ...
- Use Role-Based Access Control. ...
- Encrypt Your Data. ...
- Use the Official MongoDB Packages. ...
- Auditing and Logs. ...
- Apply MongoDB Security Fixes.
26. Join vs lookup : -

MongoDB Joins are performed by Lookup. It performs a Left Outer Join to two or more Collections. But Lookup is only permitted in Aggregate operations. This is like a pipeline that performs query, filter and group operations.

Generaly, sorted joiner is more effective on flat files than lookup, because sorted joiner uses merge join and cashes less rows. Lookup cashes always whole file. If the file is not sorted, it can be comparable.

27. Backup and recovery : -

The MongoDB Backup and Restore Tool allows you to encapsulate the state of a cluster and return to that state at any time. This helps protect you from data loss, as you can restore a database to a MongoDB instance using a created copy of that instance.

- [Step 1: Create Direct Backups Using Mongodump](https://hevodata.com/learn/mongodump/#Step1)
- [Step 2: Backup a Remote MongoDB Instance](https://hevodata.com/learn/mongodump/#Step2)
- [Step 3: Backup a Secure MongoDB Instance](https://hevodata.com/learn/mongodump/#Step3)
- [Step 4: Select Databases & Collections](https://hevodata.com/learn/mongodump/#Step4)
- [Step 5: Change the Backup Directory](https://hevodata.com/learn/mongodump/#Step5)
- [Step 6: Create an Archive File](https://hevodata.com/learn/mongodump/#Step6)
- [Step 7: Compress the MongoDB Backup](https://hevodata.com/learn/mongodump/#Step7)
- [Step 8: Restore Database](https://hevodata.com/learn/mongodump/#Step8)

●

28. Some alternative of mongodb : -

Some of the best MongoDB alternatives include Redis, Apache Cassandra, RethinkDB, DynamoDB, OrientDB, CouchDB, and ArangoDB.

29. How does mongodb store data ?

MongoDB stores data objects in collections and documents instead of the tables and rows used in traditional relational databases. Collections comprise sets of documents, which are equivalent to tables in a relational database. Documents consist of key-value pairs, which are the basic unit of data in MongoDB.

30. how mongodb different from sql and better than mysql:

MongoDB is a more dynamic and complicated choice that is appropriate for hierarchical data because of its fundamental properties, as opposed to a SQL Database, which is still more predetermined and appropriate for other types of data storage. Hence this is the reason MongoDB outshines the SQL database.

Compared to MySQL, MongoDB is easier to work with. Since there is no need to define schemas beforehand, it gives a chance to users with minimal technical knowledge to immediately start storing data in it. You can use the database with various programming languages, including C, C# and .

31. Different data models : -

MongoDB provides two types of data models: — Embedded data model and Normalized data model.

32. Horizontal and vertical scaling : -

Horizontal scaling involves adding additional servers and partitioning the system dataset and load over those servers. Vertical scaling involves expanding the resources used by a single server/replica set.

33. Replication and sharding : -

In simple terms, MongoDB replication is the process of creating a copy of the same data set in more than one MongoDB server. This can be achieved by using a Replica Set. A replica set is a group of MongoDB instances that maintain the same data set and pertain to any mongod process.

Replication can be simply understood as the duplication of the data-set whereas sharding is partitioning the data-set into discrete parts. By sharding, you divided your collection into different parts. Replicating your database means you make imagers of your data-set.1

34. What is the \_id field type in MongoDB?

Architecturally, by default the \_id field is an ObjectID, one of MongoDB's BSON types. The ObjectID is the primary key for the stored document and is automatically generated when creating a new document in a collection

35. what are some utilities for backup and restoring ?

MongoDB supplies two utilities to manage logical backups: Mongodump and Mongorestore. The Mongodump command dumps a backup of the database into the “. bson” format, and this can be restored by providing the logical statements found in the dump file to the databases.

36. Role of profiler : -

The database profiler collects detailed information about Database Commands executed against a running mongod instance. This includes CRUD operations as well as configuration and administration commands. The profiler writes all the data it collects to a system.

37. can we use regular expression in mongodb ?

MongoDB provides the functionality to search a pattern in a string during a query by writing a regular expression. A regular expression is a generalized way to match patterns with sequences of characters. MongoDB uses Perl compatible regular expressions(PCRE) version 8.42 along with UTF-8 support.

38. difference between $all and $in operator : -

$all operator retrieves all the documents which contains the subset of the values we pass. The subset might be in any order. $in operator retrieves all the documents which contains the either of the values we pass.

$all operator retrieves all the documents which contains the subset of the values we pass. The subset might be in any order. $in operator retrieves all the documents which contains the either of the values we pass.

The $in operator is used to select documents in which the field's value equals any of the given values in the array. You can use this operator in methods like find(), update(), etc., according to your requirements.

39. Add more slaves to replica : -
- Prepare the Data Directory: This is about creating a data directory for the new member and manually copying data to it from an existing member.
- Add a Member to an Existing Replica Set: 2.1 Start the new member's mongod instance, pointing to the new data directory. 2.2 Connect to the replica-set's primary.

●

40. Some application of mongodb : -

It is used to store a massive amount of demographic and biometric data. For example, India's Unique Identification project, Aadhar is using MongoDB as its database to store a massive amount of demographic and biometric data of more than 1.2 billion Indians.

41. What is mongoose ?

Mongoose is a MongoDB ODM i.e (Object database Modelling) that used to translate the code and its representation from MongoDB to the Node. js server. Advantages of Mongoose module: Collection validation of the MongoDB database can be done easily.

MongoDB is a document-oriented NoSQL database, while Mongoose is an Object Data Modeling (ODM) library for Node. js that provides a higher-level abstraction layer on top of MongoDB, allowing developers to define data models using a schema-based approach.

42. Mongodb function : -

A MongoDB Function can be used to read, insert, update, or delete data from your MongoDB database. When you connect your database to Internal, basic functions corresponding to each collection in your database are automatically generated for you.

43. which mongodb api to use ?

The MongoDB Data API can be used to query and update data in a MongoDB database without the need for language specific drivers. Language drivers should be used when possible, but the MongoDB Data API comes in handy when drivers are not available or drivers are overkill for the application.

MongoDB RESTful API is simple to set up and allows you to store and retrieve documents, making it great for Unstructured Data.

44. What is storage engine ?

The storage engine is the component of the database that is responsible for managing how data is stored, both in memory and on disk. MongoDB supports multiple storage engines, as different engines perform better for specific workloads.

45. Skip () : -

MongoDB skip() is used when we required a certain number of results after a certain number of documents simultaneously we have use skip method in MongoDB. If we want to skip a certain number of documents from the collection, skip method will skip the specified documents that we have used with the MongoDB skip method

46. Text search : -

For self-managed (non-Atlas) deployments, MongoDB's text search capability supports query operations that perform a text search of string content. To perform text search, MongoDB uses a text index and the $text operator.

47. Command syntax : -

To run a command against the current database, use db.runCommand() : db. runCommand( { <command> } ) To run an administrative command against the admin database, use db.adminCommand() : db.

What is the syntax of find command in MongoDB? Syntax: db. collection\_name. find(query, projection)

48. How does NoSQL DB budget memory?

Ans: The Replication Node manages the data in a NoSQL DB store and is the main consumer of memory. The Java heap and cache size used by the Replication Node can be important performance factor

49. Syntax to create drop collection : -

**First, check the available collections into your database mydb.**

- >use mydb switched to db mydb >show collections mycol mycollection system. indexes tutorialspoint > Now drop the collection with the name mycollection.
- >db. mycollection. drop() true > ...
- >show collections mycol system. indexes tutorialspoint >

●

Use of Drop Collection in MongoDB

To remove a collection completely, use the db. collection. drop() method and drop the entire collection, including the indexes and then reuse the collection.

50. Store capacity in a single mongodb document : -

The maximum size an individual document can be in MongoDB is 16MB with a nested depth of 100 levels.

We often need to store files in our databases, but mongoDB doesn't let you store any file larger than 16 Mb in a normal document. Instead, MongoDB has a functionality specifically for storing large files and it goes by the name GridFS. GridFS divides the file into chunks and then stores them in the database.

51. BSON : -

BSON, or Binary JSON, is the data format that MongoDB uses to organize and store data. This data format includes all JSON data structure types and adds support for types including dates, different size integers, ObjectIds, and binary data.

52. Supported datatypes in mongodb : -
- String. One of the most basic and widely used data types is the string. ...
- Integer. Numeric values are stored using the integer data type. ...
- Double. Numeric numbers containing 8 bytes (64-bit IEEE 754 floating point) floating-point are stored using the double data type. ...
- Boolean. ...
- Array. ...
- Object. ...
- Date. ...
- Timestamp.
- Null
- Binary
53. pretty() method : -

pretty() method is used to configure the cursor to display results in an easy-to-read format. Syntax: cursor.pretty() The pretty() method has the following prototype form: db.collection.find(<query>).pretty()

54. is mongodb supported foreign key and primary key relationship ?

    No. MongoDB doesn't support primary key-foreign key relationship. MongoDB has \_id key field for every document that uniquely identifies the particular document.

55. CURD : -

The basic methods of interacting with a MongoDB server are called CRUD operations. CRUD stands for Create, Read, Update, and Delete. These CRUD methods are the primary ways you will manage the data in your databases.

56. difference between insert, insertone and insertmany in mongodb ?

    With insertOne you can insert one document into the collection. insertMany accepts an array of documents and these are inserted. The insert (the method from older versions) takes a single document by default, and there is an option to insert multiple documents supplied as an array.

57. How to display all the element ?

To obtain a list of MongoDB collections, we need to use the Mongo shell command show collections . This command will return all collections created within a MongoDB database.

58. Bulk write operation : -

Bulk write operations affect a single collection. MongoDB allows applications to determine the acceptable level of acknowledgement required for bulk write operations. The db. collection. bulkWrite() method provides the ability to perform bulk insert, update, and delete operations.

59. Set () : -

The $set operator replaces the value of a field with the specified value. The $set operator expression has the following form: { $set: { <field1>: <value1>, ... } } To specify a <field> in an embedded document or in an array, use dot notation.

60. Does MongoDB support collection joins?

Join Collections

MongoDB is not a relational database, but you can perform a left outer join by using the $lookup stage. The $lookup stage lets you specify which collection you want to join with the current collection, and which fields that should match.

61. how relationship maintained in mongodb ?

In MongoDB, one-to-one, one-to-many, and many-to-many relations can be implemented in two ways: Using embedded documents. Using the reference of documents of another collection.

62. model one to one relationship in mongodb : -

In this one-to-one relationship between patron and address data, the address belongs to the patron . In the normalized data model, the address document contains a reference to the patron document. With the embedded data model, your application can retrieve the complete patron information with one query.

63. Model one to many relationship in mongodb : -

We can also perform a one-to-many relationship using the document reference model. In this model, we maintain the documents separately but one document contains the reference of the other documents. Now retrieving data from these different documents is cumbersome.

64. Different ways to model tree structure with mongodb : -
- Model Tree Structures with Parent References.
- Model Tree Structures with Child References.
- Model Tree Structures with an Array of Ancestors.
- Model Tree Structures with Materialized Paths.
- Model Tree Structures with Nested Sets.

**Creating a tree node**

- Find parent node document to get the "ancestors" for our new node.
- Save the id of parent node and ancestor nodes when adding a new node.
- Add the id of the new node to the parent node's children field.

●

64. limit() : -

In MongoDB, the limit() method limits the number of records or documents that you want. It basically defines the max limit of records/documents that you want. Or in other words, this method uses on cursor to specify the maximum number of documents/ records the cursor will return.

65. Sort () : -

MongoDB can perform sort operations on a single-field index in ascending or descending order. In compound indexes, the sort order determines whether the index can be sorted. The sort keys must be listed in the same order as defined in the index.

66. Create index : -

Indexes support efficient execution of queries in MongoDB. If your application is repeatedly running queries on the same fields, you can create an index on those fields to improve performance for those queries. To create an index, use the createIndex() shell method or equivalent method for your driver.

67. Mongodb projection : -

MongoDB projection is a powerful tool that can be used to extract only the fields you need from a document—not all fields. It enables you to: Project concise and transparent data. Filter the data set without impacting the overall database performance

68. which index is created by mongodb in every collection ?

    \_id index

    MongoDB creates a unique index on the \_id field during the creation of a collection. The \_id index prevents clients from inserting two documents with the same value for the \_id field.

69. component of sharded cluster in mongodb : -

A sharded cluster in MongoDB is a collection of datasets distributed across many shards (servers) in order to achieve horizontal scalability and better performance in read and write operations. Sharding is very useful for collections that have a lot of data and high query rates.

- Sharded Cluster Components. Shards. ...
- Shard Keys.
- Hashed Sharding. Deploy Sharded Cluster using Hashed Sharding.
- Ranged Sharding. Deploy Sharded Cluster using Ranged Sharding.
- Tag Aware Sharding. Manage Shard Tags. ...
- Data Partitioning with Chunks. Create Chunks in a Sharded Cluster. ...
- Balancer. ...
- Administration.
70. Shard key : -

The shard key is either a single indexed field or multiple fields covered by a compound index that determines the distribution of the collection's documents among the cluster's shards.

71. Accumulator operator : -

Accumulators are operators that maintain their state (e.g. totals, maximums, minimums, and related data) as documents progress through the pipeline. Use the $accumulator operator to execute your own JavaScript functions to implement behavior not supported by the MongoDB Query Language.

72. What is the use of $project in MongoDB?

The $project takes a document that can specify the inclusion of fields, the suppression of the \_id field, the addition of new fields, and the resetting of the values of existing fields. Alternatively, you may specify the exclusion of fields.

73. What is the use of $match in MongoDB ?

$match. Filters the documents to pass only the documents that match the specified condition(s) to the next pipeline stage.

What is the use of match in mongoose?

match() function of the Mongoose API is used to find the existing documents in the database that matches the conditions mentioned in the arguments of the API.

74. Why is &group used in MongoDB?

$group. The $group stage separates documents into groups according to a "group key". The output is one document for each unique group key. A group key is often a field, or group of fields.

We are also using the group method to group the documents in MongoDB. Using the group method we are grouping by two or multiple field in MongoDB. Group method will accept the single document from the collection. Basically group method is similar to group by clause which was used in other SQL databases.

75. What is the use of $unwind in MongoDB ?

The $unwind operator in MongoDB is used to deconstruct an array field into multiple documents. It creates a new document for each element in the array, effectively "unwinding" the array.

76. What is the use of $lookup in MongoDB ?

$lookup performs an equality match on the localField to the foreignField from the documents of the from collection. If an input document does not contain the localField , the $lookup treats the field as having a value of null for matching purposes.

77. feature to do safe backup in MongoDB : -

In general, if using filesystem based backups for MongoDB Enterprise 4.2+, use the "hot" backup feature, if possible. For MongoDB Enterprise versions 4.0 and earlier, if you use AES256-GCM encryption mode, do not make copies of your data files or restore from filesystem snapshots ("hot" or "cold").

MongoDB Backup and Restore Best Practices

MongoDB uses both regular JSON and Binary JSON (BSON) file formats. It's better to use BSON when backing up and restoring. While JSON is easy to work with, it doesn't support all of the data types that BSON supports, and it may lead to the loss of fidelity.

78. What is the backup method of MongoDB?

**MongoDB Backup Methods**

- Back Up with Atlas.
- Back Up with MongoDB Cloud Manager or Ops Manager.
- Back Up by Copying Underlying Data Files.
- Back Up with mongodump.
79. What is configuration in MongoDB?

The MongoDB configuration file contains settings that are equivalent to the command-line options mongod and mongos. Using a MongoDB configuration file simplifies the management of mongod and mongos options, especially in large-scale deployments.

80. Use of Ops manager : -

Ops Manager is the self-hosted management platform that enables you to deploy, monitor, back up, and scale MongoDB on your own infrastructure. Identify issues before they become emergencies and streamline operations.

- Configure Deployment to Have Limited Internet Access. ...
- Enable Backing Database Monitoring.
- Deploy a Highly Available Application.
- Deploy Highly Available Backups.
- Configure Ops Manager to Monitor Large Deployments.
- Assign Snapshot Stores to Specific Data Centers.
- Pass Outgoing Traffic through HTTP Proxy.

*THANK YOU -*
