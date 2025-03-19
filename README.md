# The Best Question

An interactive, visually pretty web page displaying [The Best Question](https://www.goodreads.com/book/show/59317244-living-fearless).
Created as a farewell gift to honour my boss and his valuable advice.

## Features

- Gentle animated typography with 3D perspective effects
- Interactive ripple animations on click
- Responsive design that works on both desktop and mobile devices
- Device orientation support for mobile tilt effects
- Smooth animations powered by GSAP

## Technologies Used

- HTML5
- CSS3 (with advanced effects)
- JavaScript (ES6+)
- GSAP (GreenSock Animation Platform) for smooth animations
- Canvas API for ripple effects
- Device Orientation API for mobile interactions

## How It Works

### Technical Implementation

1. **Typography Animation**:
   - Each word is individually animated using GSAP
   - Words appear with a blur-to-clear effect in sequence
   - Text includes a subtle chromatic aberration effect

2. **Interactive Ripple Effects**:
   - Canvas-based ripple animations trigger on click
   - Multiple ripples with varying speeds and opacities create depth
   - Words dynamically respond to ripples with distortion effects

3. **3D Perspective**:
   - Mouse movement controls the 3D tilt of the quote
   - Device orientation sensors enable tilt effects on mobile
   - Smooth transitions between states using GSAP's easing functions

## Usage

Simply open `index.html` in any modern web browser. Click anywhere on the screen to create ripple effects and interact with the quote. On mobile devices, tilting your device will create a 3D perspective effect.

## Browser Compatibility

Works best in modern browsers that support:
- ES6+ JavaScript
- Canvas API
- CSS3 3D Transforms
- DeviceOrientation API (for mobile tilt effects)

## License

MIT

Personal project - created as a farewell gift.
