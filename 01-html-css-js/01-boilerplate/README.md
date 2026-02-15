# __HTML Boilerplate__
**This is a template HTML5.  Thanks this boilerplate I can start with a base code.**

## Table of Contents
* [Features](#features)
* [Structure](#structure)
* [How to get started](#how-to-get-started)
* [Customization](#customization)
* [Meta tags explained](#meta-tags-explained)
* [Browser support](#browser-support)

## Features 
* **HTML5** with semantic elements;
* **Meta tag SEO**: for optimization on browser web;
* **Responsive**: thanks to meta viewport configured for mobile device;
* **Open graph**: tag for share to social media;
* **Sources**: CSS and JavaScript file structure;
* **Fonts**: optional but there is the Google Fonts integration;
* **Favicon**: support.

## Structure
```
giachero-gaia-units-01-03/      # main folder
└── 01-html-css-js/             # unit1 folder 
     └── 01-boilerplate/        # project folder
          ├── boileplate.html   # file project HTML
          └── README.md         # file README
```

## How to get started
1. **Download** Boilerplate.
2. **Open** file. 
3. **Edits** the HTML file and customize:  
    * Page title;
    * Meta description;
    * Author name;
    * Open Graph information.
4. **Start** coding.

## Customization
### 1️⃣Change Page Title and Description
```html
<!-- Title of the page -->
<title>Your title here</title>

<!-- Description of SEO -->
<meta name="description" content="Your description here">
```
### 2️⃣Update Author Information
``` html
<!-- Author -->
<meta name="author" content="Your name">
```
### 3️⃣Configure Open Graph Tag
``` html
<meta name="keywords" content="word1, word2, word3">
<meta name="description" content="Description of the web site">
```
### 4️⃣Add Google Fonts 
Uncomment these lines in the `<head>` section:
``` html
<!-- google fonts (optional) -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```
Replace `Your+Font` with your chosen font from [Google Fonts](https://fonts.google.com/).

## Meta tags explained
| **Meta Tag** | **Purpose** |  
|--------------|-------------|
|`charset` | Defines character encoding (UTF-8 supports all languages)|
|`viewport` | Makes the site responsive on mobile devices |
|`X-UA-Compatible`| Ensures compatibility with older IE browsers |
|`description` | Shows up in search engine results |
|`og:*` | Controls how the page appears when shared on social media |

## Browser support
This boilerplate supports all modern browsers:  
✅ Chrome  
✅ Microsoft Edge  
✅ Firefox   
✅ Opera   
✅ Safari  

**_Made by Gaia Giachero_**