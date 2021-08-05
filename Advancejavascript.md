# **Function :-**
*Function is block of code it execute when its call ,  with the help of function we avoid repeating the same code again and again . 
Function provide reuse ability of code.*

**Syntax of creating a function**
```javascript

function functionName(parameter){       // Creating function
    statement 

}

functionName(arguments);            // Calling function
```


## **Function scope :-**

**Example** :- 
```javascript
var a ;
var a ;
Console.log(a);
a = 10;
console.log(a);
a = 20;

---------------------------------------
Output :- undefined 
          10
```
```javascript 
var a = 10;        // Local scope
var b = "ok"
console.log(1,a+b);
a = 20
function hello(){
    var a = 3         // Global scope
    Console.log(2,a)
}
hello();
console.log(3,a);
a = 10;
console.log(4,a);


output--------------------
1 Undefinedok
2 3
3 20
4 10
```

## **Call by Value Vs Call by Reference :-**



![call](https://user-images.githubusercontent.com/88458111/128245158-7b2bca7d-6d54-4b08-bf57-ff3de6bd06a3.jpg)



* Call  by value always use with primitive data type.
* Call by refrence use with non-primitive data type.


**Example of call by value**
```javascript
var a = 10;
var b = a;
var b = a+11;  // we update the value of b  
console.log(a);
console.log(b);// now b = 21
output-------------------
10
21
```
**Example of call by refrence**
```javascript
const obj1 ={
    user : "vivek",
    pass : "dubey"
}
const obj2 =obj1;
obj2.pass = "Abcd";
console.log(obj1);
console.log(obj2);

output------------------------
{ user: 'vivek', pass: 'Abcd' }
{ user: 'vivek', pass: 'Abcd' }
```

## **Constructor** 
> *Constuctor is method and it is special  type of method ,
which are basically special function that prepare new instance of an object for use.  With the help of constructor keyword we can declare constructor method.* 

**Example**
```javascript
function Mobile(){
    this.model='3310';
    this.price = function(){
        document.write(this.model +"Price Rs.4000");
    }
}
var nokia = new Mobile();
nokia.price();

output--------------------
3310 Price Rs.4000

```


## **ARRAY  , OBJECT  , STRING :-**


1) **Array :-**
>*An array is a special variable that can store multiple values at a time.Array is an ordered list of values. Each value is called an element specified by an index.*

**Syntax**
> **var arrayname=[item1, item2, item3, itemN]**


|**Built in method** |**Used for** |
|-----------------|-----------|
|Indexof()        |  To check element in array and retrun the index of first match|
| push( ) |  add new items to the end of an array.|
| reverse|                           reverse the element in array|
| toString()  |                      Convert array to string |
| join()|                            join all array element into string  |
| pop()|                     To remove element at end of aaray |
|Shift() |               Remove the first array element |
|Unshift()|                  Add the a new element at the beginning of an array|
|index[]|                    Access the element of an array|
|delete |                    Delete element in array|
|Splice()|           used to add new item in an array |
|concat()|               Add two array |
|Finding max |                   find max value in array |


## **Object**
> *Object is real world entity that having state and behavior. In javascript everything is object because javascript is object base language . In javascript we don't create class to get object , we can direct create object.*


> *new keyword is use to create object in javascript*

**Syntax**
```javascript
var objectname = new object();
```
**Example**
```javascript
const person = {
  firstName: "Vivek",
  lastName: "dubey",
  age: 21,

};
```


**Javascript Method**


|**Method** |**Used for** |
|-----------|-------------|
| **Object.create()** | this is used to ceate a object |
| Object.assign() | This is used to merge source object into target object with properties.|
| Object.is() | Used  to check two value are same |
| Object.key() | This used to calculate manykeys we have in object .|
|  Object.values()| This is used to retrun an array of value.|
| Object.defineProperty() | Define behavior attributes of the properties.|
| Object.toString()| This is used to convert object in string |

## String :-

>*String is used to store character in single or double quotes*
Syntax 
```javascript 
var Stringname="Stingvalue"
```
**Example**
```javascript
var name="vivek";
console.log(name);

output-------
vivek
```

| **Method** | **Used for** |
|------------|--------------|
| Concat()   | Add two  string |
| Search()   | It is use to search specific item in a string|
| replace()  | It is use to replace element in a string |
|toLowerCase()| It is use to convert given string into lower case letter.|
|toUpperCase()| Covert givven string into upper case letter|
|length()| Used to check lenght of string|
|Trim()|  IT is use to remove white space|
| indexof()  | Retrun index positin of string|











