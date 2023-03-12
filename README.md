# Welcome to the Password generator!
### My goal is to create a wedsite that will generate a random password depending on the criteria that the user selects. My goal was to make it simple and easy to use. 

## User Story
```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security
```
## Acceptance Criteria
```
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```

# My process!
**So Since my goal was to make the process on making a password a bit easier I wanted to add a section that will show when you press the generate password button. But in order for me to do that I need to add a few things to my HTML and CSS files. My first goal was to make sure I made an easy interafce with the HTML File. Here I added a section where you can choose how manny charectures you want in your password and check mark what you want to add to your password.**
![getting started](assets/IMG/HTML%20wtih%20added%20stuff.jpg)

**After adding to the HTML i went ahead and updated the CSS**
![getting started](assets/IMG/CSS%20upadated%20.jpg)

**After adding all that this is what we have**
![getting started](Assets/IMG/Showing%20the%20Extra%20section.jpg)

**Also by adding #promts display to none in CSS we Put in our javascript a section that will allow up to display the section when you hit the button like in the gif below.** 

![Gif](assets/IMG/Showing%20teh%20section.gif)

***added to JS to help pop the prompt up***
![sectionForPromt](assets/IMG/show%20Prompt.jpg)


**Next we started adding the function to our Javascript files**
![JSFunction](Assets/IMG/JS_password%20Function.jpg)
![JSFucntion the PW](assets/IMG/funaction%20for%20the%20password.jpg)

**Then a section that will help with the password lenght, and if nothing is selected we will have it send back the phrase please select an option, on top of that we want a random scramlbe of the password to show up when playing with the settings**

![JSFucntion the PW](assets/IMG/JS_funcation_PW.jpg)

**Then when messing with the settings we want the HTML to display the current password lenght with what corrispondes to would you choose in the settings**

![JSFunction updating](assets/IMG/Event%20listener.jpg)





