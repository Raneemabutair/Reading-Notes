
# HTML Images; CSS Color & Text

## Images 

A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

  The <img> element is used to add images to a web page.
   
   ```
<img  src="images/quokka.jpg" alt="A family of quokka”/>
  ```

you must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.
We can control our images by using a lot of codes such as :

•	Height & Width of Images:

```
<img src="images/quokka.jpg" alt="A family of 
 quokka" width="600" height="450" />
```

•	Where to Place Images in Your Code:

```
<p><img src="images/bird.gif" alt="Bird" width="100" 
height="100" />There are around 10,000 living 
 species of birds that inhabit different 
 ecosystems from the Arctic to the Antarctic</p>
```

•	Aligning Images Horizontally or Vertically

```
Align =” left”
Align =” right”
Align =” up”
Align =” bottom”
Align=”middle”
```



**Three Rules for Creating Images**

  * save images in the right format

  * save images at the right size
  
  * se the correct resolution


## Color

Color can really bring your pages to life.The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways: 

•	**RGB**  values These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

•	**HEX**  codes These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80 

•	**Color names** There are 147 predefined color names that are recognized by browsers. For example: DarkCyan



**It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content)**


## Text

  * There are properties to control the choice of font, size, weight, style, and spacing.

  * if you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.

  * You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.


## JPEG vs PNG vs GIF

  * JPEG images don’t support transparency and are hence not usable for such cases.

  * PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency).

  * GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency).

