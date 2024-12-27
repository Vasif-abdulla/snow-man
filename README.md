# README: Christmas Tree and Snowman HTML/CSS Project

## Overview

This project creates a festive web page featuring a **Christmas Tree** and a **Snowman** using HTML and CSS. It showcases the use of CSS styles for creative graphical elements and is perfect for learning how to combine shapes, gradients, and animations for a fun holiday theme.

---

## Files

### 1. `index.html`
This file contains the HTML structure of the web page. The key components include:
- **Christmas Tree**: Made up of three triangular sections, a rectangular trunk, and glowing ornaments.
- **Snowman**: Created using CSS gradients and radial/linear gradient layers for realistic effects.

### 2. `style.css`
This file contains the styling and layout for the elements in `index.html`. It is responsible for:
- The background design.
- Styling for the Christmas Tree and its ornaments.
- Detailed layer styling for the Snowman.

---

## Key Features

### Christmas Tree
- Constructed using CSS triangles (`border-style: solid`).
- Three layers of green triangles with shadows to create a 3D effect.
- A trunk at the bottom styled as a rectangle.
- Five ornaments styled as glowing spheres with CSS `box-shadow` for festive lighting.

### Snowman
- Made with **radial gradients** for a smooth circular appearance.
- Details like eyes, buttons, and a carrot nose are implemented using additional radial and linear gradients.
- Layers of gradients simulate depth and realism.

---

## Code Explanation

### HTML
The HTML structure organizes the tree and snowman elements into separate containers:
- `<div class="christmas-tree">` for the tree and its ornaments.
- `<div id="snowman">` for the snowman, which relies entirely on CSS for its design.

### CSS
#### Christmas Tree
- **Triangles**: Achieved using `border-style: solid` and adjusting `border-width` to form a triangle shape.
- **Ornaments**: Styled with `border-radius: 50%` for circular shapes and glowing effects using `box-shadow`.

#### Snowman
- **Body**: Created using multiple radial gradients stacked on each other.
- **Features**: Eyes, buttons, and a nose are additional gradients positioned with `background-position`.
- **Hat and Scarf**: Linear gradients and precise positioning simulate these accessories.

---

## How to Use

1. Clone or download this repository to your local machine.
2. Open `index.html` in any modern web browser.
3. The page will display the Christmas Tree and Snowman.

---

## Customization

### Christmas Tree
- Change the `border-color` property of `.triangle1`, `.triangle2`, `.triangle3` for different tree colors.
- Modify the `background` and `box-shadow` values of `.ornament` classes for custom ornament colors and lighting effects.

### Snowman
- Adjust `background-size`, `background-position`, and `background-image` layers in the `#snowman` CSS to alter the snowman’s appearance.
- Modify the scarf, buttons, or hat color by editing the gradient colors.

---

## Compatibility
- Tested on all modern web browsers including Chrome, Firefox, and Edge.
- Requires support for CSS gradients and modern CSS properties.

---

## Acknowledgments
This project is an exercise in creative web design using only HTML and CSS. It’s ideal for those interested in learning how to use CSS for graphical elements and festive projects.

Happy Holidays! 🎄☃️
