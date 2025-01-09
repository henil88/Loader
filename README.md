# Pan Loader

A fun and creative pan-shaped loader animation built with HTML and CSS. This project uses CSS animations to simulate the appearance of a rotating pan and a dynamic shadow, making it visually engaging.

## Features

- **CSS Animations**: Smooth animations for the loader, shadow, and pan movement.
- **Responsive Design**: The loader is centered and adapts well to various screen sizes.
- **Customizable**: Easily modify colors, sizes, or animation durations to fit your needs.

## Technologies Used

- **HTML5**: For the structure of the loader.
- **CSS3**: For styling and animations.

## Structure

### HTML
The structure includes:
- A `div` with the class `pan-container` containing:
  - The `pan` element representing the main pan.
  - A `loader` element inside the pan to simulate a rotating food item.
  - A `pan-in` element representing the pan's handle.
  - A `hendal` element for an additional design element.
  - A `shadow` element for the shadow animation.

### CSS
The styles define:
- **Base Styles**: Reset margins, paddings, and box-sizing for consistency.
- **Pan and Loader Styles**: Define the dimensions, colors, and shapes of the pan and its components.
- **Animations**:
  - `loader`: Simulates the rotating loader inside the pan.
  - `shadow`: Creates a shadow animation that grows and shrinks.
  - `pan`: Adds a gentle tilting motion to the pan.

## Key CSS Animations

1. **`@keyframes loader`**:
   - Controls the size and rotation of the loader.
   - Simulates the appearance of food being tossed in the pan.

2. **`@keyframes shadow`**:
   - Changes the width and position of the shadow for a dynamic effect.

3. **`@keyframes pan`**:
   - Adds a tilting motion to the pan, making it look like it's being shaken.

## How to Use

1. Clone or download the repository:
   ```bash
   git clone https://github.com/henil88/Loader.git
2. Open the `index.html` file in your browser to view the loader.

3. Customize the `styles.css` file to modify the animation or design as needed.

## Customization

You can customize various aspects of the loader by modifying the CSS:
- **Pan Size**: Adjust the `width` and `height` of the `.pan` class.
- **Animation Speed**: Change the `animation-duration` for `loader`, `pan`, and `shadow`.
- **Colors**: Update the `background-color` and `border` properties for the loader, pan, and shadow.
