# JS-Hindi

JavaScript Series

# Variable Declaration in JavaScript

1. var a = 5;
2. let a = 8;
3. const a = 6;

print method in javascript
=====================================
document.write();
alert();
console.log();

# Comment In JavaScript

1)Single Line Comment
================================  
 //
2)Multi Line Comment
============================  
 /\* \*/

# Data Type

# 1.Primitive Datatype

    a)number
    let a = 5;
    document.write(a);
    b)string
    let a = "Asmit";
    document.write(a);
    c)boolean
    let a =5;
    let b= 6
    c = a>b;
    document.write(c)
    d)null
    let a = null;
    e)undefined
    let a;

# 2.Non Primitive Datatype

    a)Object
    b)array
    c)function

Implicit
======================================
let a= '3'+5;
console.log(a);
console.log(typeof a)  
(Result:35)
Result: (string)

---

let a = '3'-2;
console.log(a);
console.log(type a);
Result:1
Result:(number)

---

let a = '3'+null;
console.log(a);
console.log(typeof a);
(Result:3null)
Result:(String)

# Explicit

result = null ;
result=String(result);
console.log(result);
console.log(typeof result);

Result: null
Result: String

---

let a = 30.50;
a=parseInt(a)
console.log(a);
console.log(typeof a);
Result:30
Result: Number

---

let a = '30.50';
a=parseInt(a)
console.log(a);
console.log(typeof a);
Result:30
Result: Number

# Operators

## Arithmatic Operator

console.log(4+10);
result:14
console.log(4-2);
result:2
console.log(2\*2);
result:4
console.log(2/2);
result:1
console.log(2%2);
result:0
console.log(5\*\*5);
result:3125

===============================
Increment and Dcrement operator

---

let a= 5
// a++;  
 ++a;
console.log(a);
result:6

let b =5;
// --b;
b--;
console.log(b);
result:4

Comparison Operator
=================================
let a = 5;
let b = 6;
let comp = a>b;
console.log(comp);
result:false

---

let a = 5;
let b = 5;
let comp = a==b;
console.log(comp);
result:true

---

let a = '5';
let b = 5;
let comp = a==b;
console.log(comp);
result:true

---

let a = '5';
let b = 5;
let comp = a===b;  
console.log(comp);
result:false

---

let a = 5;
let b = 6;
let comp = a!=b;
console.log(comp);
result:true

================================
logical operator
------------------
console.log(4>3 || 5>5);
result: true
console.log(5<6 && 6<5);
result:false

Conditional Operator
==================================
if:
---------------
  let age = 19;
  if (age >= 18) {
    document.write("You Can Vote");
  }

  result:You Can Vote


  if-else
  ------------------------
   let age = 15;
 if (age >= 18) {
   document.write("You Can Vote");
 }
 else{
   document.write("You Can not Vote");
 }

result:You Can not Vote

nested
------------------------


