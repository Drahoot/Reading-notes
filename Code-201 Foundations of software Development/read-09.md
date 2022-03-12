## Forms (Jon Duckett Pg. p.144-175, pg.330-357)
- Allow users to search and perform other functions online
> typically seen when registering as a member, shopping, or when signing up for a mailing list online

## Form controls

### Text additions
- Text input
> used for a single line of text like email addresses and names

- Password input
> Like a single line text box but it masks the characters that are entered

- Text area
> Creates a larger space for text to be input, typically used for comment sections and messages

### Choices
- Radio Buttons
> Creats a list of bullets that can be selected from a small plethera of options

- Checkboxes
> similar to a radio button but can have multiple selections

- Drop-down box
> Creates a list of options

## From Structure
- From controls live inside of a form element and should always carry the action attribute and will usually have a method and id attribute as well

- every form element requires an action attribute. Its value is the url for the page on the server that will recieve that information in the form when it is submitted

### Methods
- Forms can be sent using a get and post method

- Get
> with the get method, the values from the form are added to the end of the URL specified in the action attribute. 
- The get method is ideal for
> - short forms
> - when you are just retrieving data from a web server

- Post
> with the post method the values are sent in the HTTP headers. A post method can be used for
> allowing users to upload a file
> if a form is very long
> contains sensative data
> adds infor to or deletes info from a database

- Input
> The input element is used to create several different from controls. The value of the type attribute determines what kind of input they will be creating

- type="password"
> this will create a text box that acts like a single line input except the characters are blocked out

- Fieldset
> you can group related form controls together inside the fieldset element 

- List-style-type
> the list style type property allows you to control the shape or style of a bullet point

# JS & JQUERY (Jon Duckett  pp.243-292)

## Event Types
### UI EVENTS - Occur when a user interacts with the browsers user interface rather than the web page

- Keyboard events
> Occur when a user interacts with the keyboard 

- Mouse events
> occur when a user interacts with a mouse or selecting device

- Focus events
> Occurs when an element gains or loses focus

- From events
> occur when a user interacts with a form element

- Mutation events
> Occur when the DOM structure has been changed by a script 

