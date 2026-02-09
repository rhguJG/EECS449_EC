# EECS449_EC

## Name and UMID
Ruohan Gu, 12324272

## Feature I add
I added **theme switching** to the todo app.  
The user can change the UI theme between:

- Light  
- Dark  
- Umich
- Pink 

Each theme has different background, text color, and styles for inputs, buttons, and category badges.

## How to install and run

1. Make sure you have **Jac** installed (following the course setup).  
2. Download the whole folder *my-todo* and put them in VSCode.
3. Get an API from Gemini, and run
   jac start main.jac

## How the feature works
I made the changes in *main.jac* first. In the client app, I store the current theme in a state variable theme. The outer <div> uses theme to choose a CSS class, and in the header, I added a <select> that lets the user change the theme through light mode to pink mode.

Then I changed the *styles.css*. I define different styles and colors for each theme. These classes control the colors of the background, text, inputs, buttons, and the **.category** badge, so switching the theme changes the whole look of the app.
