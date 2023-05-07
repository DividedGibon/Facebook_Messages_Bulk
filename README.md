# Facebook Messages Bulk Changes

Unfortunately, a function is not included in Facebook to allow chats/messages in the Messenger environment to be bulk edited – I.e. Archived, Deleted or unarchived.
There also exists some code here from Tedmiston’s, which was design to archive chats.  I’ve improved this code, then noticed others requesting code which could not just archive, but also unarchive and delete in bulk.

This repo contains code which will allow either of the three functions to be run in bulk. 

Some notes: 
1.	You need to do this via a desktop web browser which has a developer options.  I recommend Google Chrome (only due to me testing it here).
2.	The code is efficient, but if you have hundreds of chat you may need to leave the browser (take a break, put your feet up and have a coffee). 
3.	I’ve tested this as of May ’23 – I cannot guarantee that a change in Facebooks Messenger web build won’t mean this code stops working.

Please ensure you understand the following: 
•	This code works at the browser level as Facebook offers no easy way to alter/edit chats in bulk. 
•	This code is manipulating the browser console.
•	Code has only been tested in Google Chrome but may work in others. I just don’t have time to test them all. 

Quick Start
Step 1: Load Facebook messenger in a new tab (or new window).
Step 2: Navigate to the chat folder you want to bulk edit.  I.e., the main chats, marketplace or already archived chats.
Step 3: (note this step applies to Chrome only – other browsers may vary).
•	Open the “three dots menu” of Chrome, located in the top-right next to your profile picture. 
•	Click “More Tools”
•	Click “Developer Tools”
Alternatively use the keyboard shortcut “CTRL+SHIFT+I”
*Note: This will open the developer web tools – it should split the web interface window and open on the right-hand of the screen (or in a separate window). 
Step 4: In the developer interface click on “Console” at the top (next to “Elements”).
Next, we can use the one of the following code files: 
`Archive.js`
`Unarchive.js`
`Delete.js`

Step 5: Paste the contents of the file into the console and hit Enter.
Step 6: You’ll then get a browser level prompt confirm you want the code to run. 
Finally, leave it to do its thing, you’ll need to leave the browser open – have a coffee.
