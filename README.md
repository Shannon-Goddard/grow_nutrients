# Cannabis Grow Nutrients Guide

![header](pics/header.png)

A comprehensive interactive web application for cannabis growers to explore and compare different nutrient brands and feeding systems. This tool provides detailed information about popular hydroponic and organic nutrient lines to help growers make informed decisions for their cultivation setup.

## 🌿 Live Demo

**[View Live Application](https://shannon-goddard.github.io/grow_nutrients/)**

*Part of the GrowApp Cannabis ecosystem - [growappcannabis.guide](https://growappcannabis.guide)*

## 📋 Table of Contents

- [Features](#features)
- [Nutrient Brands](#nutrient-brands)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Integration](#integration)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Interactive Dropdown Menu**: Easy-to-use interface for nutrient brand selection
- **Detailed Product Information**: Comprehensive descriptions, usage instructions, and benefits
- **Brand Logos & Product Images**: Visual identification of nutrient lines
- **Direct Links**: Quick access to manufacturer websites for purchasing
- **Responsive Design**: Mobile-friendly interface with Bootstrap framework
- **Professional Branding**: Loyal9 LLC branded interface

## 🧪 Nutrient Brands

The application features 6 popular cannabis nutrient brands:

1. **Mammoth Silica (SI)** - Premium silica supplement for enhanced plant structure
2. **General Hydroponics BioThrive** - Organic grow and bloom nutrients
3. **Technaflora Recipe for Success** - Complete starter nutrient kit
4. **General Hydroponics Flora Series** - Original 3-part hydroponic system
5. **Fox Farm Liquid Trio** - Big Bloom, Grow Big, and Tiger Bloom pack
6. **Advanced Nutrients Bud Candy** - Carbohydrate supplement for enhanced flavors

## 🛠 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Framework**: Bootstrap 4.6.1
- **Libraries**: jQuery 3.6.0, D3.js 4.11.0
- **Icons**: Font Awesome 4.7.0
- **Styling**: Custom CSS with responsive design

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shannon-Goddard/grow_nutrients.git
   cd grow_nutrients
   ```

2. **Open in browser**:
   ```bash
   # Simply open index.html in your web browser
   open index.html
   ```

3. **Or serve locally**:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 📖 Usage

### Basic Navigation

1. **Select Nutrients**: Click the "Dropdown" button to view available nutrient brands
2. **View Details**: Click on any nutrient brand to see detailed information
3. **Visit Manufacturer**: Click the website link to visit the official product page
4. **Mobile Navigation**: Use the hamburger menu for mobile navigation

### Integration with GrowApp

This nutrient guide integrates seamlessly with the broader GrowApp ecosystem:

- **Strain Database**: Works with [grow_data](../grow_data) strain information
- **Filtering Interface**: Complements [grow_filter](../grow_filter) search capabilities
- **Main Application**: Powers nutrient selection in [growappcannabis.guide](https://growappcannabis.guide)

## 📁 Project Structure

```
grow_nutrients/
├── pics/                    # Header images and graphics
│   ├── gif.gif
│   └── header.png
├── static/
│   ├── CSS/
│   │   └── style.css       # Custom styling
│   ├── images/             # Brand logos and product images
│   │   ├── an_logo.png     # Advanced Nutrients
│   │   ├── biothrive.png   # BioThrive products
│   │   ├── fox_logo.png    # Fox Farm
│   │   ├── gh_logo.png     # General Hydroponics
│   │   └── ...
│   └── js/
│       ├── app.js          # Application logic
│       └── data.js         # Nutrient data structure
├── index.html              # Main application interface
├── LICENSE                 # MIT License
└── README.md              # Project documentation
```

## 🔗 Integration

### Data Structure

The nutrient data is structured for easy integration:

```javascript
{
  index: "0",
  name: "manufacturer-website.com",
  web: "https://manufacturer-website.com/product/",
  nute: "static/images/logo.png",
  info: "Detailed product description...",
  pic: "static/images/product.png"
}
```

### API Compatibility

- Compatible with GrowApp main application
- Integrates with strain database for complete grow planning
- Supports mobile and desktop interfaces

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/nutrient-brand`)
3. Commit changes (`git commit -am 'Add new nutrient brand'`)
4. Push to branch (`git push origin feature/nutrient-brand`)
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Copyright (c) 2025 Shannon Goddard | Loyal9 LLC**

## ⚠️ Disclaimer

This application is for educational and informational purposes only. Always follow local laws and regulations regarding cannabis cultivation. Nutrient information is provided for reference - consult manufacturer guidelines for proper usage and dosing.

---

*Built with 🌿 by Shannon Goddard | Part of the Loyal9 LLC Cannabis Technology Suite*