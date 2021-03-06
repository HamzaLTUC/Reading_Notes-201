

## Understanding The Problem Domain Is The Hardest Part Of Programming

There are many common reasons about the hardest thing about writing code :

•	Learning a new technology

•	Naming things

•	Testing your code

•	Debugging

•	Fixing bugs

•	Making software maintainable



**Problem domain needs:**

1.	Figuring out the major components of the problem.
2.	Sort the priorities and content by component.
3.	Put together all the steps.
4.	Put together each component of the problem from the steps we created.
5.	Sometimes we do not have enough information about problem domain we need to understand that.
6.	simple application and familiarity help us easy to understand, problem domain 

## Objects:
An *object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method.

• we can create objects by literal notation and we can access it using dot notation or square brackets.

to access a property or method we use the name of object followed by period then the name of the property or method we wany access.

![](https://i.ibb.co/CHhSRFk/object.png)


## Document Object Mode:
*It is also called Application program interface (API)

which Specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.


DOM is neither part of HTML, nor part of JavaScript; is a separate set of rules.It is implemented by all major browser makers, and covers two primary areas
When the browser loads a web page, it creates a model of the page in memory ,And DOM specifies in which browser structure, using DOM tree


The DOM is called an object model because the model (the DOM tree) is
made of objects. Each object represents a different part of
the page loaded in the browser window. DOM can change and access html webpage .


![](https://i.ibb.co/WVBPpDW/rsz-1dom.jpg)

**DOM tree**
Every element, attribute, and piece of text in the HTML is represented by its own DOM node.

**Accessing and updating the DOM tree involves two steps:**
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes

**we can select individual element node by:**
1. `getElementByID()`
2. `querySelector()`

**We can select multiple elements by:***

1.`getElementByClassName()`

2. `getElementByTagName()`
 
3.`querySelectorAll().`

**we can move from one element node to related element node by:**

1. Parent mode : This property finds the element node for the containing (or parent) element in the HTML


2. previousSibling/nextSibling : These properties find the previous or next sibling of a node
if there are siblings.


3. firstChild/lastChild : These properties find the first or last child of the current element.


***Access / Update Text Node:**
The text inside any element stored as a text node to access the text node we select the element use FirstChild property to get the text node.

**Work With HTML:**
innerHTML: allows us to access child element and text content.


**to create new nodes we can use :**

1. `createElement()`

2. `CreateTextNode()`

3.` Appendchild()/removeChild`

**To access or update Attribute values we can use:**

`hasAttribute()`:check if an attribute exists

`getAttribute()`: gets it value

`setAttribute()` : update its value

`removeAttribute()`: remove attribute
