---
title: Important JS-REACT-NEXT question
excerpt: Javascript,react and next-js is the most important programming language. for frontend development. You probably don't know it well enough!
image: frontend.png
isFeatured: false
date: '2024-08-21'
---
1. Callstack : -

The call stack is used by JavaScript to keep track of multiple function calls. It is like a real stack in data structures where data can be pushed and popped and follows the Last In First Out (LIFO) principle. We use call stack for memorizing which function is running right now.

View the Call Stack

This is useful when you have a lot of asynchronous functions, and you want to track the changes to the call stack while debugging an error. To view the call stack, open DevTools Sources panel and on the right panel, expand the Call Stack panel to see all the current functions in the call stack.

2. Hoisting : -

In JavaScript, hoisting allows you to use functions and variables before they're declared.

By default, in JavaScript, Hoisting entails moving all declarations to the top of the scope before executing the code.

3. Function : -

function is a "subprogram" that can be called by code external (or internal, in the case of recursion) to the function.

**Types of functions in javascript?**

- Named function.
- Anonymous function.
- Immediately invoked function expression. It runs as soon as the browser finds it.
4. Scope : -

A scope can be defined as the region of the execution, a region where the expressions and values can be referenced. There are two scopes in JavaScript that are global and local: Global Scope: In the global scope, the variable can be accessed from any part of the JavaScript code.

5. Let , var, const : -

var declarations are globally scoped or function scoped while let and const are block scoped. var variables can be updated and re-declared within its scope; let variables can be updated but not re-declared; const variables can neither be updated nor re-declared. They are all hoisted to the top of their scope.

6 Closures : -

A closure is a feature of JavaScript that allows inner functions to access the outer scope of a function. Closure helps in binding a function to its outer boundary and is created automatically whenever a function is created. A block is also treated as a scope since ES6.

7. Set timeout : -

The setTimeout() method calls a function after a number of milliseconds.

1 second = 1000 milliseconds.

The setTimeout() is executed only once

If you need repeated executions, use setInterval() instead Use the clearTimeout() method to prevent the function from starting.

8. Anonymous function : -

It is a function that does not have any name associated with it. Normally we use the function keyword before the function name to define a function in JavaScript, however, in anonymous functions in JavaScript, we use only the function keyword without the function name.

9. Promises , async & await : -

Async/Await is used to work with promises in asynchronous functions. It is basically syntactic sugar for promises. It is just a wrapper to

restyle code and make promises easier to read and use. It makes

asynchronous code look more like synchronous/procedural code, which is easier to understand.

Promise is an object representing intermediate state of operation which is guaranteed to complete its execution at some point in future. Async/Await is a syntactic sugar for promises, a wrapper making the code execute more synchronously. 2. Promise has 3 states – resolved, rejected and pending.

10. Event loop : -

The event loop is the secret behind JavaScript’s asynchronous programming. JS executes all operations on a single thread, but using a few smart data structures, it gives us the illusion of multi-threading. Let’s take a look at what happens on the back-end.

The Basics of the Event Loop

This means that only one task can be executed at a time, and any blocking operation will prevent other tasks from being executed until the blocking operation is complete. To avoid blocking, JavaScript uses an event loop to handle asynchronous operations

11. Higher order function : -

Higher order functions are functions that take one or more functions as arguments, or return a function as their result. In this article, we will delve into what a higher order function is, the benefits of using them, and how to use them in practical applications.

12. Callback function : -

A callback is a function passed as an argument to another function This technique allows a function to call another function

A callback function can run after another function has finished

A JavaScript callback is a function which is to be executed after another function has finished execution. A more formal definition would be - Any function that is passed as an argument to another function so that it can be executed in that other function is called as a callback function.

13. Callback hell : -

Callback Hell is essentially nested callbacks stacked below one another forming a pyramid structure. Every callback depends/waits for the previous callback, thereby making a pyramid structure that affects the readability and maintainability of the code.

14. Promise chaining & error handling : -

Promise Chaining is a simple concept by which we may initialize another promise inside our .then() method and accordingly we may execute our results. The function inside then captures the value returned by the previous promise.

To handle errors in Promises, use the . catch() method. If anything goes wrong with any of your promises, this method can catch the reason for that error. This time in our example, the error output is no longer 'uncaught' because of

15. Prototype : -

Every object in JavaScript has a built-in property, which is called its prototype. The prototype is itself an object, so the prototype will have its own prototype, making what's called a prototype chain. The chain ends when we reach a prototype that has null for its own prototype

All JavaScript objects inherit properties and methods from a prototype:

- Date objects inherit from Date.prototype
- Array objects inherit from Array.prototype
- Person objects inherit from Person.prototype
16. Memoization : -

Memoization is a programming technique that we used to speed up functions and it can be used to do whenever we have an expensive function ( takes a long time to execute). It relies on the idea of cache {}. A cache is just a plain object. It reduces redundant function expression calls. memoization is an optimization technique that makes

applications more efficient and hence faster. It does this by

storing computation results in cache, and retrieving that same information from the cache the next time it's needed instead of

computing it again.

17. Event bubbling & event capturing : -

