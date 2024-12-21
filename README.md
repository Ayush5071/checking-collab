# Custom Cursor Project

This project demonstrates how to create a custom cursor using JavaScript, where the cursor's position is manually set to follow the mouse movement. It uses basic HTML and JavaScript for dynamic interaction.  

## Features

- **Custom Cursor:**  
  The default browser cursor is replaced with a custom element that follows the mouse's movement.
  
- **Interactive Mouse Movement:**  
  The custom cursor smoothly follows the mouse using JavaScript and updates in real-time based on mouse events.

## Technologies Used

- **HTML** for structure.
- **CSS** for styling the cursor.
- **JavaScript** for adding interactivity and moving the cursor according to the mouse's position.

## Code Overview

### **JavaScript Functionality:**

1. **Selecting Elements:**  
   The script first selects the `main` container and the `.cursor` element.

   ```javascript
   var main = document.querySelector("#main");
   var crsr = document.querySelector(".cursor");
