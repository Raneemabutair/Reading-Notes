# Jon Duckett JAVASCRIPT & JQUERY

## Comparison and logical operators

**Operators are the constructs that can manipulate the values of the operands, and we some types of Operators such as:**

* **Comparison Operators,** *which allow you to evaluate a statement by comparing one value in the script with the result that you are expect and the result will be always two choices ether (Yes or No) (Boolean), the operator includes:*

   |==|===|!==|<|>|<=|>=|!=|
   |--|---|---|-|-|--|--|--|
   |Equal to|Strict equal to (both of the data type and value are the same)|Strict not equal to (both of the data type and value are the not same)|Less than|Greater than|Less than or equal to|Greater than or equal to|Not equal to|

* **Logical Operators,** *a logical operator Logical operators are used to determine the logic between variables or values as many times as you want,*

  * **&& (logical And)** ex:
   ((2<5) && (1>=2)) 
*The result will be False Because we have T & F* 
  * **||  (logical Or)** ex:
  *((2<5) || (2<1))
The result will be True Because we have T & T*
  * **! (logical Not)** ex:
  *!(2>1)
The result will be False Because the result is True*


## **Loops**
It’s a code block that will keep running as long as the returns are true, we have three types of loops:

1.	**(For) Loop** if you want to run your codes a specific number of times.
2.	**(While) Loop** if you don’t know how many times the code should run.
3.	**(Do While) Loop** it’s the same as the while loop with one difference that it will always run the statement inside the curly braces at least once even if the condition is false. 

***Example (FOR LOOP)***


           *Instead of writing:*
     text += cars[0] + "<sf>";
     text += cars[1] + "<sf>";
     text += cars[2] + "<sf>";
     text += cars[3] + "<sf>";
         
         
         *you can write* 
         var i;
         for (i = 0; i < cars.length; i++) {
         text += cars[i] + "<sf>";