The "Event Bubbling" behavior makes it possible for you to handle an event in a parent element instead of the actual element that received the event. The pattern of handling an event on an ancestor element is called Event Delegation.

Bubbling is the default behavior, where events first trigger on the target element and then bubble up to its parent and ancestor elements. Capturing, on the other hand, triggers events on the ancestor elements first before reaching the target element.

18. Data types : - (SNNUBO)

    String

    Number

    Bigint

    Boolean

    Undefined

    Null

    Symbol

    Object

    The Object Datatype

    The object data type can contain: 1. An object

19. Function declaration and function expression : -

A function expression is very similar to, and has almost the same syntax as, a function declaration. The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions.

Declarations are loaded before any code can run. Function declaration load before any code is executed while Function expressions load only when the interpreter reaches that line of code.

Similar to the var statement, function declarations are hoisted to the top of other code.

20. Cookies : -

Cookies are small pieces of text sent to your browser by a website you visit. They help that website remember information about your visit, which can both make it easier to visit the site again and make the site more useful to you.

JavaScript Cookie class

The Cookie class has three static methods: get() , set() , and remove() .

Cookies are small pieces of text sent to your browser by a website you visit. They help that website remember information about your visit

21. Imports & exports : -

With the help of ES6, we can create modules in JavaScript. In a module, there can be classes, functions, variables, and objects as well. To make all these available in another file, we can use export and import. The export and import are the keywords used for exporting and importing one or more members in a module

22. Undefined , undeclared & null : -

**Undefined:** It occurs when a variable has been declared but has not been assigned any value. Undefined is not a keyword.

**Undeclared:** It occurs when we try to access any variable that is not initialized or declared earlier using the *var* or *const keyword*. If we use *‘typeof’* operator to get the value of an undeclared variable, we will face the *runtime error* with the return value as **“undefined”**. The scope of the undeclared variables is always global.

Null: a variable is assigned a value of like any other value. Is also primitive data type in javascript and always represent the intentional absence of a value.

23. Remove duplicate from js array : -

Using filter method -

const arrayWithDuplicates = [1, 2, 2, 3, 4, 4, 5];

const uniqueArray = arrayWithDuplicates.filter((value, index, self) => {

return self.indexOf(value) === index;

});

console.log(uniqueArray); // [1, 2, 3, 4, 5]

24. Spread operator vs rest operator : -

The spread operator in JavaScript expands values in arrays and strings into individual elements, whereas the rest operator puts the

values of user-specified data into a JavaScript array.

Destructuring is used to create varibles from array items or object properties. Spread syntax is used to unpack iterables such as arrays, objects, and function calls. Rest parameter syntax will create an array from an indefinite number of values.

25. Shallow copy vs deep copy : -

In JavaScript, there are two ways to copy objects: shallow copy and deep copy. Shallow copying creates a new object with references to the same memory locations as the original object, while deep copying creates a new object with new memory locations for all of its properties and nested objects or arrays.

26. This keyword : -

In JavaScript, the this keyword refers to an object. Which object depends on how this is being invoked (used or called). The this keyword refers to different objects depending on how it is used: In an object method, this refers to the object.

The this keyword refers to the current object in a method or constructor. The most common use of the this keyword is to eliminate the confusion between class attributes and parameters with the same name (because a class attribute is shadowed by a method or constructor parameter).

27. Nan property : -

In JavaScript, NaN stands for Not a Number. It represents a value that is not a valid number. It can be used to check whether a number entered is a valid number or not a number.

- Using isNaN() method: The isNan() method is used to check whether the given number is NaN or not. ...
28. Map , filter & reduce : -

The map(), reduce() and filter() are array functions that transform the array according to the applied function and return the updated array.

map() transforms every element in an array individually and creates a new array.

filter() removes elements that are not required and creates

a new array containing the ones needed.

reduce() reduces all array elements into a single value .

29. Map & foreach : -

The map() method returns a new array, whereas the forEach() method does not return a new array. The map() method is used to transform the elements of an array, whereas the forEach() method is used to loop through the elements of an array.

30. Event handling : -

When javascript code is included in HTML, js react over these events and allow the execution. This process of reacting over the events is called Event Handling. Thus, js handles the HTML events via Event Handlers.

31. Call , apply & bind : -

What is the difference between call, apply and bind functions? The main difference between the call, apply and bind functions is that the call function immediately invokes the function it is called on, whereas the apply and bind functions return a new function that can be invoked at a later time.

**Call** is a function that helps you change the context of the

invoking function. In layperson's terms, it helps you replace the

value of this inside a function with whatever value you want.

**Apply** is very similar to the call function. The only difference is

that in apply you can pass an array as an argument list.

**Bind** is a function that helps you create another function that

you can execute later with the new context of this that is

provided.

32. For of , for in & for each : -

**for..of** loop was introduced first in Javascript ES6 version. The for…of loop iterates over the iterable objects (like Array, Map, Set, arguments object, …,etc), invoking a custom iteration hook with statements to be

executed for the value of each distinct property.

**The for...in** statements combo iterates (loops) over the properties of an object. The code block inside the loop is executed once for each property.

**The forEach()** array method loops through any array, executing a provided function once for each array element in ascending index order. This function is referred to as a callback function. Note: Arrays are collections of elements that can be of any datatype

The best use for these loops is as follows: For arrays, use for...of (or forEach ). For objects, use for...in . If you work with arrays and need access to indexes, use for or forEach .

33. “==” , “ ===” : -

The main difference between the == and === operator in javascript is that the == operator does the type conversion of the operands before comparison, whereas the === operator compares the values as well as the data types of the operands.

34. Array of object : -

The Array object lets you store multiple values in a single variable. It stores a fixed-size sequential collection of elements of the same type. An array is used to store a collection of data, but it is often more useful to think of an array as a collection of variables of the same type.

35. Classes & objects : -

Classes and Objects are basic concepts of Object Oriented Programming that revolve around real-life entities.

Classes: Classes were first introduced in the new version of the ES6 classes which replaced the previously used functions. Class is nothing but a blueprint for an object of it.

36. Built in methods : -

A JavaScript method is a property containing a function definition. In other words, when the data stored on an object is a function we call that a method.

To differenciate between properties and methods, we can think of it this way: *A property is what an object has, while a method is what an object does.*

- Useful Built-in methods
- Date
- Math
- Strings
- Arrays
- Objects
37. Document & window : -

The window is at a root/top level at the JavaScript object hierarchy. It is a global/root object in JavaScript and it is the root object of the Document object model(DOM); What is a JavaScript document? A document is an object inside the window object and we use a document object for manipulation inside the document.

38. Event capturing & event bubbling : -

Event capturing means propagation of event is done from ancestor elements to child element in the DOM while event bubbling means propagation is done from child element to ancestor elements in the DOM. The event capturing occurs followed by event bubbling.

The event needs to pass through every node on the DOM until it reaches the end, or if it is forcibly stopped. Bubbling and Capturing are the two phases of propagation. In their simplest definitions, bubbling travels from the target to the root, and capturing travels from the root to the target.

39. Strict mode : -

The "use strict" directive enables JavaScript's strict mode. JavaScript's strict mode was introduced in ECMAScript 5. It enforces stricter parsing and error handling on the code at runtime. It also helps you write cleaner code and catch errors and bugs that might otherwise go unnoticed

40. Dom : -

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

By manipulating the DOM, you have infinite possibilities. You can create applications that update the data of the page without needing a refresh. Also, you can create applications that are customizable by the user and then change the layout of the page without a refresh. You can drag, move, and delete elements.

41. Types of errors : -

There are 7 types of JavaScript errors: Syntax error, Reference Error, Type Error, Evaluation Error, RangeError, URI Error and Internal Error.

42. IIFE : -

An IIFE (Immediately Invoked Function Expression) is a function that runs the moment it is invoked or called in the JavaScript event loop. Having a function that behaves that way can be useful in certain situations. IIFEs prevent pollution of the global JS scope.

43. Temporal dead zone : -

A temporal dead zone (TDZ) is the block where a variable is inaccessible until the moment the computer initializes it with a value. A block can be defined as a pair of braces ({...}) used to accumulate multiple statements. Initialization occurs when one assigns an initial value to a variable.

44. Naming convention : -

JavaScript variables should be declared using camel case, which means that the first word in the variable name starts with a lowercase letter, and subsequent words start with an uppercase letter. This convention ensures that there aren't multiple variables with the same name, which could lead to confusion and errors.

45. Prompt box : -

A prompt box is often used if you want the user to input a value before entering a page. When a prompt box pops up, the user will have to click either "OK" or "Cancel" to proceed after entering an input value. If the user clicks "OK" the box returns the input value. If the user clicks "Cancel" the box returns null.

46. Currying : -

Currying in JavaScript transforms a function with multiple arguments into a nested series of functions, each taking a single argument. Currying helps you avoid passing the same variable multiple times, and it helps you create a higher order function

Why is currying useful in JavaScript? It helps us to create a higher-order function. It reduces the chances of error in our function by dividing it into multiple smaller functions that can handle one responsibility. It is very useful in building modular and reusable code.

**-REACT-**

1. WHAT IS REACT : -

React is a JavaScript library developed by Facebook which, among other things, was used to build Instagram.com. It aims to allow developers to create fast user interfaces for websites and applications alike easily. The main concept of React. js is virtual DOM.

2. Advantage & disadvantage : -

Advantage :

**Easy to Learn and USe**

**Creating Dynamic Web Applications Becomes Easier Reusable Components**

**Performance Enhancement**

**The Support of Handy Tools**

**Known to be SEO Friendly**

**Scope for Testing the Codes**

Disadvantage :

**The high pace of development Poor Documentation**

**View Part**

**. JSX as a barrier**

3. Role of react : -

A React developer is responsible for the design and implementation of user interfaces (UIs) and UI components using React, a front-end JavaScript library. They develop and maintain UIs for web and mobile apps.

4. Single page application (SPA) : -

React is a robust and widely-used JavaScript library for developing streamlined, interactive Single Page Applications (SPAs). Using React's fast virtual DOM and component-based design, developers can easily build sophisticated and responsive web apps

5. React vs angular : -

React is a JavaScript library, whereas Angular is a front-end framework. React uses one-way data binding and virtual DOM, whereas Angular uses two-way data binding and real DOM. Moreover, React is faster than Angular as it has a smaller bundle size

6. Real dom vs virtual dom : -

DOM is a standard technology, while virtual DOM is only one implementation in the React framework.

real dom: here any change updates the entire dom updating therefore it is slow and inefficient.

virtual dom: any change only updates the relevant in the tree updating is fast and efficient.

7. React component : -

Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML. Components come in two types, Class components and Function components

8. Npm : -

The name npm (Node Package Manager) stems from when npm first was created as a package manager for Node. js. All npm packages are defined in files called package. json. The content of package.

9. Role of node modules folder : -

In simple word node\_modules folder is the repository of modules/library which you are using inside your project. What ever you are importing in your project that module or library should present inside the node\_module folder

10. Role of public folder : -

The public folder is useful as a workaround for a number of less common cases: You need a file with a specific name in the build output, such as manifest.webmanifest . You have thousands of images and need to dynamically reference their paths. You want to include a small script like pace.js outside of the bundled code

11. Role of src folder : -

In the src folder, You can put all the js, CSS, images, components file & other assets of your projects. By default, we get the following files that are necessary to understand their usages. you can create your own files according to these files for developing your projects

12. Role of index.html page : -

public/index. html is the main HTML file of our app that includes your React code and provides a context for React to render to. If you look at the html file you could see <div id="root"></div> . We call this a “root” DOM node because everything inside it will be managed by React DOM

13. Role of app.js file : -

js is where you would usually mount/render your main react component onto your “root” element(which you mark in your html). “App” is what people tend to call the file which contains the main logic of your file, or in React case, the main component, the one that represents your entire application/web-site

14. Role of index.js file : -

Regarding React, index. js is where you would usually mount/render your main react component onto your “root” element(which you mark in your html)

15. Render method : -

We can use the ReactDOM. render() in the application using the declaration of HTML code and the HTML element. The goal of this function is to represent the imposed HTML code within the specified HTML element tags. It helps to redirect the HTML page with the help of the render() function

render() method

The render() method is the only required method in a class component. When called, it should examine this.props and this.state and return one of the following types: React elements.

16. How react app load and display the component in browser : -

    React takes a different approach by letting you build what's known as a single-page application (SPA). A single-page application loads only a single HTML document on the first request. Then, it updates the specific portion, content, or body of the webpage that needs updating using JavaScript Open the console by either right-clicking and inspecting an element or by opening the toolbar by clicking View > Developer > JavaScript console. The Components tab will show the current React component tree, along with any props, state, or context.

17. Jsx : -

JSX stands for JavaScript XML. JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React.

18. Advantage of jsx : -

One of the advantages of JSX is that React creates a virtual DOM (a virtual representation of the page) to track changes and updates. Instead of rewriting the entire HTML, React modifies the DOM of the page whenever the information is updated. This is one of the main issues React was created to solve.

19. Babel : -

Babel is a JavaScript compiler that converts modern JavaScript code into a version compatible with all browsers. Babel enables React developers to use the latest JavaScript syntax in their components. Babel transpiles modern JavaScript for use in React components and all browsers.

20. Transpiler : -

Babel in react operates as a transpiler, converting the latest JavaScript syntax into a version that can run in all environments. This is done by converting the latest JavaScript syntax into an older version that is supported by all browsers.

21. Fragment : -

React Fragment is a feature in React that allows you to return multiple elements from a React component by allowing you to group a list of children without adding extra nodes to the DOM. To return multiple elements from a React component, you'll need to wrap the element in a root element.

22. how do you iterate over a list in jsx react ?

Using the map() Method

The map() method is the most commonly used function to iterate over an array of data in JSX. You can attach the map() method to the array and pass a callback function that gets called for each iteration. When rendering the User component, pass a unique value to the key prop.

23. Map method : -

Map is a type of data structure or data collection that is used to store the data in the form of key and value pairs. Each pair has a unique key in a map, and the value stored in each pair must be mapped to its unique key.

The map() function is used to iterate over an array and manipulate or change data items. In React, the map() function is most commonly used for rendering a list of data to the DOM.

24. Props in jsx : -

React Props. Props stand for "Properties." They are read-only components. It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It gives a way to pass data from one component to other components. It is similar to function arguments.

**Using Props in React**

- Firstly, define an attribute and its value(data)
- Then pass it to child component(s) by using Props.
- Finally, render the Props Data.

Props are used to store data that can be accessed by the children of a React component. They are part of the concept of reusability. Props take the place of class attributes and allow you to create consistent interfaces across the component hierarchy.

25. Spread operator : -

In the context of React, the spread operator can be used to spread an object of props onto an element in a React component, making it easier to pass down props to child components but more on that later!

The main difference between rest and spread is that the rest operator puts the rest of some specific user-supplied values into a JavaScript array. But the spread syntax expands iterables into individual elements.

26. methods for conditional rendering in react:-
- if/else.
- Ternary operation.
- Inline IF with Logical && operator.
- Switch case operator.
- Conditional Rendering with enums.
- Higher-Order Components.
27. React context : -

React Context is a method to pass props from parent to child component(s), by storing the props in a store(similar in Redux) and using these props from the store by child component(s) without actually passing them manually at each level of the component tree.

28. Prop drilling : -

Prop drilling occurs when a parent component passes data down to its children and then those children pass the same data down to their own children. This process can continue indefinitely.

Prop drilling occurs when you need to pass down data through multiple nested components to reach the ones that require the data. This practice can lead to a complex and tightly coupled component hierarchy, making it challenging to manage state and refactor your application.

29. Control and uncontrolled component : -

In React, controlled components refer to components that have their state and behavior controlled by the parent component. These components rely on props passed down from the parent component to update their state and behavior. Uncontrolled components refer to components that manage their own state internally.

In a controlled component react, state handles all the form data, whereas, in an uncontrolled component, the HTML form element data is managed by only the DOM. If you are using a controlled component, you are in control of your form input values. The developer can decide what to insert or not and where to insert it.

30. What is React extension?

React Developer Tools is a Chrome DevTools extension for the open-source React JavaScript library. It allows you to inspect the React component hierarchies in the Chrome Developer Tools.

31. Event : -

An event is an action that could be triggered as a result of the user action or system generated event. For example, a mouse click, loading of a web page, pressing a key, window resizes, and other interactions are called events.

Basic Event Handling

You need to use the specific React version, otherwise you get a compile error. Events supported are: AnimationEvent , ChangeEvent , ClipboardEvent , CompositionEvent , DragEvent , FocusEvent , FormEvent , KeyboardEvent , MouseEvent , PointerEvent , TouchEvent , TransitionEvent , WheelEvent .

32. State : -

React components has a built-in state object. The state object is where you store property values that belong to the component. When the state object changes, the component re-renders.

33. Higher order and pure component : -

**Higher-order components (HOCs)** are a powerful feature of the React library. They allow you to reuse component logic across multiple components. In React, a higher-order component is a function that takes a component as an argument and returns a new component that wraps the original component.

**React pure components** are the components that do not re-render when the value of props and state has been updated with the same values. Since these components do not cause re-rendering when the same values are passed thus they improve performance.

34 routing : -

Routing in reactJS is the mechanism by which we navigate through a website or web-application. Routing can be server-side routing or client-side routing. However, React Router is a part of client-side routing.

35. React router : -

React Router is a JavaScript framework that lets us handle client and server-side routing in React applications. It enables the creation of single-page web or mobile apps that allow navigating without refreshing the page. It also allows us to use browser history features while preserving the right application view.

36. Life cycle method : -
- Mounting. These methods are called in the following order when an instance of a component is being created and inserted into the DOM: …componentDidMount()
- Updating. An update can be caused by changes to props or state. …componentDidUpdate()
- Unmounting. This method is called when a component is being removed from the DOM: …componentWillUnmount()
- Error Handling.
37. Interceptors : -

Interceptors allow you to modify the request or response before it is sent or received by the server. Interceptors are useful because they allow developers to add custom functionality to requests and responses without modifying the actual code that makes the request.

38. Refs in react : -

Refs are a function provided by React to access the DOM element and the React element that you might have created on your own. They are used in cases where we want to change the value of a child component, without making use of props and all. They have wide functionality as we can use callbacks with them

Refs are a function that use to access the DOM from components. You only need to attach a ref to the element in your application to provide access to it from anywhere within your component without making use of props and all. We can also use Refs to direct access to React elements and use callbacks with them.

39. Element vs component : -

A React element is an object representation of a DOM node. A component encapsulates a DOM tree. Elements are immutable i,e once created cannot be changed. The state in a component is mutable.

There is certainly a difference between elements and components. Furthermore, a component refers to a small part of a larger entity that mostly is a manufactured object. In contrast, an element is one the simplest parts of which anything consists of.

40. Class base vs function base component : -

A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX). A class component requires you to extend from React. Component and create a render function that returns a React element. There is no render method used in functional components.

Function components allow you to use Hooks. That means you can use additional functionality and make it easier to manage state and side effects.

41. Hooks : -

Hooks allow function components to have access to state and other React features. Because of this, class components are generally no longer needed. Although Hooks generally replace class components, there are no plans to remove classes from React.

42. Usestate hook : -

useState is React Hook that allows you to add state to a functional component. It returns an array with two values: the current state and a function to update it. The Hook takes an initial state value as an argument and returns an updated state value whenever the setter function is called.

43. Useeffect hook : -

The useEffect Hook allows you to perform side effects in your components. Some examples of side effects are: fetching data, directly updating the DOM, and timers. useEffect accepts two arguments. The second argument is optional.

44. Usecontext hook : -

The useContext Hook provides function components access to the context value for a context object. It: Takes the context object (i.e., value returned from React. createContext ) as the one argument it accepts. And returns the current context value as given by the nearest context provider

45. Useref hook : -

