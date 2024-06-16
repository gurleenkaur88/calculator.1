# Calculator App


Experience effortless calculations with the  Calculator app. This app combines a stylish design featuring a dark gradient background and the clean Poppins font with intuitive functionality. The interactive JavaScript code ensures smooth operation, allowing you to perform arithmetic calculations, clear all inputs, delete the last entry, and append digits or operators with ease. Ideal for anyone looking for a visually appealing and highly functional calculator.
1. *Font Awesome*: The app's clean and contemporary look is enhanced by the use of the Poppins font, made available through Google Fonts. This contribution from the open-source community has greatly improved the visual appeal of the app.

2. *Mozilla Developer Network (MDN)*: The comprehensive documentation and tutorials provided by MDN Web Docs were crucial in building and refining the HTML, CSS, and JavaScript components of this calculator.

3. *Stack Overflow*: The developer community on Stack Overflow provided solutions to coding challenges and helped optimize the app's functionality.

4. *W3Schools*: The tutorials and examples on W3Schools served as a helpful reference throughout the development process.

5. *JavaScript Libraries and Frameworks*: Various open-source JavaScript libraries and tools facilitated the implementation of interactive features, ensuring a smooth and responsive user experience.

6. *Inspiration from UI/UX Designers*: The sleek and modern design of the calculator was inspired by the work of talented UI/UX designers whose projects serve as a benchmark for creating intuitive and visually appealing interfaces.
## API Reference

### HTML Structure

#### <html lang="en">
- The root element of the HTML document, with the language set to English.

#### <head>
- Contains metadata and links to external resources.

  - <meta charset="UTF-8" />: Specifies the character encoding.
  - <meta http-equiv="X-UA-Compatible" content="IE=edge" />: Ensures compatibility with Internet Explorer.
  - <meta name="viewport" content="width=device-width, initial-scale=1.0" />: Sets the viewport to scale properly on different devices.
  - <link rel="stylesheet" href="style.css" />: Links to the external CSS stylesheet.
  - <title>Calculator</title>: Sets the title of the document.

#### <body>
- Contains the main content of the HTML document.

  - <div class="container">: A wrapper for the calculator.

    - <div class="calculator">: The main calculator element.
      
      - <input type="text" id="inputBox" placeholder="0" />: Input field for displaying the calculation result or current input.

      - <div>: Contains rows of buttons.

        - <button class="button operator">AC</button>: Clear all input.
        - <button class="button operator">DEL</button>: Delete the last character.
        - <button class="button operator">%</button>: Percentage operator.
        - <button class="button operator">/</button>: Division operator.
        - <button class="button">7</button>: Number button.
        - <button class="button">8</button>: Number button.
        - <button class="button">9</button>: Number button.
        - <button class="button operator">*</button>: Multiplication operator.
        - <button class="button">4</button>: Number button.
        - <button class="button">5</button>: Number button.
        - <button class="button">6</button>: Number button.
        - <button class="button operator">-</button>: Subtraction operator.
        - <button class="button">1</button>: Number button.
        - <button class="button">2</button>: Number button.
        - <button class="button">3</button>: Number button.
        - <button class="button operator">+</button>: Addition operator.
        - <button class="button">00</button>: Number button.
        - <button class="button">0</button>: Number button.
        - <button class="button">.</button>: Decimal point.
        - <button class="button equalBtn">=</button>: Equals button.

  - <script src="script.js"></script>: Links to the external JavaScript file.

### CSS Styling

#### General

- @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');: Imports the Poppins font.

- * { ... }: Applies general styling to all elements.

- body { ... }: Styles the body element with full viewport height, centered content, and a gradient background.

#### Calculator Container

- .calculator { ... }: Styles the calculator element with border, padding, rounded corners, transparent background, and box shadow.

#### Input Field

- input { ... }: Styles the input field with width, padding, margin, transparent background, box shadow, font size, text alignment, cursor, and text color.

- input::placeholder { ... }: Styles the placeholder text in the input field.

#### Buttons

- button { ... }: Styles the buttons with border, size, margin, rounded corners, transparent background, text color, font size, box shadow, and cursor.

- .equalBtn { ... }: Styles the equals button with a distinct background color.

- .operator { ... }: Styles the operator buttons with a distinct text color.

## Badges

[Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=google-fonts&logoColor=white)**  
   Shows the integration of Google Fonts for typography.

[Responsive Design](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)**  
   Demonstrates the app's responsiveness across various devices.

[Cross-Browser Compatibility](https://img.shields.io/badge/Cross--Browser-Compatibility-orange?style=for-the-badge)**  
   Ensures compatibility with multiple web browsers.

[Clean Code](https://img.shields.io/badge/Clean-Code-blue?style=for-the-badge)**  
   Reflects the emphasis on clean, readable, and maintainable code.

[Open Source](https://img.shields.io/badge/Open%20Source-333333?style=for-the-badge&logo=github&logoColor=white)**  
   Indicates that the project is open source and encourages collaboration.

[W3C Validated](https://img.shields.io/badge/W3C-Validated-brightgreen?style=for-the-badge)**  
   Signifies that the HTML and CSS adhere to W3C standards.

[Poppins Font](https://img.shields.io/badge/Poppins-Font-blue?style=for-the-badge)**  
    Highlights the use of the Poppins font for a clean, modern look.
1. *Background Linear Gradient:*
   - #0a0a0a (Very dark gray)
   - #3a4452 (Dark slate gray)

2. *Border:*
   - #717377 (Gray)

3. *Box Shadow:*
   - rgba(113, 115, 119, 0.5) (Semi-transparent gray with 50% opacity)
   - rgba(84, 84, 84, 0.1) (Very light gray with 10% opacity)
   - rgba(255, 255, 255, 0.1) (Very light white with 10% opacity)

4. *Text Color:*
   - #ffffff (White)
   - #6dee0a (Bright green for operator buttons)
   - #fb7c14 (Bright orange for the equal button)


https://github.com/gurleenkaur88/calculator.1.git

