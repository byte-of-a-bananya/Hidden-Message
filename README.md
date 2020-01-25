/* The villains of the 90s action thriller Con Air cleverly 
 * planned their escape by communicating through hidden messages 
 * disguised in a plain letter.  Only with the cover image could the 
 * invisible message be revealed. Their plan was fool proof until 
 * Agent Larkin discovered a photo of the Last Supper with holes 
 * mysteriously cut into it.  When he placed it on top of the letter 
 * the secret rendezvous location was revealed.

You will be given a paragraph of text.  Somewhere inside the text 
is an invisible message.  Your task is to expose the message from 
this inconspicuous text by laying a cover message on top revealing 
the correct letters.


 

The first line of the file input.txt will contain a positive 
integer T denoting the number of test cases that follow.  Each 
test case will have the following input:

 

- The first line of each test case will be a positive integer M denoting 
how many lines of text the message contains.
- The next M lines will contain the seemingly normal message.
- The next line will contain the start coordinate for the cover message 
in row,column format.Since the villains were aspiring computer programmers, 
they cleverly chose to make the first character in the normal message row 0, 
column 0.
- The next line will be a positive integer N denoting how many lines of text 
the cover message contains
- The next N lines will be the cover message. The cover message may not be 
the same size as the original message but will fit inside it.  A capital 
letter O indicates a hole in the cover message where the invisible message 
can peek through.  A – (dash) is not a hole and does not reveal any piece 
of the invisible message.
 

Example Input:

 

1

9

We hold these truths to be self-evident, that all men are created equal,

that they are endowed by their Creator with certain unalienable Rights,

that among these are Life, Liberty and the pursuit of Happiness. That to

secure these rights, Governments are instituted among Men, deriving their

just powers from the consent of the governed, --That whenever any Form of

Government becomes destructive of these ends, it is the Right of the

People to alter or to abolish it, and to institute new Government, laying

its foundation on such principles and organizing its powers in such form,

as to them shall seem most likely to affect their Safety and Happiness.

2,5

7

-O------O-----O-------------------------

--O----O--------------------O------O----

------O---O-----------------------------

----------------------O--------------O--

------------------------------O-----O---

-----------------------------------O----

-------O---------------------O----------

 

Example Output:

meet at midnight

*/
