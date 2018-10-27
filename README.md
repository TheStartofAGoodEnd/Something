# Something

JavaScript:
Most used engines in JavaScript:
	- V8 - For Chrome and Opera;
             - SpiderMonkey - For FireFox;
             - SquirrelFish - For Safari.
Basic theory before the code:
In basic terms what engines do are compilations of the files to be easly executed by the computer.
<script> tag is used to increment JavaScript code in to a HTML file
<script src=""> tag is used to import a file that is in a diferent folder with his path in the "" and is used to more complex pieces of code because it goes to the browser cache.
The code:
alert(); - Used to show something in the browser;
'use strict' - You need to put this in the top of your code and it then you can writen in the new form;
Variables - It is a "named storage" for data, strings, numbers, integers, functions, arrays,...(To create one you need to use let (supposing that you used strict));
VariableNaming - The name must contain only letters, digits, symbols "$", "_". The first character can't be a number. When the name has more than one word you use camelCase;
Const - Used to create a value that won't change. Normally the name is written in capital letters with _ in the space;
Data Types:
Number - A variable can have stored a integer or a floating number. The operations that exist with the numbers are:
	- Multiplication - *;
	- Division - /;
	- Additiom - +;
	- Subtraction - -.
NaN - Represents an error when you do an operation with a string and a number;
String - Needs to be quoted with "" or '' and `` to wrap variables in to strings;
Bolleans - Can have a value or true or false;
null - That doesn't have any information inside or have an unknown value;
undefined - Means that any value is assigned to some variable;
Objects - They are used to store more complex and bigger amounts of data and they aren't primitives;
typeof x - To see what represent the value inside the variable;
String(); - Function that converts any type of data in to string;
Number(); - Function that numbers that are in strings to numbers(if you do the conversion in certain values you get: null = 0; true = 1; false = 0; "" = 0; "Hello" = NaN);
If a number is added to a string the number transforms in to a string and they get concatenated ( 1 + "2" = "12");
Boolean(); - Converts any thing in to true or false. Basically any thing that is intuitivelly empty is coverted to false other wise is converted to true);
Operands - It's a number from a mathematical expression. Example: 1 * 2 = 2. The left operand is 1 and the right one is 2.
Concatenation - It's a method that is used to add to strings and numbers with strings. It only works with the plus sign. It can be used to convert non numbers to numbers. Example: "my" + "string" = "mystring", 1 + "2" = 12, +true = 1 or +"" = 0
++variable or --variable - Is used to incremend or decrement a value by one. If it is used in a separate line it adds or subtract something but if is used for example let a = counter++ it will give the counter value without adding it will only add if you put the plus sings before.
Bitwise operators:
	- && - And;
	- || - Or;
	- ^ - Xor;
	- ~ - Not (Converts into binary code);
	- << - Left sign;
	- >> - Right sign;
	- >>> - Zero-fill right shift;
	- ! - The not operator;
	- !! - The bollean converter;
	- any operation= - Will give to the operation to the variable that you want and you need to put it before;
	- , - It is used to throw away the the last part of an operation. Example: let a = 1 + 2, 3 + 4, it will be equal to 3 because the last part is thrown away.
Comparisons:
	- < - Less sign;
	- > - Greater sing;
	- >= - Greater or equal sign;
	- <= - Less or equal sign;
	- == or ===- Equal sign;
	- != or !== - Diferent sign.
