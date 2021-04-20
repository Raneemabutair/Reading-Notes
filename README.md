# CSS Layout

<img src="https://cdn.freebiesupply.com/images/thumbs/2x/css-layout-templates-from-codepen.png">

## **Key Concepts in Positioning Elements:**
  * **Building Blocks :** CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

  * **Containing Elements:** If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

  ## **Controlling the Position of Elements**
  * Normal flow (Static position)
  * Relative Positioning
  * Absolute positioning
  * Fixed Positioning
  * z-index

## **Floating Elements**
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated.

```
blockquote {
 float: right;
 width: 275px;
 font-size: 130%;
 font-style: italic;
 font-family: Georgia, Times, serif;
 margin: 0px 0px 10px 10px;
 padding: 10px;
 border-top: 1px solid #665544;
 border-bottom: 1px solid #665544;}
```


**We can use Floating for:**

***Placing Elements Side-by-Side.***,
***Left***, 
***Right***,
***None***


## **Creating Multi-Column Layouts with Floats such as using**

  * width This sets the width of the columns. 

  * float These positions the columns next to each other.

  * margin This creates a gap between the columns.


```
.column1of3, .column2of3, .column3of3 {
width: 300px;
float: left;
margin: 10px;}
```


**Fixed Width Layouts**

Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

***Liquid Layouts**

liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

**Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).**

 **Grids help create professional and flexible designs**.

 