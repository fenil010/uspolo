# U.S. Polo Assn. Clone Website

A static website clone of the U.S. Polo Assn. brand e-commerce site, built with HTML and CSS.

## 🌐 Live Demo

Visit the live site: [https://melodious-dolphin-b8e210.netlify.app/](https://melodious-dolphin-b8e210.netlify.app/)

## 📋 Prerequisites

To run this project on your laptop, you need:
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A code editor (optional, for viewing/editing code - VS Code, Sublime Text, etc.)

## 🚀 How to Import and Run on Your Laptop

### Method 1: Download as ZIP

1. Go to the GitHub repository: [https://github.com/fenil010/uspolo](https://github.com/fenil010/uspolo)
2. Click the green **Code** button
3. Select **Download ZIP**
4. Extract the ZIP file to your desired location
5. Open the `index.html` file in your web browser

### Method 2: Clone with Git

If you have Git installed on your laptop:

```bash
# Clone the repository
git clone https://github.com/fenil010/uspolo.git

# Navigate to the project directory
cd uspolo

# Open index.html in your default browser
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html
```

### Method 3: Using a Local Web Server (Recommended)

For the best experience, use a local web server:

#### Using Python (if installed):
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js (if installed):
```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server
```

#### Using VS Code:
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

Then open your browser and navigate to `http://localhost:8000` (or the port shown in your terminal).

## 📁 Project Structure

```
uspolo/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet for the website
├── assets/             # Images and media files
│   ├── logo.avif
│   ├── i1.webp
│   ├── i2.webp
│   ├── p1.webp - p4.webp
│   ├── pic1.webp - pic8.webp
│   ├── img1.webp - img3.webp
│   └── gif.webp
└── README.md           # This file
```

## 🎨 Features

- Responsive navigation bar with icons
- Product showcase sections
- Category browsing
- Blog section
- Store finder functionality
- Email signup form
- Modern UI with U.S. Polo Assn. branding

## 🛠️ Technologies Used

- HTML5
- CSS3
- Font Awesome Icons
- Boxicons

## 📝 Notes

- This is a static website with no backend functionality
- All images are stored locally in the `assets/` folder
- The website uses external CDN links for icons (Font Awesome and Boxicons)

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## 📧 Contact

For any questions or suggestions, please open an issue on GitHub.
