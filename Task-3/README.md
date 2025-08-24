# Creative Black Calculator

A sleek, modern calculator with a dark theme and advanced functionality built with HTML, CSS, and JavaScript. Features a stunning black background with neon cyan accents, smooth animations, and both basic and scientific operations.

## ✨ Features

### 🎨 Visual Design
- **Dark gradient background** with animated rotating glow effects
- **Glassmorphism-inspired design** with subtle borders and shadows
- **Neon cyan accents** for displays and hover effects
- **Color-coded button system** for intuitive operation
- **Smooth animations** including button press effects and hover transitions
- **Responsive design** optimized for desktop and mobile devices

### 🔢 Calculator Functions

#### Basic Operations
- ➕ Addition
- ➖ Subtraction  
- ✖️ Multiplication
- ➗ Division
- 🔢 Decimal point support
- ⌫ Backspace/Delete last entry
- 🆑 All Clear (AC)

#### Scientific Operations
- √ Square root
- x² Square (power of 2)
- % Percentage calculations
- 1/x Reciprocal
- ± Sign toggle (positive/negative)

#### Memory Functions
- **MC** - Memory Clear
- **MR** - Memory Recall
- **M+** - Memory Add
- **M-** - Memory Subtract

### ⌨️ Keyboard Support
- **Numbers 0-9**: Input numbers
- **Operators (+, -, *, /)**: Mathematical operations
- **Enter/=**: Calculate result
- **Escape**: Clear all
- **Backspace**: Delete last character
- **.**: Decimal point

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. **Download the HTML file**
   ```bash
   # Clone or download the calculator.html file
   wget [your-file-url] -O calculator.html
   ```

2. **Open in browser**
   ```bash
   # Simply double-click the HTML file or
   open calculator.html
   ```

3. **Or serve locally**
   ```bash
   # Using Python's built-in server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 🎯 Usage

### Basic Calculations
1. Click number buttons to input values
2. Click operator buttons (+, -, ×, ÷) 
3. Input second number
4. Press = or Enter to calculate

### Scientific Functions
- **Square Root (√)**: Input number → Click √
- **Square (x²)**: Input number → Click x²
- **Percentage (%)**: Input number → Click %
- **Reciprocal (1/x)**: Input number → Click 1/x
- **Sign Toggle (±)**: Input number → Click ± to make positive/negative

### Memory Operations
1. **Store in memory**: Calculate a result → Click M+ to add to memory
2. **Recall from memory**: Click MR to display stored value
3. **Add to memory**: Input number → Click M+ to add to existing memory
4. **Subtract from memory**: Input number → Click M- to subtract from memory
5. **Clear memory**: Click MC to reset memory to zero

## 🛠️ Technical Details

### Architecture
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Advanced styling with gradients, animations, and grid layout
- **Vanilla JavaScript**: Pure JS with no external dependencies

### Key Technologies Used
- **CSS Grid**: 5-column responsive button layout
- **CSS Gradients**: Complex multi-layer background effects
- **CSS Animations**: Rotating glow effects and button interactions
- **JavaScript Event Listeners**: Keyboard and mouse input handling
- **Error Handling**: Division by zero and invalid operation protection

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Design

### Desktop (450px+ width)
- Full 5-column layout
- Large buttons (75px height)
- Extended display area
- All animations enabled

### Mobile (< 480px width)
- Compressed layout maintaining functionality
- Adjusted button sizes (65px height)
- Optimized font sizes
- Touch-friendly interface

## 🎨 Customization

### Color Themes
The calculator uses CSS custom properties that can be easily modified:

```css
/* Main color scheme */
--primary-bg: linear-gradient(145deg, #1e1e1e, #2a2a2a);
--accent-color: #00ffff;
--text-primary: #ffffff;
--text-secondary: #888888;

/* Button categories */
--number-bg: linear-gradient(145deg, #2d2d2d, #404040);
--operator-bg: linear-gradient(145deg, #ff6b35, #ff8c42);
--equals-bg: linear-gradient(145deg, #00ff88, #00cc66);
--memory-bg: linear-gradient(145deg, #6c5ce7, #a29bfe);
--scientific-bg: linear-gradient(145deg, #00cec9, #55efc4);
```

### Layout Modifications
- **Button Grid**: Modify `grid-template-columns` in `.buttons`
- **Spacing**: Adjust `gap` property for button spacing
- **Sizing**: Change `height` and `font-size` for buttons

## 🐛 Error Handling

The calculator includes robust error handling for:
- **Division by zero**: Displays alert and prevents calculation
- **Square root of negative**: Prevents invalid mathematical operations
- **Invalid inputs**: Filters non-numeric input
- **Display overflow**: Limits input length to prevent display issues

## 🔒 Security Features

- **Input validation**: All user inputs are sanitized
- **Safe evaluation**: Uses explicit mathematical operations instead of `eval()`
- **Memory protection**: Memory values are stored in controlled variables
- **XSS prevention**: No dynamic HTML generation from user input

## 📊 Performance

- **Lightweight**: Single HTML file under 15KB
- **Fast rendering**: Pure CSS animations with hardware acceleration
- **Efficient JavaScript**: Event-driven architecture with minimal DOM manipulation
- **Memory efficient**: Automatic cleanup of calculation variables

## 🤝 Contributing

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across browsers
5. Submit a pull request

### Code Style
- Use meaningful variable names
- Comment complex calculations
- Maintain consistent indentation
- Follow existing naming conventions

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

### Common Issues

**Calculator not responding**
- Check JavaScript console for errors
- Ensure browser supports ES6+ features
- Verify HTML file is complete

**Display issues on mobile**
- Clear browser cache
- Check viewport meta tag
- Test in different orientations

**Keyboard shortcuts not working**
- Click on calculator area to focus
- Check for conflicting browser shortcuts
- Try using number pad vs top row numbers

### Getting Help
- Check browser developer console for errors
- Verify all HTML tags are properly closed
- Test in different browsers to isolate issues

## 🌟 Acknowledgments

- Design inspired by modern dark mode interfaces
- Color palette optimized for accessibility
- Mathematical functions follow standard calculator conventions

---

**Version**: 1.0.0  
**Last Updated**: August 2025  
**Tested Browsers**: Chrome 127+, Firefox 128+, Safari 17+, Edge 127+
