# 💰 Debit Credit Calculator

A simple, elegant web-based calculator for processing debit and credit entries with automatic data cleaning and real-time calculations.

## ✨ Features

- **Smart Data Processing**: Automatically removes alphabets and spaces from pasted data
- **Flexible Input Formats**: Supports comma-separated, line-by-line, or mixed entry formats
- **Real-time Calculations**: Auto-calculates as you type (1-second debounce)
- **Accounting Logic**: Credits are added (+), Debits are subtracted (-)
- **Large Result Display**: Prominent display of final calculation
- **Data Transparency**: Shows how each entry was processed
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean, gradient-based design with smooth animations

## 🚀 Live Demo

Simply download the HTML file and open it in any modern web browser. No server or installation required!

## 📝 Usage

### Input Formats Supported

The calculator accepts various input formats:

```
9271.977 Cr, 200 Dr
9271.977 Cr - 200 Dr
9271.977 Cr
200 Dr
1500.50
```

### Entry Types

- **Credits (Cr)**: Added to the result (+)
- **Debits (Dr)**: Subtracted from the result (-)
- **Plain Numbers**: Treated as credits by default

### Example Calculation

**Input:**
```
9271.977 Cr
200 Dr
```

**Calculation:**
```
Credits: 9271.977
Debits: 200.00
Result: 9271.977 - 200.00 = 9071.977
```

## 🛠️ How It Works

1. **Data Cleaning**: Removes all alphabetic characters and spaces, keeping only numbers and decimal points
2. **Classification**: Identifies entries as credits (Cr) or debits (Dr) based on suffixes
3. **Calculation**: Applies the formula: `Result = Total Credits - Total Debits`
4. **Display**: Shows breakdown of credits, debits, and final result

## 📋 Installation

### Option 1: Download and Run Locally
1. Download the `index.html` file
2. Open it in any web browser
3. Start entering your data!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/debit-credit-calculator.git
cd debit-credit-calculator
# Open index.html in your browser
```

## 🎨 Screenshots

### Main Interface
- Clean, modern design with gradient backgrounds
- Separate sections for input and results
- Real-time processing feedback

### Results Display
- Large, prominent final result
- Breakdown of credits and debits
- Transparent data processing view

## 🔧 Technical Details

- **Frontend**: Pure HTML, CSS, JavaScript
- **No Dependencies**: Runs entirely in the browser
- **Storage**: Uses in-memory variables (no localStorage)
- **Compatibility**: Works with all modern browsers

## 📱 Mobile Support

Fully responsive design that works seamlessly on:
- Desktop computers
- Tablets
- Mobile phones

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💡 Feature Requests

Have an idea for improvement? Please open an issue with:
- Clear description of the feature
- Use case examples
- Any relevant screenshots or mockups

## 🐛 Bug Reports

Found a bug? Please report it with:
- Steps to reproduce
- Expected behavior
- Actual behavior
- Browser and version information

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the need for quick debit/credit calculations in accounting
- Built with modern web technologies for maximum compatibility
- Designed with user experience and accessibility in mind

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Check existing issues for solutions
- Review the documentation above

---

**Made with ❤️ for accountants and finance professionals**
