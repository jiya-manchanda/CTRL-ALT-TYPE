# Font Identification and Accessibility Checker

## Overview

The **Font Identification and Accessibility Checker** is a powerful tool that integrates **font identification** and **accessibility evaluation** into a single workflow. It allows users to identify fonts from images and evaluate their compliance with accessibility standards like the Web Content Accessibility Guidelines (WCAG). This tool is ideal for designers, developers, educators, and accessibility advocates, providing insights into font usability while promoting inclusivity.

## Features

### Font Identification
- **Image-Based Font Recognition**: Upload an image containing text to identify fonts.
- **Feature Extraction**:
  - Serif vs. Sans-Serif classification.
  - Weight analysis (light, bold, etc.).
  - x-height, ascenders, and descenders measurements.
- **Database Matching**: Compare extracted font features against a database or use APIs like WhatTheFont.
- **Interactive Selection**: Use an image picker to select specific text regions for analysis.

### Accessibility Checker
- **Legibility Analysis**:
  - Evaluate fonts for compliance with WCAG standards.
  - Assess character spacing, contrast ratios, and font weight.
- **Dyslexia-Friendliness**: Check for distinct letterforms and readability for users with dyslexia.
- **Real-Time Adjustments**: Modify font settings such as size, weight, and spacing, and re-evaluate results dynamically.

### Exportable Reports
- Generate detailed `.txt` or `.pdf` reports summarizing:
  - Font identification results.
  - Accessibility evaluation metrics.
  - Recommendations for improvement.

---

## Real-World Applications

### 1. Design Industry
Streamline workflows for font identification and analysis in branding, web design, and creative projects. Designers can ensure fonts align aesthetically while maintaining accessibility.

### 2. Web Development
Improve website usability by ensuring fonts meet WCAG standards, making digital content more accessible to users with visual impairments.

### 3. Accessibility Advocacy
Empower organizations to create inclusive materials. This tool helps identify and address potential readability barriers in content.

### 4. Education
Serve as a resource for teaching typography, font design principles, and accessibility guidelines. It offers practical, hands-on learning experiences.

### 5. Historical Preservation
Aid in identifying fonts in historical documents, facilitating accurate digital restoration and preserving cultural heritage.

---

## Installation

### Prerequisites
- **Python 3.8+**
  - Libraries: `Pillow`, `opencv-python`, `pytesseract`, `fontTools`, `reportlab`
- **Node.js** (Optional for web-based interface)
  - Libraries: `Tesseract.js`, `Canvas API`

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/font-accessibility-checker.git
   cd font-accessibility-checker
