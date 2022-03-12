# day-4-notes

you can start a function whenever you want instead of first loading in the page
MVP: Minimum Vile Product
JS has built in functions, like prompt and alert
programming: a step by step process to solve a problem
Funtion: Input output scenario
debugging is usaully harder to figure out rather than making the function

User input function example
new js file
// step 1. Gather our ingredients -> Bread, Meat, Cheese, Mayo, Grey Poupon, Lettuce
// Step 2. put it together
// Step 3. Return your result
// Step 4. Refactor

// DECLARE function
// STYLE GUIDE
//Arguments = Function input
take everything under the function over it to create an argument

// pass data into your functions
function makeASandwhich (arguments) {                       (bread. meat. cheese) use these as arguments
let bread = 'Sourdough';            = prompt('What kind of bread would you like?')
let meat = 'ham';
let cheese = 'swiss';
let condiments = 'Mayo & Grey Poupon';
let veg - 'lettuce';



console.log('HERE I AM')
return 'Here is your sandwhich on' + bread + 'containing ' + meat + ',' + cheese + ',' + condiments + ', and ' + veg
}

//let makeMeASandwhich = function (){}
//either one of those two will work

//call/Invoke the function
makeASandwhich ('Sourdogh','ham','swiss','bbq','lettuce');

if you wanna run your code, highlite it first, F1, Run code
you can run the same function multiple times at once

if you dont have a defined input it will make the best descisiion with what you give it.

function makeASandwhich (bread, meat, cheese, condiments, veg) {
//all your code/logic lives here
if (bread && meat && cheese && condiments && veg) {
}

NEW EX:
function promptUserForTime () {
// have a descriptive naming function
//step 1. prompt user for time

let tod = prompt('What hour is it?')
console.log('tod', tod)

// step 2. decide what response to return to the user

let response = 'welcome';

//step 3. create logic that changes response
// Step 4. Check user input for valid input
//// if not valid, call PromptUserForTime() again.

if (tod > 18){
response = 'Good evening!';
} 

else if (tod > 12) {
response = 'Good afternoon';
} 

else if (tod >= 0) {
response = 'Good morning';
} 

return alert(response)
console.log('tod', tod);
}

//console log logs stuff in the console believe it or not
// Function CALL a.k.a Function Invocation
promptUserForTime();

The control flow is the order in which the computer executes statements in a script.
code will always run top to bottom in which it is written
thats called control flow
functions make it easier to reuse code at different points whilst making cleaner
Functions can be used the same way as you use variables
there are tons of assignment operators such as = += -= 
 A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values

