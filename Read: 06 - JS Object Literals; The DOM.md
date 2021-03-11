### Domain Modeling
 process of creating a conceptual model in code for a specific problem


### object-oriented model.
entity that stores data in properties and encapsulates behaviors in methods .
1.	The new keyword instantiates (i.e. creates) an object.
he constructor function initializes properties inside that object using the this variable.
The object is stored in a variable for later use.


Generate random numbers
To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a Math.random() function for just this sort of occasion.


 tips to follow when building your own domain models.
1.	When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2.	Model its attributes with a constructor function that defines and initializes properties.
3.	Model its behaviors with small methods that focus on doing one job well.
4.	Create instances using the new keyword followed by a call to a constructor function.
5.	Store the newly created object in a variable so you can access its properties and methods from outside.
6.	Use the this variable within methods so you can access the object's properties and methods from inside



### Tables:

table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results

The `<table>` element is used to create a table. The contents of the table are written out row
by row.

`<tr>` indicate the start of each row using the opening tag. Its shortcut of table row.

`<td>` cell of a table is , td stands for table data.

`<th>`  its like <td> element but its purpose is to represent the heading for either a column or
a row. (The th stands for table heading.)


For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>



### Functions, Methods, and Objects

• we can use ‘ new ‘ word to create a  new object

• to update value of properties we can use dot notation or square brackets . 
for example :

`hotel.name=’park’`
Or 
`hotel`[‘name’]`=’park’`

• we can use functions as a template  for creating objects .its  contains statements. In this case, the added  properties or methods to the object.



### Chapter 6 : “Functions, Methods, and Objects”:

(I skimmed  the whole chapter and copy the  summary) 

• Functions allow you to group a set of related
statements together that represent a single task.

• Functions can take parameters (information required
to do their job) and may return a value.

• An object is a series of variables and functions that
represent something from the world around you.

• In an object, variables are known as properties of the
object; functions are known as methods of the object.

• Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.


• JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.


• Arrays and objects can be used to create complex data
sets (and both can contain the other).
