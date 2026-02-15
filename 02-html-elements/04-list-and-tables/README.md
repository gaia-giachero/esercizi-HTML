# __List and tables__
**This is an HTML5 file demonstrating ordered lists, unordered lists, and HTML tables with various types of content including links and images.**

## 📍 Table of Contents
* [Features](#features)
* [Structure](#structure)
* [How to get started](#how-to-get-started)
* [What It Demonstrates](#What-It-Demonstrates)
* [Meta tags explained](#meta-tags-explained)
* [HTML Elements Used](#HTML-Elements-Used)
* [Technologies Used](#technologies-used)
* [Browser support](#browser-support)
* [Resources](#Resources)

## 📑 Features 
* **HTML5** with semantic elements;
* **Meta tag SEO**: for optimization on browser web;
* **Responsive**: thanks to meta viewport configured for mobile device;
* **Open graph**: tag for share to social media;
* **Internal navigation**: with anchor links to jump between sections;
* **Lists**: ordered and unordered lists with various content types;
* **Tables**: structured data display with headers and body rows.

## 🗂️ Structure
```
giachero-gaia-units-01-03/                # main folder
├── 01-html-css-js/                       # unit1 folder 
|    ├── 01-boilerplate                   # project folder ex1
|    └── 02-new-js                        # project folder ex2
|
└── 02-html-elements/                     # unit2 folder
     ├── 01-basic-text                    # project folder ex1
     ├── 02-favorite                      # project folder ex2
     ├── 03-links-and-images              # project folder ex3
     └── 04-list-and-tables/              # project folder ex4
         ├── assets/                      # assets folder
         |   └── img/                     # image folder
         |       ├── city.jpg             # local image
         |       ├── earth.jpg            # local image
         |       ├── mountains.jpg        # local image
         |       ├── nature.jpg           # local image
         |       ├── sea.jpg              # local image
         |       └── VanGogh.jpg          # local image
         ├── index.html                   # file project HTML
         └── README.md                    # file README
```

## 🎯 How to get started
### Method 1: Double-Click (Easiest)
1. **Download** all project files
2. **Double-click** on `index.html`
3. The page will open in your default browser
4. You'll see all the headers and formatted text

### Method 2: Using VS Code Live Server (Recommended)
1. **Open** the project folder in Visual Studio Code
2. **Install** the "Live Server" extension
3. **Right-click** on `index.html`
4. Select **"Open with Live Server"**
5. The page opens automatically with live reload

## 🔍 What It Demonstrates
This project showcases **lists and tables** using fundamental HTML elements:

### 1. Heading Hierarchy
* **h1**: Main page title ("List and Tables")
* **h2**: Section headers with IDs for navigation (id="chapter1" through id="chapter7")

### 2. Navigation Menu
* **Internal anchor links** at the top of the page linking to all 7 sections
* Each link includes a `title` attribute for accessibility

### 3. Lists
* **Ordered List (ol)**: Numbered list of items (Table, Chairs, Glass, etc.)
* **Unordered List (ul)**: Bulleted list of elements
* **List of Links**: Ordered list containing hyperlinks to external resources (Wikipedia, W3Schools, Google)
* **List of Images**: 
  - Unordered list with links to external images
  - Ordered list with locally hosted images displayed inline

### 4. Tables
* **First Table**: Basic 3x3 table demonstrating table structure
* **Second Table**: Table with HTML element references and W3Schools documentation links
* **Third Table**: Complex table combining text, external links, and embedded images

### 5. Visual Separators
* **Horizontal rules** (`<hr />`) used to visually separate sections

### 6. Images
* **6 local images** displayed in lists and tables with inline width styling (20%)
* Images include: earth.jpg, nature.jpg, mountains.jpg, sea.jpg, VanGogh.jpg, city.jpg

### 7. Semantic Structure
* Proper use of table elements (`<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`)
* List items (`<li>`) within ordered and unordered lists
* Line breaks with `<br />` tags
* ID attributes for section linking
* Comments explaining code sections

## 📝 Meta tags explained
| **Meta Tag** | **Purpose** |  
|--------------|-------------|
|`charset` | Defines character encoding (UTF-8 supports all languages)|
|`viewport` | Makes the site responsive on mobile devices |
|`X-UA-Compatible`| Ensures compatibility with older IE browsers |
|`description` | Shows up in search engine results |
|`og:*` | Controls how the page appears when shared on social media |

## 📚 HTML Elements Used
| Element | Purpose | Example in Project |
|---------|---------|-------------------|
| `<h1>` | Main header | "List and Tables" |
| `<h2>` | Section headers with IDs | "Ordered List" (id="chapter1"), "Unordered List" (id="chapter2"), etc. |
| `<a>` | Hyperlinks | Navigation menu, external links to W3Schools, Wikipedia, Google |
| `<br />` | Line breaks | Used after navigation links |
| `<hr />` | Horizontal rule (divider) | Separates each section visually |
| `<ol>` | Ordered list (numbered) | List of items (Table, Chairs...), list of links, list of local images |
| `<ul>` | Unordered list (bulleted) | List of elements, list of external image links |
| `<li>` | List item | All items within `<ol>` and `<ul>` |
| `<table>` | Table container | Three different tables demonstrating various uses |
| `<thead>` | Table header section | Contains header rows with `<th>` elements |
| `<tbody>` | Table body section | Contains data rows with `<td>` elements |
| `<tr>` | Table row | Defines each row in tables |
| `<th>` | Table header cell | Column headers (e.g., "Element", "What Is", "Sources") |
| `<td>` | Table data cell | Table content cells |
| `<img>` | Display images | Local images with inline width styling (style="width: 20%;") |
| `<script>` | Links external JavaScript file | `<script src="./js/scripts.js"></script>` |
| `id` attribute | Creates anchor points for internal links | id="chapter1" through id="chapter7" |
| `href` attribute | Specifies link destination | `href="#chapter1"`, `href="https://..."` |
| `title` attribute | Provides tooltip text | title="The 1st Chapter" |
| `border` attribute | Defines table border | border="1" on all tables |
| `style` attribute | Inline CSS styling | style="width: 20%;" on images |

## 🛠️ Technologies Used
* **HTML5** - Document structure
* **CSS3** - Styling (inline with `<span>`)

## 💻 Browser support
This HTML supports all modern browsers:  
✅ Chrome  
✅ Microsoft Edge  
✅ Firefox  
✅ Opera  
✅ Safari on iPhone and iPad  
✅ Chrome on Android 

## 📖 Resources
- [MDN Web Docs - HTML Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [MDN Web Docs - HTML Tables](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
- [MDN Web Docs - HTML Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Validator](https://validator.w3.org/) - Check your HTML code

**_Made by Gaia Giachero_**