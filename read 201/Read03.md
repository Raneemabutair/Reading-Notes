# HTML Lists, CSS Boxes, JS Control Flow

## Lists

**HTML provides us with three different types of lists:**

• Ordered Lists

```
<ol>
<li> potatoes </li>
<li> water </li>
<li> milk </li>
</ol>
```

```
1. potatoes
2. water
3. milk
```

• Unordered list

```
<ul>
<li> potatoes </li>
<li> water </li>
<li> milk </li>
</ul>
```

```
• potatoes
• water
• milk
```

• Definition List

```
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```
```
Coffee

- black hot drink
Milk
- white cold drink
```

## Boxes

**CSS treats each HTML element as if it has its own box as You can also control the borders, margin and padding for each box with CSS. there is something also name Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.**


***Every box has three available properties that can be adjusted to control its appearance:***

   * Border: The border separates the edge of one box from another.

   * Margin: margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

   * Padding: padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

```
a {
 color: #000000;
 text-transform: uppercase;
 text-decoration: none;
 padding: 6px 18px 5px 18px;}
 a:hover, a.on {
 color: #cc3333;
 background-color: #ffffff;}
 </style>
</head>
<body>
 <div id="page">
 <div id="logo">
 <img src="images/logo.gif" alt="The Analog Specialists" />
 </div>
 <ul id="navigation">
 <li><a href="#" class="on">Home</a></li>
 <li><a href="#">For Sale</a></li>
 <li><a href="#">Repairs</a></li>
 <li><a href="#">About</a></li>
 <li><a href="#">Contact</a></li>
 </ul>
 <p>
 <img src="images/keys.jpg" alt="Fender Rhodes, Hohner Clavinet, 
 and Wurlitzer EP200" />
 </p>
 <p>
 We specialise in the sales and repair of classic keyboards, in particular 
 the Fender Rhodes, Wurlitzer EP200, and Hohner Clavinet.
 </p>
 </div>
</body>
</html>
```


## Basic JavaScript Instructions


**STATEMENTS**
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.


**COMMENTS**
You should write comments to explain what your code does. They help make your code easier to read and understand.

**VARIABLES**
A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

**DATA TYPES**
 * NUMERIC DATA TYPE (1,2,3.5)
*  STRING DATA TYPE “hello”
 * BOOLEAN DATA TYPE (true or false)

Expressions rely on operators to calculate a value.

## Decisions and Loops

**SWITCH STATEMENTS**

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

```
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```

**Type of looping:**
  *	for

* while

* do while

**I explained a lot about in the loop in a previous reads please check them .**
