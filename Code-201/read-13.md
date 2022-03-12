# The past, present & future of local storage for web applications (By: Mark Pilgrim)

-Local storage historically has almost always had an edge compared to web applications, albeit cookies for website was created in the early days of web applications,
but they do most commonly have three major problems, being:
1. Cookies are inclued with every HTTP request, slowing down the web application in the process by needlessly transmitting data back and forth constantly
2. As well as constantly sending data that is uncrypted over the internet.
3. Cookies also have a limited amount of stored data at around four KB of data - which is not much on its own but is still enough to slow you down

## Brief history of local storage hacks before HTML 5
- Microsoft created something called DHTML Behaviors to combat other web exploring applications, one of the behaviors was called userData
> User data allows pages to store up to 64 kb of data rather than the 4 that a cookie provides.

- In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.
Gears provides an API to an embedded SQL database based on SQLite. After gaining permission from the user once,
Gears can store unlimited amounts of data per domain in SQL database tables.
 
- After going over many problems and trying to find a solution for them, a pattern emerges.
That pattern being that they are all either specific to a browser or are reliant on a third party plugin.
 
- What is HTML 5 storage?
> HTML 5 storage is a way for web pages to store key/value paris locally within the client web browser similar to cookies.
> This data is never transmitted to a remote web server.
 
- HTML 5 storage is usually data formatted into a string, if it is not a string there may need to be functions used to access it such as parseInt() or parseFloat()
 
## Tracking changes to storage area
To keep track of changes you can trap a storage event whenever something is actually changed.
The storage event is stored globally and can be called anywhere

