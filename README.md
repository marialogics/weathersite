# Temperature Converter Website

A modern, interactive web application for converting temperatures between different scales: Celsius, Kelvin, Fahrenheit, and Newton.

## 📋 Overview

This project provides a user-friendly interface to convert temperatures from Celsius to multiple temperature scales. The application features real-time conversions and a responsive design that works seamlessly on desktop and mobile devices.

## 🌡️ Features

- **Real-time Temperature Conversion**: Convert Celsius to Kelvin, Fahrenheit, and Newton instantly
- **Interactive Input**: Enter any Celsius value and see conversions update immediately
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, gradient-based interface with smooth animations
- **Console Logging**: Outputs conversion results to browser console for debugging
- **Keyboard Support**: Press Enter to convert without clicking the button

## 📁 Project Structure

```
js projects/
├── index.html          # Main HTML file with interactive interface
├── style.css           # Styling and responsive design
├── weathersite.js      # Temperature conversion logic
└── README.md           # This documentation file
```

## 🔄 Temperature Conversions

The application converts from **Celsius** to:

### Kelvin (K)
- **Formula**: K = C + 273
- **Example**: 200°C = 473K

### Fahrenheit (°F)
- **Formula**: F = (C × 9/5) + 32
- **Example**: 200°C = 392°F

### Newton (°N)
- **Formula**: N = C × 0.33 (or C × 33/100)
- **Example**: 200°C = 66°N

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. Clone or download the project files
2. Ensure all three files are in the same directory:
   - `index.html`
   - `style.css`
   - `weathersite.js`

### Usage

1. Open `index.html` in your web browser
2. Enter a temperature value in Celsius in the input field (default: 200°C)
3. Click the "Convert" button or press Enter
4. View the converted temperatures in the result boxes
5. Check the browser console (F12 → Console) to see logged output

## 💻 Technical Details

### HTML (`index.html`)
- Semantic HTML5 structure
- Input field for Celsius temperature
- Three result display boxes for different scales
- Embedded JavaScript for interactivity

### CSS (`style.css`)
- Modern gradient background (purple theme)
- Flexbox and CSS Grid layouts
- Smooth transitions and hover effects
- Mobile-first responsive design
- Media queries for devices under 600px

### JavaScript (`weathersite.js` & embedded script)
- Temperature conversion calculations
- DOM manipulation for real-time updates
- Event listeners for user interactions
- Console logging for debugging

## 🎨 Design Features

- **Color Scheme**: Purple gradient (from #667eea to #764ba2)
- **Typography**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Spacing**: Consistent padding and margins for visual hierarchy
- **Shadows**: Subtle box shadows for depth
- **Animations**: Smooth transitions on button hover and focus states

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with 3-column grid for results
- **Tablet**: Optimized spacing and font sizes
- **Mobile** (< 600px): Single-column layout, adjusted typography

## 🔧 Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Code Examples

### Basic Conversion (from weathersite.js)
```javascript
const celsius = 200;
const kelvin = celsius + 273;           // 473
let fahrenheit = celsius * (9 / 5) + 32; // 392
let newton = celsius * (33/100);         // 66
```

### Using the Web Interface
```javascript
// Enter 200 in the input field and click Convert
// Results display:
// Kelvin: 473K
// Fahrenheit: 392°F
// Newton: 66°N
```

## 🐛 Debugging

1. Open Developer Tools (F12 or Cmd+Option+I on Mac)
2. Go to the Console tab
3. Perform a conversion
4. View the logged output:
   ```
   The temperature is 392 degrees Fahrenheit.
   The temperature is 66 degrees Newton.
   ```

## 📚 Learning Resources

- [MDN Web Docs - Temperature Scales](https://en.wikipedia.org/wiki/Temperature_scale)
- [JavaScript Math Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math)
- [CSS Flexbox Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [Responsive Web Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or bug fixes.

## 📄 License

This project is open source and available for educational and personal use.

## 👨‍💻 Author

Created as a demonstration of temperature conversion using HTML, CSS, and JavaScript.

## 📞 Support

For issues or questions, please check the code comments or review the conversion formulas in the Technical Details section.

---