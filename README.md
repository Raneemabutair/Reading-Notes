# **CSS Transforms, Transitions, and Animations**

## **Transforms**

With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. 

All of these new techniques are made possible by the transform property.

•	Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 

•	Three-dimensional transforms work on both the x and y axes, as well as the z axis.
 These three-dimensional transforms help define not only the length and width of an element, but also the depth. 

•	The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

•	skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. 

## **Transform Origin**

The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

**3D Transforms**

Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements.


**Transitions**

for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the: hover, :focus, :active, and :target pseudo-classes. 

•	popular transitional properties Such as:
•	background-color
•	background-position
•	border-color
•	border-width
•	border-spacing
•	bottom
•	clip
•	color
•	crop
•	font-size
•	font-weight
•	height
•	left
•	letter-spacing
•	line-height
•	margin
•	max-height
•	max-width
•	min-height
•	min-width
•	opacity
•	outline-color
•	outline-offset
•	outline-width
•	padding
•	right
•	text-indent
•	text-shadow
•	top
•	vertical-align
•	visibility
•	width
•	word-spacing
•	z-index

## **Animations**

JavaScript animations are done by programming gradual changes in an element's style. The changes are called by a timer. When the timer interval is small, the animation looks continuous

•	Once you have declared the animation-name property on an element, animations behave similarly to transitions.

•	animations run their cycle once from beginning to end and then stop. To have an animation repeat itself numerous times the animation-iteration-count property may be used

•	The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively.

•	The animation-fill-mode property accepts four keyword values, including none, forwards, backwards, and both.

## **8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS**
 
 1. **Fade in**

Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.
```
.fade
{ opacity:0.5;}
```

2. **Change color**

3. **Grow & Shrink**
To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.
```
.grow:hover
{  -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
 transform: scale(1.3);}
```
```
.shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);
}
```
4. **Rotate elements**
```
.rotate:hover
{ -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);}
```
5. **Square to circle**
```
.circle:hover
{ border-radius:50%;}
```


6. **3D shadow**
```
.threed:hover{ box-shadow: 
   1px 1px #53a7ea,
   2px 2px #53a7ea,
    3px 3px #53a7ea;
    -webkit-transform: translateX(-3px);
        transform: translateX(-3px);}
```

7. **Swing**

```
@-webkit-keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
       transform: translateX(-5px);
    }

@keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
        transform: translateX(-5px);
    }

```

8. **Inset border**

```
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;

}
```