The useRef Hook allows you to persist values between renders. It can be used to store a mutable value that does not cause a re-render when updated. It can be used to access a DOM element directly.

46. Usereducer hook : -

The useReducer Hook is similar to the useState Hook. It allows for custom state logic. If you find yourself keeping track of multiple pieces of state that rely on complex logic, useReducer may be useful.

On the other hand, the main advantage of using the useReducer() is that it allows us to manage complex state changes in a single, centralized place. We can define all of our state updates and actions in the reducer() function, making it easier to maintain and debug our application.

47. Usememo hook : -

The React useMemo Hook returns a memoized value. Think of memoization as caching a value so that it does not need to be recalculated. The useMemo Hook only runs when one of its dependencies update. This can improve performance. The useMemo and useCallback Hooks are similar.

The React hooks useMemo take two arguments in its parameter. These arguments are an array of dependencies and some functions whose output you want to cache. By default, the useMemo hook will execute the function you passed as an argument after the initial render.

48. Custom hook : -

Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated

Hooks are reusable functions. When you have component logic that needs to be used by multiple components, we can extract that logic to a custom Hook. Custom Hooks start with "use". Example: useFetch .

49. Lazy loading : -

Lazy loading is a technique for waiting to load certain parts of a webpage — especially images — until they are needed. Instead of loading everything all at once, known as "eager" loading, the browser does not request certain resources until the user interacts in such a way that the resources are needed.

50. Arrow function : -

Arrow functions offer a compressed and short version of a function expression and need fewer keystrokes than regular JavaScript functions from the developer and can be used as a simpler alternative to functions within class components and functional components and event handlers in React

51. Props vs state : -

Props are used to pass data from a parent component to a child component, while state is used to manage data within a component. Props are immutable and cannot be changed within a component, while state is mutable and can be updated using the setState function.

52. can ajax is used with react ?

You can use any AJAX library you like with React. Some popular ones are Axios, jQuery AJAX, and the browser built-in window. Fetch.

The core function of Ajax is to asynchronously update web content, justifying the “A” of AJAX. This means a user's web browser doesn't need to refresh the entire web page while changing a small portion of the content on the page. So, there is no need for a page reload or a postback.

We need to call APIs from a remote endpoint to access external resources, which we can do using Ajax to configure the request and respond to the resources.

53. Synthetic event : -

The react event handling system is known as Synthetic Events. The synthetic event is a cross-browser wrapper of the browser's native event. Handling events with react have some syntactic differences from handling events on DOM. These are: React events are named as camelCase instead of lowercase.

54. Stateful component & stateless component : -

The difference between stateful and stateless is that one has state, and the other doesn't. That means the stateful components are keeping track of changing data, while stateless components print out what is given to them via props, or they always render the same thing.

The answer is performance. Stateless functional components can be rendered faster. One of the reasons why this is the case is because stateless functional components do not require some of the life cycle hooks.

55. Disadvantage of using MVC in react : -

One of the drawbacks of MVC is that it can increase the complexity and overhead of your code. Because you have to create and manage three components, you may end up with more files, classes, and functions than necessary. This can make your code harder to debug and refactor.

56. Keys : -

A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used in React to identify which items in the list are changed, updated, or deleted. Keys are used to give an identity to the elements in the lists.

57. What is the second argument that can optionally be passed to setState and what is its purpose ?

    The second argument that can optionally be passed to setState is a callback function which gets called immediately after the setState is completed and the components get re-rendered.

58. Strict mode : -

StrictMode is a tool that highlights potential issues in a programme. It works by encapsulating a portion of your full application as a component. StrictMode does not render any visible elements in the DOM in development mode, but it enables checks and gives warnings.

59. React fiber : -

React Fiber is a backwards compatible, complete rewrite of the React core. In other words, it is a reimplementation of older versions of the React reconciler. Introduced from React 16, Fiber Reconciler is the new reconciliation algorithm in React.

Goals of React Fiber: Fiber focuses on animations and responsiveness. It has the ability to split work into chunks and prioritize tasks. We can pause work and come back to it later. We can also reuse previously completed work or maybe abort it if it is not needed

60\.Error boundary : -

Error boundaries in React are a crucial aspect of error handling in React applications. They are React components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the component tree that crashed.

To handle errors, wrap components with the error boundary class component. You can wrap the top-level component or individual components. If you wrap the top-level component, the error boundary class will handle the errors thrown by all the components in the React application

61. Optimize react app performance : -
- Minimize the number of re-renders. ...
- Use the production build. ...
- Code-splitting. ...
- Lazy loading. ...
- Avoid using inline styles. ...
- Use the React DevTools profiler. ...
- Optimize images and other assets.
62. Reconciliation : -

Reconciliation is the process by which React updates the UI to reflect changes in the component state. The reconciliation algorithm is the set of rules that React uses to determine how to update the UI in the most efficient way possible. React uses a virtual DOM (Document Object Model) to update the UI.

63. How does React rendering works?

After you trigger a render, React calls your components to figure out what to display on screen. “Rendering” is React calling your components. On initial render, React will call the root component. For subsequent renders, React will call the function component whose state update triggered the render.

