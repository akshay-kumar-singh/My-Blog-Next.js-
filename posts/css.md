---
title: Important CSS question
excerpt: Css is the most important programming language for web development. You probably don't know it well enough!
image: css.png
isFeatured: false
date: '2021-10-30'
---

**INTERVIEW**

1\.What is css : -

CSS is the acronym of “Cascading Style Sheets”. CSS is a computer language for laying out and structuring web pages (HTML or XML). This language contains coding elements and is composed of these “cascading style sheets” which are equally called CSS files

2. Types : -

**There are three types of CSS which are given below:**

- Inline CSS.
- Internal or Embedded CSS.
- External CSS.
3. Css selectors : -

CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:

- Simple selectors (select elements based on name, id, class)
- [Combinator selectors](https://www.w3schools.com/css/css_combinators.asp) (select elements based on a specific relationship between them)
- [Pseudo-class selectors](https://www.w3schools.com/css/css_pseudo_classes.asp) (select elements based on a certain state)
- [Pseudo-elements selectors](https://www.w3schools.com/css/css_pseudo_elements.asp) (select and style a part of an element)
- [Attribute selectors](https://www.w3schools.com/css/css_attribute_selectors.asp) (select elements based on an attribute or attribute value)
4. Universal selector : -

The asterisk (\*) is known as the CSS universal selectors. It can be used to select any and all types of elements in an HTML page. The asterisk can also be followed by a selector while using to select a child object. This selector is useful when we want to select all the elements on the page.

5. Box sizing : -

The box-sizing property allows us to include the padding and border in an element's total width and height. If you set box-sizing: border-box; on an element, padding and border are included in the width and height: Both divs are the same size now!

6. Hide an element : -

You can hide an element in CSS using the CSS properties display: none or visibility: hidden . display: none removes the entire element from the page and mat affect the layout of the page.

7. Flex model : -

The flexbox or flexible box model in CSS is a one-dimensional layout model that has flexible and efficient layouts with distributed spaces among items to control their alignment structure ie., it is a layout model that provides an easy and clean way to arrange items within a container.

In a perfect world of browser support, the reason you'd choose to use flexbox is because you want to lay a collection of items out in one direction or another. As you lay out your items you want to control the dimensions of the items in that one dimension, or control the spacing between items.

8. Important : -

The !important rule in CSS is used to add more importance to a property/value than normal. In fact, if you use the !important rule, it will override ALL previous styling rules for that specific property on that element!

9. Css Sprites : -

CSS Sprites are a collection of images that are combined into a single file that an HTML document can access. These images are then called into use within the HTML code to be displayed on the website.

10. Pseudo class / Pseudo element : -

In CSS, pseudo-classes and pseudo-elements are two types of keywords that you can combine with selectors. They are used to target the element's state or specific parts of an element.

A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, the pseudo-class :hover can be used to select a button when a user's pointer hovers over the button and this selected button can then be styled.

11. SASS , LESS , STYLUS : -

LESS is pretty intuitive and more CSS-like.

SASS is more programmatic than it is CSS-like, although it supports all versions of CSS.

Stylus is more concise, intuitive and is just as programmatic as SASS. This is due to the fact that they are both imperatively styled.

12. Position relative vs Position absolute : -

a relative position moves the element, but still consumes some space in the original position. an absolute or fixed position moves the element, but does not consume any layout space.

13. VH : -

The full form of VH is viewport height. It works like the percentage unit as well. Specifying 10vh is equivalent to occupying 10% of entire visible screen height.

14. CSS3 vs CSS2 : -

CSS3 has compatibility with external font styles through google fonts and typecast. It was not possible with earlier CSS1 and CSS2. The selectors in CSS3 has increased while CSS1 and CSS2 only had simple selectors. CSS1 AND CSS2 didn't have provision to specifically design the web layout.CSS3 is now split into different modules. Since each module makes its way through the W3C individually, there's a wider range of browser support. Make sure you test your CSS3 pages in as many browsers and operating systems as possible to ensure compatibility

15. RGB stream : -

RGB represents colors in CSS. There are three streams in this nomenclature representing a color, namely the Red, Green, and Blue streams. The intensity of colors is represented using numbers 0 to 255. This allows CSS to have a spectrum of visible colors.

16. Class vs Id : -

While an ID is specific to a single element, classes can be assigned to multiple elements on a page or throughout the website. They are not unique. And while a single element can only have one ID, it can have multiple classes.

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

To select elements with a specific class, write a period (.) character, followed by the class name.

17. Z-index : -

Z Index ( z-index ) is a CSS property that defines the order of overlapping HTML elements. Elements with a higher index will be placed on top of elements with a lower index. Note: Z index only works on positioned elements ( position:absolute , position:relative , or position:fixed ).

18. Media types : -

The @media rule, introduced in CSS2, made it possible to define different style rules for different media types.

Examples: You could have one set of style rules for computer screens, one for printers, one for handheld devices, one for television-type devices, and so on.

Unfortunately these media types never got a lot of support by devices, other than the print media type.![](Aspose.Words.f5cf3f34-fc70-4f9a-8f69-07488d1636a0.001.png)

CSS3 Introduced Media Queries

Media queries in CSS3 extended the CSS2 media types idea: Instead of looking for a type of device, they look at the capability of the device.

Media queries can be used to check many things, such as:

- width and height of the viewport
- width and height of the device
- orientation (is the tablet/phone in landscape or portrait mode?)
- resolution

Using media queries are a popular technique for delivering a tailored style sheet to desktops, laptops, tablets, and mobile phones (such as iPhone and Android phones).

19. Image repetition : -

The CSS background-repeat is what you're looking for. If you want the background image not to repeat at all, use background-repeat: no-repeat;

20. Image scroll : -

Background-repeat : none; Background-attachment : fixed;

21. Font related attributes : -
- font-family.
- font-size.
- font-stretch.
- font-style.
- font-variant.
- font-weight.
- line-height.
22. Contextual selectors : -

A contextual selector matches when an element is an arbitrary descendent of some ancestor element (i.e., it may be any generation below the ancestor element). A contextual selector is made up of two or more selectors separated by white space.

Contextual selectors allow the developer to select different types of styles for different parts of the document. In CSS, the developer can either specify styles directly or by making certain classes. The contextual selector will only apply the style to the elements which are specified.

23. Css nomenclature : -

The CSS class naming convention defines rules for choosing the character sequences for naming a CSS class to reduce the effort needed to read and understand the code. There are various naming conventions, like using hyphen-delimited strings, BEM(Block-Element-Modifier), OOCSS(Object-oriented CSS), etc.

- Naming Convention Basics.
- Do Not Use Special Characters.
- Do Not Use Any Spaces.
- The Filename Should Start With a Letter.
- Use All Lower Case.
- Keep the Filename as Short as Possible.
- The Most Important Part of Your CSS Filename.
- CSS File-Naming Conventions.
24. When should you use translate () instead of absolute positioning in

CSS?

Use translate() when you need to move an element without affecting the layout of other elements on the page. Consider using translate() instead of absolute positioning in scenarios such as animations, responsive design, and small adjustments to element positions.

25. Position some aspect : -

The <position> (or <bg-position> ) CSS data type denotes a two-dimensional coordinate used to set a location relative to an element box. It is used in the background-position and offset-anchor properties. Note: The final position described by the <position> value does not need to be inside the element's box

26. Mixins : -

A mixin lets you make groups of CSS declarations that you want to reuse throughout your site. It helps keep your Sass very DRY. You can even pass in values to make your mixin more flexible. Here's an example for theme . SCSS.

Mixins allow you to define styles that can be re-used throughout your stylesheet. They make it easy to avoid using non-semantic classes like .float-left , and to distribute collections of styles in libraries.

27. How does browser work under the hood?

Each browser has a browser engine under the hood. It works as a bridge between the user interface and the rendering engine. It queries and manipulates the rendering engine based on the input it gets from the user interface.

28. Float : -

The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

29. Logical vs physical tag : -

a logical tag is a tag that describes the meaning or structure of the content it surrounds, while a physical tag describes the presentation or appearance of the content.

30. Image scripts : -

An image sprite is a collection of images put into a single image. A web page with many images can take a long time to load and generates multiple server requests. Using image sprites will reduce the number of server requests and save bandwidth.

31. Position static : -

The position property specifies the type of positioning method used for an element.

There are five different position values:

- static
- relative
- fixed
- absolute
- sticky ●
32. Attribute selectors : -

This type of attribute selector is used to select all the elements that have the specified attribute and applies the CSS property to that attribute. For example, the selector [class] will select all the elements with the style attribute

33. Child selectors : -

The child selector selects all elements that are the children of a specified element.

34. Css framework : -

**Top 5 CSS Frameworks for Developers and Designers**

- Bootstrap.
- Tailwind CSS.
- Foundation.
- Bulma.
- Skeleton.
35. Ruleset : -

The CSS Ruleset is used to apply a set of properties with some define values for the element or a specific set of elements that are used in the HTML page.

36. Embedded style sheet : -

It allows you to define styles for a particular HTML document as a whole in one place. This is done by embedding the <style></style> tags containing the CSS properties in the head of your document.

37. Reset vs normalize css : -

Normalizing retains the default styles that are useful and removes those that are not whereas the reset removes all the styles of the browser. In reset, we will have to re declare all the styles after resetting the browser whereas, normalizing will keep the required styles and only removes the unwanted ones

38. Adaptive vs responsive desing : -

A responsive design can change its layout and appearance based on the screen size of the device it's accessed on, from a large desktop computer to a small mobile phone. An adaptive design requires the creation of a different layout for each device the website will be accessed on

39. Center a div : -

.parent {

background: gray; height: 300px; width: 300px; position: relative;

}

.child {

background-color: orange; position: absolute;

top: 50%;

left: 50%;

transform: translate(-50%,-50%);

}

40. Grid system : -

The CSS grid layout module excels at dividing a page into major regions or defining the relationship in terms of size, position, and layer, between parts of a control built from HTML primitives. Like tables, grid layout enables an author to align elements into columns and rows.

41. Grid vs flex box : -

The basic difference between CSS grid layout and CSS flexbox layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

42. Progressive rendering : -

In progressive Rendering, the web page is divided into different parts on the basis of priority. So different parts will be rendered sequentially according to Server-Side Rendering and sent to the client side

43. Reset.css file : -

A CSS Reset file circumvents inconsistencies across different browsers when developing websites. All browsers have default rules with properties and values applied to all pages before loading files. Due to the cascading nature of CSS, any styles the browser uses will remain unless explicitly overridden

44. Box model vs box sizing : -

The box model refers to the composition of elements on a page. When you specify the height or width of an element, you're setting the content size—any padding, border, and margin will be added to that. Applying box-sizing: border-box to an element changes the box model to a more predictable behavior.

45. Css variables : -

The var() function is used to insert the value of a CSS variable.

CSS variables have access to the DOM, which means that you can create variables with local or global scope, change the variables with JavaScript, and change the variables based on media queries.

A good way to use CSS variables is when it comes to the colors of your design. Instead of copy and paste the same colors over and over again, you can place them in variables.

46. Display property : -

The display CSS property sets whether an element is treated as a block or inline box and the layout used for its children, such as flow layout, grid or flex. Formally, the display property sets an element's inner and outer display types.

47. Direct child selectors and descendent child selector in css : -

    The Child Combinator (>) only selects those HTML Elements that are direct children of a specified element. While the Descendant Combinator selects all HTML Elements that are either children, grandchildren, great grandchildren and so on. They all are descendants of a specified element and thus all are selected.

48. Margin vs padding : -

In CSS, a margin is the space around an element's border, while padding is the space between an element's border and the element's content. Put another way, the margin property controls the space outside an element, and the padding property controls the space inside an element.

49. Media breakpoint for responsive : -
- Mobile devices – 320px — 480px.
- iPads, Tablets – 481px — 768px.
- Small screens, laptops – 769px — 1024px.
- Desktops, large screens – 1025px — 1200px.
- Extra large screens, TV – 1201px, and more.
50. Bem methodology : -

BEM is a front-end naming method for organizing and naming CSS classes. The Block, Element, Modifier methodology is a popular naming convention for class names in HTML and CSS

51. Em vs rem : -

Basically that both rem and em are scalable and relative units of size, but with em, the unit is relative to the font size of its parent element, while the rem unit is only relative to the root font size of the HTML document. The “r” in rem stands for “root”

52. Specificity : -

If there are two or more CSS rules that point to the same element, the selector with the highest specificity value will "win", and its style declaration will be applied to that HTML element.

53. Diff b/w static,relative,absolute and fixed position : -

    Static - this is the default value, all elements are in order as they appear in the document. Relative - the element is positioned relative to its normal position. Absolute - the element is positioned absolutely to its first positioned parent. Fixed - the element is positioned related to the browser window.

54. Gradient : -

Gradient Backgrounds. CSS gradients let you display smooth transitions between two or more specified colors. CSS defines three types of gradients: Linear Gradients (goes down/up/left/right/diagonally) Radial Gradients (defined by their center)

55. Calc () : -

It can be used to calculate length, percentage, time, number, integer frequency, or angle. It uses the four simple arithmetic operators add (+), multiply (\*), subtract (-), and divide (/). It is a powerful CSS concept because it allows us to mix any units, such as percentage and pixel.

56. Word wrap : -

The word-wrap property allows long words to be able to be broken and wrap onto the next line.

57. Shadow effect : -

With CSS you can add shadow to text and to elements.

h1 { text-shadow: 2px 2px;}

58. Transition : -

CSS transitions provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time.

**THANK YOU**

**(*AKKI)***


