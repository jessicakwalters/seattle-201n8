# Assignment Overview: Lab for Class 8 - Pat's Salmon Cookies

Today you will be adding a form to your existing cookie stand project so that you can add new locations to the table by simply inputting their information with the form.

**Today's work is done in pairs. These pairs will be announced on slack prior to lab start.**

Today's working branch will be `class-8-forms`.

## Instructions

Here's some of the steps you'll need to take, but not necessarily in this order:

- Add the necessary HTML to create the input form.
- Don't forget \<fieldset>!
- Use the constructor function as your guide to determine what input fields your form needs (hint: also consider what is passed in when creating instances!)
- Your JS will need an event listener and and event handler, and also a variable to facilitate DOM access to the form.
- As we saw in class, the event handler should use the take the data from the input field, pass it into the constructor function, and create a new instance of a cookie stand that then appends to the table.
- Are you going to do any error correction on input? You probably should. Look at what kind of input validation is built in to HTML5.
- Build incrementally. Test frequently.
- Be attentive to overall code structure.
- This is a good point to refactor your code into smaller functions/methods if you have some huge functions going on. Remember that each function should do one thing, and then you can compose more complex behavior out of functions.
- Anywhere you have repeated chunks of code, maybe you can start to apply some DRY principles. Generally, once some chunk of code is appearing for a 3rd time or so, that's when you want to consider refactoring.
- When making code more DRY, look for repeated behaviors that act on different pieces of data. Put the behavior into a function that is declared with parameters to receive the unique data, and then replace the repeated code with the function called with the unique data in arguments.

## Submitting Your Assignment

1. When your work is complete and ready for submission, **open and merge a Pull Request** from `class-8-forms` to `master` ***ON YOUR FORK***.
2. **Open a pull request** from the `master` branch in your repository (*driver*) to the `master` branch in your partner's (*navigator*) repository.
3. Submit the link to the above Pull Request [step 2 here, NOT step 1] to Canvas
4. Add a comment to this Canvas submission with answers to the following questions.
  - How did this go, overall?
  - What observations or questions do you have about what you've learned so far?
