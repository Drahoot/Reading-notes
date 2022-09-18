# Encryption, Decryption, and Cracking
- Encrypting a message will convert a string of letters to look like a random jumble of characters
but in reality it is the same sentence that will translate when used with the correct cypher
- IE
  - SECRET MEETING AT THE PALACE
  - YKIXKZ SKKZOTM GZ ZNK VGRGIK
- Decrypting a message is taking that random jumble of characters and converting it into the correct sentence
- IE
  - YKIXKZ SKKZOTM GZ ZNK VGRGIK
  - SECRET MEETING AT THE PALACE
- When it comes to cracking an encryption there are three techniques you can do
1. Frequency analysis
   - With Frequency analysis the first and main step is to figure out the most common character in an encryption
, for instance, a good character to try that is common place in english would be the letter E.
2. Known plaintext
   - A way to use Known plaintext is to already know a part of the plaintext, for example in WW2 german messages that were encrypted
always started with the weather forcast, this made code breakers be able to solve the cipher easier 
3. Brute force
   - With brute force its a matter when the correct cypher is being used, to decrypt you must go through every possible code shift there is

# Ceaser Cypher
- The Ceaser Cypher is one of the simplest and most commonly known cyphers out there. 
It is a type of substitution cypher, which means that the plaintext in shifted x amount of numbers in the alphabet
- The ceaser cypher can be represented using modular arithmetic by transforming letters in numbers
  - IE
  - A → 0, B → 1, ..., Z → 25
  - Encryption method: E n(x)=(x+n)\mod {26}.
  - decryption: D n(x)=(x-n) mod  26 .