64. Unidirectional data flow : -

React, a Javascript library, uses unidirectional data flow. The data from the parent is known as props. You can only transfer data from parent to child and not vice versa. This means that the child components cannot update or modify the data on their own, makeing sure that a clean data flow architecture is followed.

65. Mounting : -

Mounting is the initial phase in which the instance of the component is created and inserted into the DOM. When the component gets successfully inserted into the DOM, the component is said to be mounted. In the updating phase, the component gets updated while being present in the DOM

66. Way to call api : -

An API call in React refers to making a request to a web API from a React application. We can make an API call with: XMLHttpRequest, Fetch API or Axios.

67. React context api : -

The React Context API, introduced in React v. 16.3, allows us to pass data through our component trees, giving our components the ability to communicate and share data at different levels.

68. Event pooling : -

Events in React are pooled, this means that the SyntheticEvent object will be reused and all properties will be nullified after the event handler has been called. In simpler terms, as soon as the eventHandler is done with its job, the same event object will be recycled and made new for handling other events.

69. Set state () : -

setState() allows you to change state in a React class component. To change the state of a function component, you use the useState() hook. Learn more about it here. setState() enqueues change to the component state and tell React that this component and its children need to be re-rendered with the updated state.

\- -NEXT.JS- -

1\.WHAT IS NEXT JS ?

Next.js is a React framework that gives you building blocks to create web applications. By framework, we mean Next.js handles the tooling and configuration needed for React, and provides additional structure, features, and optimizations for your application.

2. FEATURES : -

Next.js is a React framework that gives you building blocks to create web applications. By framework, we mean Next.js handles the tooling and configuration needed for React, and provides additional structure, features, and optimizations for your application.

- Data Fetching. Make your React component async and await your data. ...
- Node.js & Edge Runtimes. ...
- Advanced Routing & Nested Layouts. ...
- CSS Support. ...
- Route Handlers. ...
- Middleware. ...
- Client and Server Rendering.
3. ADVANTAGE AND DISADVANTAGE : -

The benefits of using Next. js in developing websites are adaptability and responsiveness, security, shorter load time, improved SEO, a faster development process, and better image optimisation.

Limitations of Using NextJS

It's a file-based router, which means that it's a file system and uses files to deal with responses and requests. Sometimes these file projects aren't sufficient for some projects. To create or use the dynamic routes, you need to have NodeJS in hand, which requires proficient developers.

4. Server Components & Client Components : -

Server Component is a component that is fetched and rendered ON THE SERVER, while Client Component is the one that is fetched and rendered ON THE CLIENT(browser).

React Server Components allow you to write UI that can be rendered and optionally cached on the server. In Next.js, the rendering work is further split by route segments to enable streaming and partial rendering, and there are three different server rendering strategies: Static Rendering.

5. Routing types : -

file-system based router

Next.js uses a file-system based router where folders are used to define routes. Each folder represents a route segment that maps to a URL segment. To create a nested route, you can nest folders inside each other.

6. Default component : -

By default, Next.js uses Server Components. This allows you to automatically implement server rendering with no additional configuration, and you can opt into using Client Components when you needed,

7. Can we use event in server component ?

if you want to use event handlers you have to add 'use client'; at the top of your component file because the node. js server that renders the server components for create static version of your app knows nothing about browser APIs like DOM

8. Middleware : -

Middleware in Next. js is a piece of code that allows you to perform actions before a request is completed and modify the response accordingly. It bridges the incoming request and your application, providing flexibility and control over the request/response flow.

9. Environment variable : -

Environment variables in Next. js are a way to set configuration values that are used by your application. They can be used to store data such as the name of your company, the port your application will run on, or any other configuration values you need.

10. Why server component better for seo ?

js has a pre-rendering feature that the HTML supposed to render is produced on the server-side then sent to the client-side. This pre-rendering feature provides improved SEO for the Next. js application because the search engine will get HTML directly from the server and doesn't require generating HTML while crawling.

11. How can custom error page created in next js ?

To create a custom 404 page, you first need to create a “404. js” named file in your pages directory. This file is statically generated at build time. In this page create and export a custom component and the rest will be taken care of by Next Js

12. Benefits of implementing a serverless model :-

Serverless deployment dramatically improves reliability and scalability by splitting your application into smaller parts (also called lambdas). In the case of Next. js, each page in the pages directory becomes a serverless lambda

The Serverless Framework enables developers to quickly configure and deploy their applications. It provides developers with the ability to customize events, functions, and triggers, as well as the resources required to run their applications

13. SSR : -

SSR or Server Side Rendering is also known as dynamic rendering. In SSR the page is generated each time the server gets a request. Pages on which the data have to change for a particular type of request, those pages use SSR as data is not the same for every request and may vary with it.

SSR brings several benefits to Next. js applications: Improved SEO: SSR enables search engines to easily crawl and index our pages, leading to better search engine rankings and visibility. Faster initial page load: Pre-rendered HTML is sent from the server, resulting in shorter load times and a better user experience.

14. STYLED JSX IN NEXT JS : -

