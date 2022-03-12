### Lists

- <li> Stands for list item and will most likely be in every list that you make

- <ol> Creates an ordered list

- <ul> is a tag that creates an unordered list (cool thing is, you can put multiple inside of each other)

- <dl> Creates a definition list. Definition list most usually consists of terminoligy and descriptors following them. More often then not these lists will have the next few tags

- <dt> will contain a term being defined

- <dd> will be paired with a <dt> most likely and will contain the definition of the term listed

### CSS

- p{
  height: 75%
  width:75%
  }
- this will set the text to only take up 75% of the width and height within the element (content can be too big for the given area)

- Scroll 
- Lets say you had to much text in a given area 

// EX:
// (<html> - <p class="two">)
// CSS (p.two{
  overflow: scroll
}) (Example taken from John Ducketts HTML & CSS Page 306 in Chapter 13)

- great solution if there is too much given text to display as it will give a scroll wheel to accesss the rest of the text.

- Border, Margin, and Padding help create spaces between bodies of text to help them look better visually 

- Border width can be edited in size, color, and style I.E.: dashed, double, solid, etc...

- Padding creates space between the content inside of an element and the border of said element

- Text-align will align the text to the given value like left right and center

### IF/ELSE Statements & Loops

- If a condition is met it will continue 
- Else it will go with another conditional if it is not met

- String: Text
- Number: Number
- Boolean: true or false statements
- Null: Empty or nonexistent value
- Undefined: The variable has been created and declared but does not yet have an assigned value

- Falsy: Are values treated as if they are false, can be treated as the number 0
- Truthy: Are values that treated as true, can be treated as the number 1

- For Loop: runs a specific line of code for a specific amount of times
- While loop: runs loop indefinitly until certian criteria is met
- Do while loop: similar to while but will always run statements inside of curly brackets
- Break: Causes the termination of the loop and tell the interpreter to go the next statement or line of code
- Continue: tells the interpreter to stop the current interation, and then update and check the ocndition again.
- Comparison operators: used to compare two operators