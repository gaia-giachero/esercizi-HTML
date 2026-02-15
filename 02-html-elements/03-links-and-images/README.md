# __Links and Images__
**This is an HTML5 file about volleyball with headers, paragraphs, text formatting elements (bold, italic, underline), inline styles, hyperlinks, and images.**

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
* **Open graph**: tag for share to social media.

## 🗂️ Structure
```
giachero-gaia-units-01-03/                   # main folder
├── 01-html-css-js/                          # unit1 folder 
|    ├── 01-boilerplate                      # project folder ex1
|    └── 02-new-js                           # project folder ex2
|
└── 02-html-elements/                        # unit2 folder
     ├── 01-basic-text                       # project folder ex1
     ├── 02-favorite                         # project folder ex2
     └── 03-links-and-images/                # project folder ex3
         ├── assets/                         # assets folder
         |   └── img/                        # image folder
         |       ├── campo-pallavolo.jpg     # local image
         |       └── pallavolo.jpg           # local image
         ├── index.html                      # file project HTML
         └── README.md                       # file README
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
This project showcases **volleyball-themed content** using fundamental HTML elements:

### 1. Heading Hierarchy
* **h1**: Main page title ("Volleyball")
* **h2**: Major section headers ("What Is Volleyball", "Volleyball at the Olympic Games", "Main International Volleyball Competitions")
* **h3**: Subsection headers ("Email:", "Sources:")

### 2. Text Formatting
* **Bold text** using `<strong>` tag (e.g., "Volleyball", "volley", "The most important international competitions")
* *Italic text* using `<em>` tag (e.g., "volleyball", "Olympic Games program since 1964")
* Underlined text using `<u>` tag (championship names)
* Colored text using `<span>` with inline styles (red text)

### 3. Special Characters
* **Internal links** using anchor tags with `href="#id"` to jump to sections within the page
* **External link** to Wikipedia volleyball page
* **Email link** using `mailto:` protocol
* **Image link** to external image URL

### 4. Images
* Local image displayed using `<img>` tag (campo-pallavolo.jpg)

### 5. Special Characters
* HTML entities for symbols: ☞ (`&#9758;`) and ☺ (`&#9786;`)

### 6. Semantic Structure
* Proper use of paragraphs `<p>`
* Line breaks with `<br />` tags
* ID attributes for linking sections
* Comments explaining code sections
* Logical content organization about volleyball topic

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
| `<h1>` | Main header | "Volleyball" |
| `<h2>` | Section headers with IDs | "What Is Volleyball" (id="chapter1"), etc. |
| `<h3>` | Subsection headers | "Email:", "Sources:" |
| `<p>` | Paragraphs of text | All volleyball description paragraphs |
| `<strong>` | Important text (bold) | "Volleyball", "volley", "The most important international competitions" |
| `<em>` | Emphasized text (italic) | "volleyball", "Olympic Games program since 1964" |
| `<u>` | Underlined text | Championship names (World Championships, Nations League, etc.) |
| `<span>` | Inline container for styling | Red colored text: "team sport played between two teams☺" |
| `<a>` | Hyperlinks | Internal navigation links, email link, external Wikipedia link, image link |
| `<img>` | Display images | Local volleyball court image (campo-pallavolo.jpg) |
| `<br />` | Line breaks | Used to create spacing between links |
| `<script>` | Links external JavaScript file | `<script src="./js/scripts.js"></script>` |
| `id` attribute | Creates anchor points for internal links | id="chapter1", id="chapter2", id="chapter3" |
| `href` attribute | Specifies link destination | `href="#chapter1"`, `href="mailto:..."`, `href="https://..."` |
| `title` attribute | Provides tooltip text | title="The 1st Chapter" |
| `&#9758;` | HTML entity for symbol ☞ | Used at the start of each paragraph |
| `&#9786;` | HTML entity for symbol ☺ | Used in the first paragraph |
| Inline CSS | Quick styling | `style="color: red;"` for colored text |

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
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Validator](https://validator.w3.org/) - Check your HTML code
- [Volleyball Sources](https://it.wikipedia.org/wiki/Pallavolo) - Learn more about volleyball

**_Made by Gaia Giachero_**