alert(); - This shows a message and pauses the script until the user click in the "OK";
.toUpperCase(); - It is used to put a string in capital letters;
prompt(tittle, default); - This shows a text message and a white box that can be used to type. The title is the message and the defualt is the first thing that will apear in the white box.
comfirm(); - This shows a message with two buttons OK and Cancel, and if you click on them the answer to the message will be true if you click on OK and false if you click on Cancel.
if statement if (variable === 2015) {} - It is used to check the value of something depending on what you want and if the value has the relashion that you want the code in the if will be read;
else clause - It is used next to if and it normally checks when the conditions is wrong and if it is it reads the code in the else. This can be optional;
else if clause - It is used like if but you can do it several times;
let variable = condition ? value1 : value2; - The '?' is used to do a shorter version of 'if'. The condition is evaluated and if it is true returns value1 otherwise value2. You can use multiple lines to but it will only have the condition and one value, example, (age < 18) ? "Hello" : and you can add in other line the next codition with the value;
while (condition) {} - The "while" loop it is a way to repeat code easly and it works by putting a condition that will be checked if it is true or not and if it is the loop willl execute his code until the condition gets wrong;
do { // loop body // } while (condition); - It works like "while" loop, the only difference is the body will always be executed at least one time;
for (begin; condition; step) { // Body// } - The "for" loop it is the most often used and it goes like this first in the begin it will have a variable that is equal to something in the condition will have a condition that checks if the begin is true in realshionship with other value and then runs the code, but in the final it will read the step that increments or decrements the begin;
if (condition) break; - It is used in the "while" loops and it breaks the execution when the condition is falsy;
continue; - It is used in all loops and what it does is it skips a certain itenarition and forces the loop to start a new one;
label: ..... break outer; - It is used to break more efficietly;
switch statement - It is a way to substitute multiple if checks (switch == if, case == else if, default == else); 
function - It is used to make and action that only goes once, it is written like this function doSomething() { // Code // };
Function rules:
	- A variable that is created inside of a function it can't be acessed outside of the function;
	- A function can acess and outer variable, the value if the changed variable only changes after you call the function;
	- Function prefer the local variables instead of the outer variables, so if you have two variables with the same name but one is inside and the other outside of the function when  the variable its called the one that will be used is the local one;
	- In a function you can use parameters and it is written like this function doSomething(num, from) {} it is used to when you call the function you can put the parameters and the function will be in the way that you want;
	- A function can have a return value and that is used in a lot of cases especially in maths and whenever the function gets to the return the function stops running and it will return the value;
	- To name a function normally it is used verbs and in a way that they can describe the most of the function.
Global variable - If you create a variable outside of a function that variable can be acessed in all the code so it is called global variable;
Function expression - It is a different way to create a function, example, let sayHi = function() { //Code// };
Arrow function - It is a different way to create a function, example, let func = (arg, arg,...) => expression;
Debugging:
	- Breakpoints - They are used to stop the JavaScript execution on that lines;
	- debugger; - It is a command that sets a breakpoints in the code editor instead of going to the browser and set it up there;
	- Watch - It will show you curent values for any  expressions;
	- Call Stack - It will jump to the outer function, if you setted a breakpoint on one;
	- Scope - It will show you the local and global variables and their values;
	- Go forward - It will jump to the next breakpoint;
	- Make a step - It will run the next command;
	- Go down - It will run the next script action, it goes more deeply than "Make a step";
	- Go up - It will continue the execution till the end of the current function;
	- Slash in something - Enable/Disable all breakpoints;
	- The pause buttom - Enable/Disable automatic pause in case of an error, you can see in detail what make the script stop;
	- console.log(); - It is used to output something in to the console.
Objects:
	- They are used to store whatever amount of data that you want, they store data in form off properties that have a name and a value, example, "key: value", key is the name off the property and value is the value inside key. Function are objects to;
	- Syntaxe - The constructor one, let obj = new Object(); or the literal one, let obj = {}; 
	- To read properties - obj.propertyName;
	- To add properties - obj.propertyName = "Jhon";
	- To remove properties - delete obj.propertyName;
	- Multiword properties need - "";
	- To read/add/remove multiword properties - obj["Multiword property"];
	- To check if exist any property in the object - "propertyName" in object;
	- To loop an object - for (let key in object) {// To alert the name of the properties alert(key) // To alert  the value of the properties alert(obj[key]) };
	- Loop order in objects is from the first created to the last one, if the properties are integers it will be looped in a numeral order;
	- A variable stores not the object itself but, its "adress in memory", in other words " a reference to it", so if you create another variable and set it equal to some object you have the same object in both variables;
	- If you compare an empty object that is stored in diferente variables it is equal, but if you have two diferente empty objects in diferente variables they are not equal;
	- To clone an object - let clone = {}; for (let key in user) { clone[key] = obj[key] };
	- Diferente way off clonning an object - Object.assign(clone, obj); It copys obj properties and values to clone.
	- Multiple objects - You can create multiple objects with this syntax, function User(name) {this.properties}; let user = new User("Jack");  
Reachability - You need to be carefull because if a global variables is connected with some properties and the properties are all connected with themselfs, if you remove the main connection everything stops working;
Symbols - You can create a symbol by typing Symbol("Descripton that you want") it is used to hide porperties and symbols are special because to diferente symbols can have both the same name. Symbol.for() is used to create symbols with the vairable properties so now you can't have diferente symbols with the same name. Symbol.keyFor(variable) it is used to see the descreption of the symbol (needs to be global symbol);
This - It is used to access the object, a method can use the this keyword. It's usefull because if you clone the object it won't work if you did use the name of the object, so it's better to use this instead. You can use it to create a variable that is common in all the properties of the object (usefull when working with functions);
Constructor functions - They are used to make your work easier they can simplify for example the object creation as I mentioned earlier but the syntax difference is that they need to have a capital letter in the name of the function, and objects when created they need to come with new Something;
Primitive - There are 6 types of primitives: string, number, boolean, symbol, null and undefined.
Numbers - 
	- Instead of writing a number with 10 zeros we can write 7e10; 
	- Hexadecimal - It is used a lot to write colours;
	- ..toString(n) - It converts the number into a string. N determinates the number base it can be 16 (hexadecial), 2 (binary) and 36 (a to Z and A to Z and the latin alphabet);
	- Math.floor - It rounds down every decimal part;
	- Math.ceil - It rounds up every decimal part;
	- Math.round - It rounds to the nearest integer;
	- Math.trund - It removes every thing from the decimal part without rounding;
	- .toFixed(n); - It is used to round a number to the given precision; 
	- Infinity - It is the greatest value of numbers;
	- NaN - It is a representation of "not a number";
	- isNaN() - It is used to convert something to a number and then check if it is equal to NaN;
	- isInfinity() - It convertes numbers that are in strings and it compare to check if is a number after converting;
	- parseInt() - It convertes anything to a number and remove every thing that is not a number and decimal parts (First digit can't be a letter);
	- parseFloat() - It convertes anything to a number and remove every thing that is not a number (First digit can't be a letter);
	- Math.random() - It return a random number from 0 to 1, not including 1;
	- Math.max(a,b,...) or Math.min(a,b,...) - It return the greates or the smallest value from the given numbers;
	- Math.pow(a, b) - It raises a to the given power;
	- Math.max(value1, value2, ...) - It checks in a certain interval of numbers for the biggest one.
String - The textual data in JavaScript is stored in strings.
	- You can use different types of quotes "" or '' and `` to embed something in a string;
	- string.length - It can be used to know the size of the string that you want;
	- string[position] - It is used to check which letter is in that position in that string, the counting starts in zero;
	- let string of "Hello" - It is used in a loop to go for all the letter of the string;
	- "string".toLowerCase() "string".toUpperCase() - They are used to put all the string in lower case or in upper case. string[position].toUpperCase() - It is used to put only one letter or only an interval of letters in UpperCase or LowerCase;
	- "string".includes("shorter string") - It checks for the shorter string in the string;
	- "string".startsWith("short string") - It checks for the shorter string in the beginning;
	- "string".endsWith("short string") - It checks for the shorter string in the beginning;
	- "string".slice(startpostion, endposition) - It is used to cut the interval of characters that you want in the string;
	- "string".substring(startpostion, endposition) - It is used to extract the interval of the string that you want;
	- "string".substr(startpostion, length) - It is used to extract the interval of the string that you want;
	- LowerCase characters have greater value then UpperCase characters;
	- "character".codePointAt(0) - It is used to see the position of the character in JavaScript;
	- string.fromCodePoint(90) - It creates a character of the given position;
	- "string".trim() - It remove any spaces from the beginning and from the end;
	- "string".repeat() - It repeats the string n times.
Array - It is a collection of ordered data, the difference between array and objects is that an objects don't have positions to the elements. Arrays are objects but different types of objects, so if you want to copy the array you will need to do exactly equal to the objects;
	- Array sysntaxes - There are two different ways to create an array, let arr = new Array(); and let arr = [];
	- Every element in the Array have a position that stars in zero;
	- You can call an Array element by his position array[1];
	- You can replace an element for another array[1] = "Fibonacci" or if that position doesn't have any element it will add it array[10] = "Mathematics";
	- You can see the length of an Array by this fruits.length;
	- If you alert an array it will show every element from it;
	- Arrays can store elements from any type;
	- After eatch element in an Array you should put a comma like in objects;
	- You can remove elements from an Array and this syntax will remove it and show it and then doesn't show in the array anymore .pop();
	- You can add an element to the end of an Array .push(), this is equal to array[array.length] = ;
	- You can remove the first element of an Array .shift();
	- You can add an element to the first position of the array .unshift();
	- The .push() and the .unshift() and both add multiple new elements;
	- Arrays have a different syntax to the loop which is for (let elements of array) alert(elements);
	- You can cut the array if you add the less length to the array example, array.length = 1; imagine that array had 6 length then I changed that and now it has one so every element from 6 to 1 is not longer in the array;
	- You can create a multidimensional array example, let array = [[1, 2, 3],	to access you can do it alert(array[1][1]);
									[4, 5, 6],
									[7, 8, 9]];
	- delete array[1] - It will delete the value of the property "1" but it won't remove the property so if you have an array with four elements and you delete a value of a property it will steal have 4 of length;
	- array.splice(start, howManyElementsWillBeDeleted, elementToBeAdded1, elementToBeAdded2,...) - It removes the number of elements that you want from a starting element and it add elements in the position that the others where removed;
	- array.slice(start, end) - It will copy the elements from strings/arrays and will alert them out;
	- array.concat([element1,...]) - It will add the array as much elements as you want. This only works with objects if you add the following property [Symbol.isConcatSpreadable]: true, with that property now all the properties from the object will be added next to the array;
	- array.IndexOf(item, from) - It will search for the item and starting in from, if it doesn't found the item it will return -1;
	- array. lastIndexOf(item, from) - Same as IndexOf but it starts searching from right to left;
	- array.includes(item, from) - Same thing as IndexOf but if it is found it will return true;
	- array.find(function(element, index, array) { } ) - It will search for an element in the array until it find it, when it does will return true;
	- array.map(function(item, index, array) {} ) - It calls the function for each element of the array and returns the array of results;
	- array.sort(); - It will reorder the elements of the array after converting them to strings so it won't be in the corrrect order in numeric terms sometimes;
	- array.reverse(); - It will reverse the order of the elements from the array;
	- str.split(', '); - It will split the string in two and alert the part that doesn't have the comma. It is used when you want to alert something that was written by somenone else but you don't know if they will put a comma or not;
	- array.join(';'); - It will put every element together but separated by a semi colloum;
	- Array.isArray(value) - It will check if the value is an array or not, if it is it will return true if not false.
	- object[Symbol.itenerate] - It is used to allow an object to get for...of looped;
	- let array = Array.from(object); - Array.from(obj) Is used to copy all the properties from the bject into an array. An iterator must have the method named next() that returns an object {done: Boolean, value: any}, here done:true denotes the iteration end, otherwise the value is the next value.
Map - Is a collection of keyed data items, just like an Object, but the main difference is that Map allows keys of any type. To create a map, let map = new Map(). When a map is looped it goes from the order of creation, which is the oposite in relashion to objects;
	- map.set(key, value) – stores the value by the key;
	- map.get(key) – returns the value by the key, undefined if key doesn’t exist in map.
	- map.has(key) – returns true if the key exists, false otherwise;
	- map.delete(key) – removes the value by the key;
	- map.clear() – clears the map;
	- map.size – returns the current element count;
	- new Map(Object.entries({})); - It creates keys and values for them right next of map;
	- map.keys() – returns an iterable for keys;
	- map.values() – returns an iterable for values;
	- map.entries() – returns an iterable for entries [key, value], it’s used by default in for..of.
Set - Is a collection of values, where each value may occur only once. You can't have a repeated value in set;
	- new Set(iterable) – creates the set, optionally from an array of values (any iterable will do);
	- set.add(value) – adds a value, returns the set itself;
	- set.delete(value) – removes the value, returns true if value existed at the moment of the call, otherwise false;
	- set.has(value) – returns true if the value exists in the set, otherwise false;
	- set.clear() – removes everything from the set;
	- set.size – is the elements count;
	- Set can be looped with the for...of loop;
	- set.keys() – returns an iterable object for values,
	- set.values() – same as set.keys, for compatibility with Map,
	- set.entries() – returns an iterable object for entries [value, value], exists for compatibility with Map
DO IT, JUST DO IT:



Important shit!

Set up node.js:
- Visual Studio (Editor de código);
- Node.js (Serve para que qualquer coisa que cries que precise de um servidor e isto faz esse trabalho);
- npm -g install http-server;

Spotify extension for Visual Studio Code:
https://marketplace.visualstudio.com/items?itemName=shyykoserhiy.vscode-spotify

Arrays porperties:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

Books to read about hacking:
Metasploit - https://drive.google.com/file/d/0B5kcDDBESO11Z1hhZGtxeVZQX1k/view
Kali Linux - https://kali.training/downloads/Kali-Linux-Revealed-1st-edition.pdf

Websites about hacking:
http://overthewire.org/
https://picoctf.com/
https://www.hackthebox.eu/

Hacker Glossary:
- Black Hat - It is an hacker that violates computer security for maliciousness or for his own personal gain;
- White Hat - It is an ethical hacker, someone that ensures the security of an organization's information systems;
- Gray Hat - It is an hacker that will break the lae in the pursuit of a hack, but does not do so maliciously or for personal gain;
- Exploit - It is a piece of software that takes advantage of a bug or vulnerability to cause unintended or unanticipated behaviour to occur on computer software, hardware or something electronic;
- FireWall - A system using hardware, software, or both to prevent unauthorized access to a system or machne;
- Vulnerability - A weak spot hackers can exploit to gain access to a machine;