Styled JSX is a CSS-in-JS library that lets you write encapsulated and scoped CSS to style your components. The styles you make for one component won't impact other's features. Allowing you to add, modify and delete styles without stressing unintended side effects.

15. Automatic code splitting : -

Code-splitting is the process of splitting the application's bundle into smaller chunks required by each entry point. The goal is to improve the application's initial load time by only loading the code required to run that page.

Next.js has built-in support for code splitting. Each file inside your pages/ directory will be automatically code split into its own JavaScript bundle during the build step. Further: Any code shared between pages is also split into another bundle to avoid re-downloading the same code on further navigation.

16. Frontend or backend ?

Next. js is a React framework that makes building powerful full stack (front end + back end) applications a lot easier. The team behind Next. js recently released Next

17. Dom : -

React uses a virtual DOM that is a JavaScript representation of the actual DOM. This allows React to update only the components that have changed, which makes React apps faster. Next. js also uses a virtual DOM, but it also builds on React to provide additional features that can make Next

18. Imperative and declarative programming : -

The easiest way to explain the difference between declarative and imperative code, would be that imperative code focuses on writing an explicit sequence of commands to describe how you want the computer to do things, and declarative code focuses on specifying the result of what you want.

19. Types of prerendring : -

Next.js has two forms of pre-rendering: **[Static Generation**](https://nextjs.org/docs/basic-features/pages#static-generation-recommended)** and **[Server-side Rendering**](https://nextjs.org/docs/basic-features/pages#server-side-rendering)**. The difference is in **when** it generates the HTML for a page.

- [**Static Generation**](https://nextjs.org/docs/basic-features/pages#static-generation-recommended) is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then *reused* on each request.
- [**Server-side Rendering**](https://nextjs.org/docs/basic-features/pages#server-side-rendering) is the pre-rendering method that generates the HTML on **each request**.
20. Default prerender : -

By default, Next.js pre-renders every page. This means that Next.js *generates HTML for each page in advance*, instead of having it all done by client-side JavaScript. Pre-rendering can result in better performance and [SEO](https://en.wikipedia.org/wiki/Search_engine_optimization).

Each generated HTML is associated with minimal JavaScript code necessary for that page. When a page is loaded by the browser, its JavaScript code runs and makes the page fully interactive. (This process is called **hydration**.)

21. Main scripts : -

Nextjs Script component is one of them. In nextjs Script component help to add third-party javascript like google Adsense, google analytics, stripe, tailwind CSS, and many more. Nextjs automatically optimize your app with the nextjs script component. You do not worry about configuration and other stuff.

22. Method for fetching data : -

Server-Side Data Fetching 

Next. js provides two functions, getStaticProps and getServerSideProps , for server-side data fetching during the rendering process. These functions allow you to fetch data from an API or a database and pass it as props to your page components

23. getinitial props() : -

getInitialProps is a special function provided by Next. js that runs on the server side before rendering a page. This function allows you to fetch data from an external API, database, or any other data source, and pass it as props to your React components.

24. Key feature of seo : -

Next. js provides better SEO performance by rendering web pages on the server (server-side) instead of rendering in the browser (client-side). Server-side rendering allows search engine crawlers and bots to scan and index web pages, detect metadata, and properly understand the information a website contains

SEO stands for Search Engine Optimization. The goal of SEO is to create a strategy that will increase your rankings position in search engine results. The higher the ranking, the more organic traffic to your site, which ultimately leads to more business for you!

25. How build id be configured ?

Next. js uses a constant id generated at build time to identify which version of your application is being served. This can cause problems in multi-server deployments when next build is run on every server. In order to keep a consistent build id between builds you can provide your own build id.

To configure the build-id in Next. js , we must configure a static ID between our builds. So, we have to provide the " generateBuildId " function with the following configuration.

26. AMP first page method : -

The page is automatically optimized with AMP Optimizer , an optimizer that applies the same transformations as AMP caches (improves performance by up to 42%) The page has a user-accessible (optimized) version of the page and a search-engine indexable (unoptimized) version of the page

27. Hybrid amp first page method : -

The page is rendered as traditional HTML (default) and AMP HTML (by adding ? amp=1 to the URL) The AMP version of the page only has valid optimizations applied with AMP Optimizer so that it is indexable by search-engines.

28. How cdn be setup ?

To set up a CDN , you can set up an asset prefix and configure your CDN's origin to resolve to the domain that Next. js is hosted on. The exact configuration for uploading your files to a given CDN will depend on your CDN of choice. The only folder you need to host on your CDN is the contents of .

In Next. js, since pre-rendering can be done ahead of time, CDNs are well suited to store the static result of the work - making content delivery faster.

29. What is the alternative to Next.js framework?

Well, there are quite a few options for you to explore! Some popular ones are Gatsby, Nuxt. js, and Sapper/SvelteKit. Each of these frameworks has its own unique features and capabilities, but they all serve the purpose of creating fast, modern web applications.

30. Is Next.js written in TypeScript?

Next.js provides a TypeScript-first development experience for building your React application. It comes with built-in TypeScript support for automatically installing the necessary packages and configuring the proper settings.

**THANK YOU -**
