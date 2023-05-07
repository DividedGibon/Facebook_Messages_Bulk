# Facebook Messages Bulk Changes

This repository contains code to bulk edit Facebook Messenger chats/messages by archiving, unarchiving, or deleting them. Unfortunately, Facebook does not provide a built-in function for bulk editing of chats, hence this code works at the browser level to manipulate the browser console.

## Usage

1. **Open [Facebook Messenger](https://www.facebook.com/messages/) in a desktop web browser with developer options enabled**. Google Chrome is recommended (tested as of May '23).
2. **Navigate to the chat folder you want to bulk edit** (main chats, marketplace, or already archived chats).
3. **Open the Chrome "three dots menu" located at the top-right next to your profile picture** and click "More Tools" -> "Developer Tools". Alternatively, use the keyboard shortcut "CTRL+SHIFT+I". This will open the developer web tools, which should split the web interface window and open on the right-hand of the screen (or in a separate window).
4. **In the developer interface, click on "Console" at the top (next to "Elements")**.
5. **Choose one of the following code files: `Archive.js`, `Unarchive.js`, or `Delete.js`**.
6. **Paste the contents of the chosen file into the console and hit Enter**.
7. **You'll get a browser-level prompt to confirm you want the code to run**. Finally, leave it to do its thing. If you have hundreds of chats, it may take some time to complete.

## Notes

- This code has only been tested in Google Chrome but may work in other browsers.
- This code is efficient, but if you have hundreds of chats, you may need to take a break and leave the browser open to finish the task.
- Facebook Messenger's web build may change at any time, which may cause this code to stop working.
