### Forms:
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

Form Controls:

1. adding text: text, password input, text area.

1. Making choices: such as radio button ,checkboxes ,Drop-down boxes .

1. Submititng forms: such as Subscribe , image, button .

• Form Structure:
`<form>` element should always carry the action attribute and will usually have a
method and id attribute too.

• actions: Its value is the URL for the page on the server that will receive the
information in the form when it is submitted.

•  method Forms can be sent using one of two methods: get or post.
 • `<input>`  : to create several different form controls. Such as name, size, password.
• `<textarea>` to create a mutli-line text input.
• we can add Radio button, checkout boxes by specifying the type, name, value , 
Checked status.

 `<form action="/my-handling-form-page" method="post">`

`</form>`




### Lists , tables &Forms:
 
• To make list-style-type we can use `<ol>`, `<ul>`, and `<li>` elements.
•  in CSS (list-style-image) used to add style image on list.

#### Tables properties: 

• Width: to set width of table.  
 
• padding: to set the space between the border of each table cell and its content.
 
 • text-transform to convert the content of the table headers to uppercase.

• border-top, border-bottom : to set borders above and below the table headers.

• text-align to align the writing to the left of some table cells and to the right of the others
 
• background-color to change alternating table rows.

• hover to highlight a table row when a user's mouse goes over it


• We can control Gaps Between Cell using  border-spacing, border-collapse 

• The cursor property allows you to control the type of mouse cursor that should be displayed
to users.it has many values ( auto , crosshair, help , wait etc..)


### Events:
HTML events are "things" that happen to HTML elements when JavaScript is used in HTML pages, JavaScript can "react" on these events.

there are a lot types of events such:
1. Load 
2. Unload
3. Error
4. Resize 
5. Scroll
6. Blure
7. focus
etc

• Events triggers JavaScript code by event handling which by:

1. select element
 
3. Specify event

4. Call code.

Here is the syntax to bind an event to an element using an event handle:

![](https://i.ibb.co/QMhpTVP/events.png)

