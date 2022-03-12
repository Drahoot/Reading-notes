# HTML & CSS (Jon Duckett Ch. 15 pg, 360-400)

### Positions
- static
> All this does render the element normally 

- Relative
> Moves an element in relation to where it would have been in normal flow
> You can indicate that an element should be relatively positioned using the position property with a value of relative
> Then use the offset properties to indicate how far to move the element from where it owuld have been in normal flow

- Absolute
> When given a value of absolute the box is taken out of normal flow and no longer affects the postion of other elements on the page
> The box offset properties specify where the element should appear in relation to its containing element

- Fixed
> This is a type of absolute positioning that requires the position property to have a value of fixed
> This will postion the elements in relation to the browser window

### Floating elements
The float property allows you to take an element in normal flow and place it as far to the side of the containing element as possbile

- Clear
This property allows you to say that no element should touch the left or right hand sides of a box, it can take the following values
1. left
2. right
3. both
4. none

