# HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Text
**The text is the contents of what presented on your pages, HTML contains several elements for defining text with a special meaning.
HTML elements are used to describe the structure of the page (e.g., headings, subheadings, paragraphs). 
They also provide semantic information (e.g., where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).**
## Elements:
**Headings**
HTML has six "levels" of headings.

<img src= 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSb2Us8ouKzyDlMyiLBobl0t_CmtQ9Wr6bQ2g&usqp=CAU'>;

**Paragraphs**

To write pa Paragraphs on HTML we need to use this code
```
<p> Paragraph</p>
```

***And all other text formatting Tags***

<img src= 'https://image.slidesharecdn.com/html2-150218221004-conversion-gate02/95/html2-1-638.jpg?cb=1424319044 '>;


## Introducing CSS 

**CSS stands for Cascading Style Sheets, CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers.
We have Different types of selectors allow you to target your rules at different elements. CSS rules usually appear in a separate document, although they may appear within an HTML page**


We can write Css in many ways:

•	Inline - by using the style attribute inside HTML elements.

•	Internal - by using a style element in the head section.

•	External - by using a element to link to an external CSS file


## Basic JavaScript Instructions

JavaScript is a programming Language for the Web that can update and change both HTML and CSS by calculate, manipulate and validate data and make web pages more interactive. When using JavaScript, you can easily:

•	ACCESS CONTENT you can use JavaScript to select any element, attribute, or text from an HTML page. For example: Select any elements that have a class attribute with a value of note.


•	MODIFY CONTENT you can use JavaScript to add elements, attributes, and text to the page, or remove them. For example: change the value of class attributes to trigger new CSS rules for those elements.


•	PROGRAM RULES you can specify a set of steps for the browser to follow which allows it to access or change the content of a page. For example: a mortgage calculator could collect values from a form, perform a ca loculation, and display repayments.


•	REACT TO EVENTS You can specify that a script should run when a specific event has occurred. For example, it could be run when: a button is pressed, information is added to a form.



<img src= 'https://modeling-languages.com/wp-content/uploads/2015/04/img_551d34ebec5c3.png  '>;


## Loops

It’s a code block that will keep running as long as the returns are true, we have three types of loops:
1.	(For) Loop 
2.	(While) Loop 
3.	(Do While) Loop 

Example (FOR LOOP)
```
          *Instead of writing:*
 text += cars[0] + "<sf>";
 text += cars[1] + "<sf>";
 text += cars[2] + "<sf>";
 text += cars[3] + "<sf>";
     
        *you can write* 
     var i;
     for (i = 0; i < cars.length; i++) {
     text += cars[i] + "<sf>";