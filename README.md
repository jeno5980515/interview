# interview

## Overrall
* How do you measure the performance of your code?
* Explain Devops.

## Computer Organization and Architecture
* Compare pass by value, reference and address.  
* Compare Global, Stack and Heap.
* How to compare two floats?

## Web 
* Different between session, cookie and localstorage? 
* Compare WebSocket, Polling, Long-Polling and Streaming. 
* Explain REST.
* Different between GET and POST.
* Explain OAuth.
* How to improve SEO?
* Different between HTTP and HTTPS?
* Different between HTTP/1.1 and HTTP/2?

## Front-end 
* How to (not) hide a mobile browser's address bar?
* How to solve Browser Compatibility issues?
* How to improve the perfornamce? 
* Explain event bubbling.  
* Event Bind and Event Delegate.
* Explain AMP and RWD.
* Talk about CORS.
* CSS Animations vs Javascript Animations

## HTML
* Talk about HTML5.
* HTML5 Semantic

## CSS 
* How to center an element? 
* Talk about px, rem and em.
* Box Model
* Talk about position.
* Explain pseudo elements   
* Difference between @import and link?
* Talk about CSS3.
* Explain margin collapsing.
* Remove space between two inline-block elements.
* Use CSS to draw triangle.

## JavaScript     
* What is the difference between undefined and not defined in JavaScript? 
* Different between Call, Apply and Bind ?  
* Different between var and let?
* Talk about ES6.
* Talk about Reduce, Map and Foreach.
* Talk about Symbol.
* Talk about Design Patterns.
* Explain "use strict".
* Explain IIFE.
* Explain "this".
* Explain Lifetime of JavaScript variables.
* Explain hoisting.
* Implement filter.
* Implement forEach, map and reduce, and break the loop at specific condition.
* Implement bind, call, apply.
* Implement Promise.
* Implement Debounce.
* Implement Curry.
* Implement Compose and Pipe.
* Implement the adder function to pass all assert 
* Implement retry. 
* How to use `Promise.all()` to wait all promise finished, even reject?
```
var adder = function(n){......}
var add_one = adder(1);
var add_two = adder(2);	
assert(add_one(5) == 6); 
assert(add_two(8) == 10);   
```
* Equal or not? 
```
console.log( 0 == false )
console.log( 0 === false )
if( {} ) alert(true); 						
if( [] ) alert(true); 
if( “” ) alert(true);
```

## Java 
* Different between Overloading and Overriding.
* Does Java support multiple inheritance? If not, can we simulate it?  

## SQL
* Explain join.  

## OS
* Different between Process and Thread.
* Explain deadlock.
* Explain Race Condition and how to avoid it?  

## Data Structure & Algorithm
* Multiple by 8 without using multiplication or addition.
* How to find the longest palindromic substring?
* Given an array and a value, remove all elements of that > value in place* and return the new length. The order of elements can be changed. It doesn't matter what you leave beyond the new length. And the all elements of the array in new length should <= value. *(in place: You can’t create new array to store result, just use original array)
* Given two binary strings, return their sum (also a binary string). For example, a = "11" b = "1" Return "100". You can assume "0" < a, b, a+b < “11111111111111111111” (2^20-1)
* Suppose you have an array of 1000 integers. The integers are in random order, but you know each of the integers is between 1 and 5000 (inclusive). In addition, each number appears only once in the array. Assume that you can access each element of the array only once. Describe an algorithm to sort it. If you used auxiliary storage in your algorithm, can you find an algorithm that remains O(n) space complexity?
* Given a string with only character '(' and/or ')', find the number K that the amount of '(' in the left part of K is same as the amount of ')' in the right part.
* Implement Topological Sort.
