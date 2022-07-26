### What Went Wrong? Troubleshooting JavaScript.

1. Name some key differences between a Syntax Error and a Logic Error.

- Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!

- Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
- Eslint, prettier, and just going through my code when i open the console to see if my code runs correctly or if it doesnt. After checking the console and it doesnt fire up correctly. I will look at where the error is located in the console. It also shows in vscode the red showing me where my logic or syntax errors lie.

3. How will this topic continue to influence your long term goals?
- Checking my code over and over seems to be a good practice. once i write a function i need to make sure the function runs correctly. I should write functions with replit to see if there are any logic errors before I go ahead and create them in my vscode/text editor. 

### The JavaScript Debugger.

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

- The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

- I would describe it as a pause before the break. JavaScript debugger shows you up until when the code breaks. So you can see when and where you need to fix. 

2. Define what a breakpoint is.
-places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.
  - Example:
  - listItems.push(inputNewItem.value);

➤ Web Developer ➤ Debugger or press Ctrl + Shift + S to open the JavaScript Debugger. If the tools are already displayed, click on the Debugger tab.

Chrome: Open the Developer tools and then select the Sources tab. (Opera works the same way.)

Edge and Internet Explorer 11: Press F12 and then, Ctrl + 3, or if the tools are already displayed, click on the Debugger tab.

Safari: Open the Developer Tools and then select the Debugger tab.

3. What is the call stack?
-shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint.