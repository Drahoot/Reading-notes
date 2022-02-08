// Assignment operator
let x = 7
let y = 5
// Addition assignment
x += y;
x = x + y;
// Increment operator     will be used in demo today
x++; add another value of 1 or x

// Logical operatir &&
let expr1 = 5 > 1;
let expr2 = 4 > 1;
if (expr1 && expr2) {
console.log('true')
} else {
console.log('false')
}
Will show as true, they are true


// typeof operator
let string = 'hello'
let fakestring = 7;
//console.log(typeof string);
if(typeof string == 'number'){
console.log('true');
}
Will show as true
change to fakestring in the if and it will show false



A loop is doing x y number of times
define x and y
let x = 8;
let y = 0;
// LOOP I want to loop and increase y by 1 UNTIL y = x
// WHILE LOOP

practical EX
// while the expression is TRUE, LOOP and run code in {}
// WHEN EXPRESSION is FALSE, you're done with loop
while(y < x){
console.log('what is y:', y)
y++:
}
// Once while loop is flase, continue down here
console.log('I AM OUT OF THE LOOP')

// FOR LOOP
put in i, i stands for index
// FOR Loop - WE set the iteration count
for(let i =0; i < 10; i++){
console.log('I', i); //loop body//
// i++ is the updater in a FOR LOOP
}
//DONE with loop, continue on
console.log('PAST THE FOR LOOP')


//Better example that i can implement in website
this will be working with a function
// create a user prompt that asks "how mmany pictures of ___ would you like to see?"
// I want to write a function that i can call
zork will be image example
Function zorkImgCountPrompter(whichPrompt){
//step 1
let zorkCount = prompt("whichPrompt")
// I want to add a validation check
if(zorkCount === ''){
let message = 'How many pictures of zork would oyu like to see')
let error = ('Please enter a number between 1 and 3')
zrokImgCountPrompter(message + error);
// user gave no input, prompt again
  }
if (zorkCount == 3){
for (let i=0; i <3; i++){
// add a zork image in 3 times
document.write('<img src="images/zork.jpg">')} 
//use different qoutes when using multiple qoutes inside the same line or ur a \
// EX 1 document.write('<img src=\images/zork.jpg\>')
// EX 2 document.write('<img src="images/zork.jpg">')

  }
}

 An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal, which assigns the value of its right operand to its left operand.
 try to avoid chaining assignments it can result in some pretty funky stuff
 A comparison operator compares its operands and returns a logical value based on whether the comparison is true
 
 while (!isvalid)
 PageANS = prompt('How many Electric Triangles would you rate my page out of 5?')
    VAL = parseInt(PageANS);
    isvalid = !isNaN(VAL) && VAL >= 1 && VAL <= 5;
keeps comparing the given number between the set values it was given


