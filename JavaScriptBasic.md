# **Intoduction of JavaScript** 
* JavaScript one of  most famous programmaning laguage in the world .

* JavaScript is initially designed to intract the element of web page .

* The help of javascript we can create a dynamic web page .
* JavaScript easy to learn .

* All popular web browser support  javascript .

* JavaScript is both client side or server side.


## **History of JavaScript** 
* There are 1.6 million website in the world , of which 95% are run on JavaScript .

* In mid nineties and the boom of internet at that time there was two popular browser .

  * Internet Explorer

  * Netscap

* In september 1995  **Netscap company**  hire a developer , whose name is **Brendan Eich** . 
* **Brendan Eich** developed *JavaScript* in ten days . 

*  First name of Javascript is **Mocha** later **LiveScript** current now we know as **JavaScript**


## **Why JavaScript is so popular :-** 
 
 * Easy to learn .
 * Open source but standardized by - **ECMA INTERNATIONAL** .
 * We can use server side or client side .
 * Good performance


 ## **Difference between javascript and java**
 ![WhatsApp Image 2021-08-04 at 8 17 59 PM](https://user-images.githubusercontent.com/88458111/128250527-f364454c-3f01-47c9-a76b-a9de2d507e8c.jpeg)







## **Feacture of JavaScript :-** 
* Interpreted language 

* Objecr based language 

* Scripting language 

* In every browser there is javascript enginee.




## **Variable :-**

> Variable is container that contain a value. 

```
var a =  10;
var b =  20;

```


* In JavaScript  there is two type of variable 

  * Local variable 

  * Global variable 


* **Local variable** :-  local variable define inside a function and it is access within function .

* **Global variable** :- Global variable define outside of a function and it is access in whole program .

**Example**
```JavaScript
var a = 10;         // Global Variable 


function add(){
    var b = 20;      // Local Variable 
    var c = a+b;    // Here we call global variable inside function 
    Console.log(c)

}
add();              // Function call 
Console.log(a)     // Global variabl outside of function

Output :- 30
          10
```

## **Data Type :-** 

* In java script there is two type of data type .

  * Primitive datatype

  * Non-Primitive data type 


1)**Primitive data type** :-

| Data Type | Used for |
|-----------|----------|
| String    | It is used to represent characters value. ex :-"vivek"|
| Number    | It is used to represent integar/number value. ex :- 1,2,3,10,21|
| Boolean   | It is used to represent either true or false .|
| Undefined |  It is used to represent undefined .|
| Null      |  It is used to represent null value .

2) **Non-Primitive Data type** :-

| Data Type | Used For |
| ----------|----------|
| Object	    | It is used to represents instance through which we can access members|
| Array     |It is used to represents group of similar values|
| RegExp	|represents regular expression|



## **OPERATORS IN JAVASCRIPT :-**
Operator are symbol that is used to perform some opeartion on oprands.

There are following type of operator that is use in javascript .

1) **Airthmetic Operators**

2) **Assigment Operators**

3) **Comparison Opearators**

4) **Logical Opearators** 

5) **Bitwise Opearators**

6) **Type Opearators**

>**Aithmetic Operators** :- *It is used to perform Airthmetic operation on oprands.*

|**Operators**| **operation** | **Used for**  | **Example** |
|-------------|---------------|---------------|---------|
|  **+**      | Addition      | It is use for add two number | 30+21 = 51|
| **-**    | Subtraction   | It is use for subtract two number | 40-10 = 30|
| __*__ | Multiplicaton |  This is use for multiplication of number | 12 * 4 = 48|
| **/** | Division | Divide two number | 4/2= 2|
| **%** | Module | It is used for find a  remainder|3/2= 1|
|**++** | Increment | Increment a value | var x=21; var x=++; Now x=21; |
| **--**| Decrement | Decrease a value | var y=10;  var y= --; Now y=9;|

**Comparison Opearators**

| **Operators** | **operation** | **Example** |
|---------------|---------------|-------------|
| **==**        | Is equal to	| 30==40 =false|
| **===**	    |Identical (equal and of same type)|	20==30 = false|
| **!=**| Not equal to|	10!=20 = true|
| **!==**	|Not Identical	|10!==10 = false|
|**>**|Greater than |30>10 = true |
|**>=**|	Greater than or equal to|	20>=10 = true |
|**<**|Less than	|40<10 = false|
|**<=**	|Less than or equal to	|20<=10 = false|


## **Condition Statement :-**

```
There is three type of Condition Statement in javascript.
```

* if Statement 
* if else Statement
* if else if Statement

* if Statement :-
> if statement execute when condition is true.

**Syntax** :- 
```
if(condition){
  statement;
}
```

**Example**
```
var age = 20;
if(age>18){
  Console.log("you can vote ")
}


Output:-
        you can vote 
```

**if else statement :-**
> if condition is true then execute if block or false then execute else block --

**Syntax**
```
if(condition){
  statement1
}
else{
  Statement2
}
```
**Example**
```
var num =12;
if(num%2==0){
  Console.log(" even number")
}
else {
  Console.log(" Odd number")
}

Output:- 
        even number
```        
**if else if**


**Syntax**
```
if(condition1){  
// if condition1 is true  
}  
else if(condition2){  
// if condition2 is true  
}  
else if(condition3){  
// if condition3 is true  
}  
else{  
// if no condition is true  
}  
```
**Example**
```
var a = 30; 
    b = 40;
if (a > b) {
    console.log('a is greater than b');
} else if (a < b) {
    console.log('a is less than b');
} else {
    console.log('a is equal to b');
}

Output:- a is less than b
```
## Switch Case:-
> Switch case is a flow control statement ,in switch case we execute one code for multiple condition.

**Syntax**
```
switch(condition){
  case statement1:
  statement_1;
  break;
  case statement_2:
  statement_2;
  break;
  case statement_3:
  statement_3;
  break;
  default:
  default_statement;
}
```
> **break Statement**:- *Break is nothing but it is keyword that  is use to break the flow of program/loop.*

>**Continue Statement** :-
*Continue statement used to  in skip the current iteration of loop and immediately jumps to the next one.*


## **Loop in javascript :-** *There are four type of loop in javascript*
* while loop
* for while loop
* do while  loop
* for in loop 



**while loop** 

*Syntax* 
```
while(condition){
  statement 
}
```

**for loop**

*Syntax*
```
for (initialization; condition; post-expression) {
    // statements
}
```
**do While loop**

*Syntax*
```
do {
  statement(s);
} while(expression);
```






























