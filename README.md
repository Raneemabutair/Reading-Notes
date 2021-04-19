# Object-Oriented Programming, HTML Tables

## Domain modeling
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

1.	When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2.	Model its attributes with a constructor function that defines and initializes properties.
3.	Model its behaviors with small methods that focus on doing one job well.
4.	Create instances using the new keyword followed by a call to a constructor function.
5.	Store the newly created object in a variable so you can access its properties and methods from outside.
6.	Use this variable within methods so you can access the object's properties and methods from inside

## Tables

A table represents information in a grid format.
The ```<table>``` element is used to create a table. The contents of the table are written out row by row.
You indicate the start of each row using the opening ```<trt>``` tag
Each cell of a table is represented using ```<td>``` element.
```
<table>
 <tr>
 <td>15</td>
 <td>15</td>
 <td>30</td>
 </tr>
 <tr>
 <td>45</td>
 <td>60</td>
 <td>45</td>
 </tr>
 <tr>
 <td>60</td>
 <td>90</td>
 <td>90</td>
 </tr>
</table>
```

The element ```<th>``` is used just like the```<td>```
 element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)


You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
For long tables you can split the table into a ```<thead>, ```
```<tbody>```, and ```<tfoot>.```

```
<html>
<head>
 <title>Tables</title>
</head>
<body>
 <table>
 <thead>
 <tr>
 <th></th>
 <th scope="col">Home starter hosting</th>
 <th scope="col">Premium business hosting</th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <th scope="row">Disk space</th>
 <td>250mb</td>
 <td>1gb</td>
 </tr>
 <tr>
 <th scope="row">Bandwidth</th>
 <td>5gb per month</td>
 <td>50gb per month</td>
 </tr>
 <!-- more rows like the two above here -->
 </tbody>
 <tfoot>
 <tr>
 <td></td>
 <td colspan="2">Sign up now and save 10%!</td>
 </tr>
 </tfoot>
 </table>
</body>
</html>
```
## Functions, Methods, and Objects

***Objects*** 

JavaScript is designed on a simple object-based paradigm. An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. In addition to objects that are predefined in the browser, you can define your own objects. This chapter describes how to use objects, properties, functions, and methods, and how to create your own objects.


```
var myCar = new Object();
myCar.make = 'Ford';
myCar.model = 'Mustang';
myCar.year = 1969;
```

***Functions*** 
***
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

```
function square(number) {
  return number * number;
}
```
Calling the function actually performs the specified actions with the indicated parameters. For example, if you define the function function name, you could call it as follows:
```
functionname ();
```




***Methods***
JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Methods are functions stored as object properties.
Adding New Methods
Defining methods to an object is done inside the constructor function:
```
function person(firstName, lastName, age, eyeColor) {
    this.firstName = firstName; 
    this.lastName = lastName;
    this.age = age;
    this.eyeColor = eyeColor;
    this.changeName = function (name) {
        this.lastName = name;
    };
}
```

<img src="https://image.slidesharecdn.com/javascript-1193630506982978-3/95/javascript-17-728.jpg?cb=1193601707  ">

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDCowqVvu2ootzAnBsBVXi-TeFZ9qtKgkRvz5rLEfkeU1agdPk2zfyTYoKpx6eFz3nzbI&usqp=CAU   ">