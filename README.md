# bparticles.js

A lightweight JavaScript library for creating dynamic particle effects on web pages.

## Features

- **Customizable**: Easily configure particle size, movement, and appearance to suit your project's needs.
- **Dynamic**: Bring your web interfaces to life with captivating particle animations.
- **Simple Integration**: Quick and easy setup allows for seamless integration into any web project.
- **Responsive**: Automatically adjusts to different screen sizes for a consistent user experience.

## Installation

To use the bparticles.js in your project, simply include the `bparticles.js` file in your HTML:

```html
<script src="bparticles.js"></script>
```

## Usage

```javascript
// Initialize the Particles Library
const particles = new Particles(element, config);
```

Replace `element` with the HTML element where you want to display the particles, and `config` with an optional configuration object.

## Configuration Options

The `config` object can include the following options:

- `amount`: Number of particles to generate.
- `size`: Array defining the range of particle sizes.
- `duration`: Duration of particle animations.
- `timeFunction`: Transition timing function.
- `mode`: Movement mode ('random' or 'range').
- `floatX`: Horizontal floating range.
- `floatY`: Vertical floating range.
- `autoAmount`: Automatically calculate particle amount based on screen size.
- `disappear`: Enable random particle disappearance.

## Examples

```javascript
// Example configuration
const config = {
  amount: 100,
  size: [5, 10],
  duration: 1000,
  timeFunction: 'ease-out',
  mode: 'random',
  floatX: 50,
  floatY: 50,
  autoAmount: true,
  disappear: true
};

// Initialize Particles Library with configuration
const particles = new Particles(document.getElementById('particle-container'), config);
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
