#  HTML Links, CSS Layout, JS Functions

## Links
**links are the defining feature of the web because they allow you to move from one web page to another.
Linking to Other Sites 
Links are created using the element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.**
```
<ul>
 <li><a href="http://www.empireonline.com">
 Empire</a></li>
</ul>
```
Linking to Other Pages on the Same Site
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
```
<ul>
 <li><a href="index.html">Home</a></li>
</ul>
```
Email Links
mailto: this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
```
<a href="mailto:jon@example.org">Email Jon</a>
```



Opening Links in a New Window
Target: If you want a link to open in a new window, you can use the target attribute on the opening tag. The value of this attribute should be _blank.
```
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)
```
Linking to a Specific Part of the Same Page
Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to.
```
<h1 id="top">Film-Making Terms</h1>
<a href="#arc_shot">Arc Shot</a><br />
<a href="#interlude">Interlude</a><br />
<a href="#prologue">Prologue</a><br /><br />
<h2 id="arc_shot">Arc Shot</h2>
```

Layout
•	elements are often used as containing elements to group together sections of a page,

•	Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

•	Pages can be fixed width or liquid (stretchy) layouts.

•	The float property moves content to the left or right of the page and can be used to create multi-column layouts.
 (Floated items require a defined width.)

•	Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

There are tons of different layout designs to choose from here some examples:
 
**This called Fix-width layout**

```
<body>
<div id="header">
 <h1>Logo</h1>
 <div id="nav">
 <ul>
 <li><a href="">Home</a></li>
 <li><a href="">Products</a></li>
 <li><a href="">Services</a></li>
 <li><a href="">About</a></li>
 <li><a href="">Contact</a></li>
 </ul>
 </div>
</div>
<div id="content">
 <div id="feature">
 <p>Feature</p>
 </div>
 <div class="article column1">
 <p>Column One</p>
 </div>
 <div class="article column2">
 <p>Column Two</p>
 </div>
 <div class="article column3">
 <p>Column Three</p>
 </div>
</div>
<div id="footer">
 <p>&copy; Copyright 2011</p>
</div>
</body>
```
**This called liquid-layout:**

```
<body>
<div id="header">
 <h1>Logo</h1>
 <div id="nav">
 <ul>
 <li><a href="">Home</a></li>
 <li><a href="">Products</a></li>
 <li><a href="">Services</a></li>
 <li><a href="">About</a></li>
 <li><a href="">Contact</a></li>
 </ul>
 </div>
</div>
<div id="content">
 <div id="feature">
 <p>Feature</p>
 </div>
 <div class="article column1">
 <p>Column One</p>
 </div>
 <div class="article column2">
 <p>Column Two</p>
 </div>
 <div class="article column3">
 <p>Column Three</p>
 </div>
</div>
<div id="footer">
 <p>&copy; Copyright 2011</p>
</div>
</body>
```



## Functions, Methods, and Objects

**Functions let you group a series of statements together to perform a specific task.**

**A BASIC FUNCTION**
```
var msg = 'Sign up to receive our newsletter for 10% off!'; 
function updateMessage() { 
var el = document.getElementByld('message'}; 
el .textContent = msg; 
} 
updateMessage(};
```





**Declaring a Function**

 ```
function Usename() 
{document.write('Ahmad');}

```
**Call the function** 
```
Username();

```

**Declaring functions that need information**:

```
function getArea(width,height) {return width*height;}
```

**Getting a single value out of a function**

```
function calculationArea(width,height){
var area= width* height;
return area;
} 
var wallOne = calculationArea(3,5); 
var wallTwo=calculationArea(8,5);

```

## 6 Reasons for Pair Programming


there are four fundamental skills that help anyone learn a new language:

  * Listening: hearing and interpreting the vocabulary 
  *  Speaking: using the correct words to communicate an idea 
  * Reading: understanding what written language intends to convey 
  * Writing: producing from scratch a meaningful

**As a developer you need to focus on :**
1. Greater efficiency
 2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness



