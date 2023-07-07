# frontend-learnings
---------------------**PHASE-1: Covering core JS**----------------------------------
**Javascript Learnings**:  

Try out at the end of PHASE-1:  
* Client-side validation,
* Dynamic drop-down menus,
* Displaying date and time,
* Displaying pop-up windows and dialog boxes (like an alert dialog box, confirm dialog box and prompt dialog box),
* Displaying clocks etc.

**Variables**:  
Global vs local variables  
Let, const, var difference & their use case.  

**Data types**:  
Primitive vs non-primitive  
Primitive: string, number, boolean, undefined, null  
Non-primitive: Object, array, regEx  
How to check data type of var/const/let  
Difference b/w undefind, null  
What is the datatype of functions ?  

**Operations**:  
++,—, %, equality Check :   ===, ==  
assignment: +=,-=,  
Special: (a ? B : c ), delete, in, instance, new, typeof, void, yield  

If…statement, switch , for, while loop syntaxes:  

If (expression) {}  
expression = a  , !!a (converting to true boolean => a = ‘’ / undefined gives “false”), !a (negating..if a = ‘’ / undefined / 0 gives “true”)  
Ex:let a; expression can be  a >0 , a == 10, a === ’10’, a, !a, !!a, myfunction(a)  
Switch statement.  

**Functions**:  
Normal functions.. constructor way, arrow functions, differences    
Declaring functions both,   
how to get list of arguments passed to functions  while calling inside function definition  hint: arguments object.  
Different ways of calling functions & differences: call, apply bind, toString  

Understanding the usage of “this” keyword inside functions.  
Understanding of closures (watch 2 videos, enough) 

An example explaining declaring functions inside another function.  
Example passing function as argument to another function.  
How function execution happens in browser ( youtube 2 videos, enough) ?

**Class**:
How to create a class..constructor,  class vs function
members of class: data variables, functions
how to create objects from class, assign values, call method functions
static methods in class ?

**Objects**:  
Different ways of creating objects  
Methods: keys, entries, values  

**Arrays**:  
Different ways of creating arrays  
Methods:   
Object methods,  
Level1: Map, filter, reduce, find, includes, findIndex, forEach,  join, slice, splice, toString  
Level2:Shift, unshift, push, pop, reverse,  
Level3:Concat, flat, flatMap, fill, reduceRight  

**Strings**:  
Different ways of creating strings  
Methods:  
Level1: chartAt, indexOf, concat, substr, toLowerCase, toUpperCase, trim, split  
Level2: substring, replace, valueOf, search  

**Date**: (used for displaying running time in browser like: clock)  
Creating date objects.  
Methods:  
Now, get/set day, date, month, year, hours, toString.  

**Math**:   
Abs, ceil, floor, min, max, random

**Number**:  
parseInt, parseFloat, toString, isInteger

——— **Must know JS built-in functions**———————   
setTimeout  
setInterval  
clearTimeout  
clearInterval  

——————— **BOM (browser object model)**————————  
Window  
History  
Navigation  
Location  

Explore above objects & how they are used in JS code

———————— **Basic DOM queryselectors for DOM manipulations** ———————

getElementById.   
getElementsByClassName.   
getElementsByName. 
getElementsByTagName.  
innerHTML, inner text difference ?   

-----------**HTML DOM Events**--------------------

try out different Events available for below DOM input elements:

radio  
checkbox  
dropdown  
textbox  
button  
keyup, keydown events  

----------**Assignments**------------------
1. how to Load js file, style sheet into browser, when HTML file is loaded & assign some functions to DOM elements events, styles.


--------------**PHASE-2 Covering Browser**-------------------------   
**Storages**   
Localstorage   
sessionstorage   
cookies   

**Fetching API: fetch, axios: GET,POST,PUT,DEL**  
promise  
callbacks  
async...await  
fetch api  
axios library  
HTTP status codes  

**CSS in depth**  
display  
common styles  

**Closures in JS**


##############**Assignments**############################

----------**PHASE-3: Advanced**-----------------

Eventpropogation  
preventdefault  
EventBubbling  
EventThrotling  
EventDelegation  
debouncing  
how to stop eventPropogation, default behaviour ?.  


