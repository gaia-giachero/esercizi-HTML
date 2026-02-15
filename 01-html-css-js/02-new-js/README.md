# __New JS__
**This is a template HTML5 with a tag script for JavaScript file.**

## Table of Contents
* [Features](#features)
* [Structure](#structure)
* [How to get started](#how-to-get-started)
* [Technologies Used](#technologies-used)
* [What It Does](#what-it-does)
* [Meta tags explained](#meta-tags-explained)
* [Browser support](#browser-support)

## Features 
* **HTML5** with semantic elements;
* **Meta tag SEO**: for optimization on browser web;
* **Responsive**: thanks to meta viewport configured for mobile device;
* **Open graph**: tag for share to social media;
* **Sources**: JavaScript file structure.

## Structure
```
giachero-gaia-units-01-03/      # main folder
└── 01-html-css-js/             # unit1 folder 
     ├── 01-boilerplate         # project folder ex1
     └── 02-new-js/             # project folder ex2
          ├── index.html        # file project HTML
          ├── main.js           # file project JS
          └── README.md         # file README
```

## How to get started
### Method 1: Double-Click (Easiest)
1. **Download** all project files to your computer
2. **Double-click** on `index.html`
3. The page will open in your default browser
4. **Open Developer Tools** to see the console:
   * **Windows/Linux**: Press `F12` or `Ctrl + Shift + I`
   * **Mac**: Press `Cmd + Option + I`
5. Click on the **Console** tab
6. You should see "Gaia" printed in the console.

### Method 2: Using VS Code Live Server (Recommended for Development)
1. **Open** the project folder in Visual Studio Code
2. **Install** the "Live Server" extension (if not already installed)
3. **Right-click** on `index.html`
4. Select **"Open with Live Server"**
5. The page will open automatically in your browser
6. **Open Developer Tools** to see the console:
   * **Windows/Linux**: Press `F12` or `Ctrl + Shift + I`
   * **Mac**: Press `Cmd + Option + I`
7. Click on the **Console** tab
8. You should see "Gaia" printed in the console.

## Technologies Used
* **HTML5** - Page structure
* **JavaScript** - Programming logic
* **Browser Console** - Output display

## What It Does
This project demonstrates the **most basic** JavaScript functionality:

1. **HTML file** loads the page structure
2. **JavaScript file** (`main.js`) runs when the page loads
3. The JavaScript prints **"Gaia"** to the browser console
4. You need to open **Developer Tools** to see the output

### Code Breakdown
**HTML (index.html):**
```html
<script src="main.js"></script>
```
This line loads and executes the JavaScript file.

**JavaScript (main.js):**
```javascript
console.log("Gaia");
```
This command prints text to the browser console (not visible on the page).

## Meta tags explained
| **Meta Tag** | **Purpose** |  
|--------------|-------------|
|`charset` | Defines character encoding (UTF-8 supports all languages)|
|`viewport` | Makes the site responsive on mobile devices |
|`X-UA-Compatible`| Ensures compatibility with older IE browsers |
|`description` | Shows up in search engine results |
|`og:*` | Controls how the page appears when shared on social media |

## Browser support
This HTML and JavaScript supports all modern browsers:  
✅ Chrome  
✅ Microsoft Edge  
✅ Firefox  
✅ Opera   
✅ Safari (testing with App Web Inspector on iPad)  

**_Made by Gaia Giachero_**