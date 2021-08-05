# **What is ES6** 

* *It is sixth edition of edition of **ECMA Script** that is reason it knowns as **ES6***.
* *It was intoduce in 2015.*
* *It is add some additonal feature in javascript .*
* *ES6 is add two new feature  to declare a variable in javascript .*
  * *let* 
  * *const*

## **let :-**
* *let keywords was introduce in ES6 in 2015.*
* *let is keyword that is used to declare variable .*
* *It is Similar to var keywords .*
* *let is can't be **Redeclared** .*
* *let variable have block scope .* 

**Example**
```javascript
let name = "vivek";
let a = 10;
console.log(name)
console.log(a)

output------------------
vivek
10

```

## **const :-** 
* *const is keyword that is use to declare variablein javascript .*
* *It was also intoduce in 2015 throught ES6.*
* *const variable can't be **Redeclared** or **Reassigned**.* 
* *It also have block scope.*


**Example**

```javascript
const name = "vivek";
const a = 10;
console.log(name)
console.log(a)

output------------------
vivek
10
```
## **Different between var , let , const** 

|**var**           | **let**          | **const**       |
|-----------------|--------------------|----------------|
| *Value declare with var keyword*| *value declare with let keyword* |  *value declare with let keyword*|
| *var have function scoped* | *let have block scoped* | *const also have block scoped* |
| *In var value can be change* | *In let value can't be  change* | *In const value can't change* |
|*var is part of **ES5**.* | *let is part of **ES6**.* | *const is also part of **ES6**.* |
|*var can be redeclared*  | *let can't be redeclared* |  *const  can't be redeclared* |



## **Built-in function in javascript :-**

**There are some built-in function in javascript**


* **Arrow Function :-**
> With the help of arrow we write a code in different way or also in shortest way .

**Example**
```javasript

 const name =()=>{
     console.log("Hi my self Vivek Dubey")

 }
 name();


output ----------
Hi my self Vivek Dubey 
```  

* **Default parameters** :-
>*Default parameters is use  to be initialized with default values if no value or undefined is passed.*

**Example**
```javascript
const multiply =(a,b=4) =>{
  console.log(a*b)
}

multiply(10);

output ------
40

```








