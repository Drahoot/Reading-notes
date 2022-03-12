## Objects

- Property
> a variable that is part of an described object

- Method
> a function that is part of an object

- Key
> a descriptive name of an value

## Node

- DOM Tree 
> stands for Document Object Model, that treats an HTML webpage as a structured tree framework typically ending with nodes

- DOM Node
> the starting point for for all visits to the DOM tree

- Attribute Nodes
> additional information that details more information for other tags

- Text node
> cannot have a child node but rather is the text element itself

## Element accesment (Pg. 188 Js & JsQuery J. Duckett)

- getElementById()
> Uses value  of an elements id attribute

- Query selector
> Uses a CSS selector, and returns the first matching element

- getElementByClassName()
> Selects every element that have a specific value for said class attribute

- getElementsByTagName()
> Selects all elements that have a specified tag name

- querySelectorAll()
> Uses a CSS selector to select all matching elements

- parentNode
> selects the parent of the current element node (will return one element)

- previousSibling/nextSibling(can be used in css)
> selects the previous or next sibling in the DOM Tree

- firstChild / lastChild(can be used in css)
> select the first or last child of the current element

### THE TERMS ELEMENTS AND ELEMENT NODE ARE USED INTERCHANGEABLY

Several methods let you create new nodes, add nodes to a tree, and remove nodes from a tree EX:
- createElement()
- createTextNode()
- appendChild() / removeChild()
methods that return more than a singular node always return a nodelist, a collection of node elements.

- Nodelist
> a collection of nodes, each time a nodelist is called it gives each node an index number similar to an array


