# __Baked trofie with speck and walnuts__
**This is an HTML5 file about a delicious Italian recipe with navigation, tables, lists, images, and structured content for a family-friendly meal.**

## Table of Contents
* [Features](#features)
* [Structure](#structure)
* [How to get started](#how-to-get-started)
* [What It Demonstrates](#what-it-demonstrates)
* [Meta tags explained](#meta-tags-explained)
* [HTML Elements Used](#html-elements-used)
* [Technologies Used](#technologies-used)
* [Browser support](#browser-support)
* [Resources](#resources)

## Features 
* **HTML5** with semantic elements;
* **Meta tag SEO**: for optimization on browser web;
* **Responsive**: thanks to meta viewport configured for mobile device;
* **Open graph**: tag for share to social media;
* **Internal navigation**: quick jump to recipe sections;
* **Visual content**: images of ingredients and final dish.

## Structure
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
     ├── 04-list-and-tables               # project folder ex4
     └── 05-complete-html5-page/          # project folder ex5
         ├── assets/                      # assets folder
         |   └── img/                     # image folder
         |       ├── trofie.jpg           # trofie pasta image
         │       ├── speck.jpg            # speck image
         │       ├── walnuts.jpg          # walnuts image
         │       ├── complete.jpg         # finished dish image
         │       └── baking-dish.jpg      # dish in oven image
         ├── index.html                   # file project HTML
         └── README.md                    # file README
```

## How to get started
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

## What It Demonstrates
This project showcases an **Italian baked pasta recipe** using fundamental HTML elements:

### 1. Heading Hierarchy
* **h1**: Main page title ("BAKED TROFIE WITH SPECK AND WALNUTS")
* **h3**: Section headers ("Ingredients:", "Procedure:", "Sources")

### 2. Navigation
* **Internal navigation menu** using a table with anchor links
* Links jump to specific sections: Ingredients, Procedure, and Sources
* ID attributes used as anchor points (`id="Ingredients"`, `id="Procedure"`, `id="Sources"`)

### 3. Lists
* **Unordered lists** (`<ul>`) for ingredients:
  - Pasta ingredients (trofie, speck, walnuts, rosemary, cheeses, oil)
  - Béchamel sauce ingredients (milk, butter, flour, seasonings)
* **Ordered list** (`<ol>`) for step-by-step cooking procedure
* **Nested list** within procedure for béchamel preparation steps

### 4. Tables
* **Navigation table** for internal links
* **Ingredient images table** displaying main components (trofie, speck, walnuts)
* **Final result table** showing completed dish and baking dish
* **Sources table** with links to image sources

### 5. Images
* Multiple local images using `<img>` tags with inline styling
* Images of ingredients (trofie, speck, walnuts)
* Images of final dish (complete.jpg, baking-dish.jpg)
* Styled with width attributes for consistent sizing

### 6. Text Formatting
* **Underlined text** using `<u>` tag for ingredient subsections ("For the pasta:", "For the béchamel sauce:")
* **Special character** &#9758; (☞) used as a decorative pointing hand before sections

### 7. Links
* **Internal anchor links** in navigation menu
* **External links** to image sources
* **Link to video recipe** on Instagram as the recipe source

### 8. Semantic Structure
* Proper use of paragraphs `<p>`
* Logical content organization (navigation → ingredients → procedure → sources)
* Comments separating main content section
* Appropriate use of table elements (thead, tbody, tr, td, th)

## Meta tags explained
| **Meta Tag** | **Purpose** |  
|--------------|-------------|
|`charset` | Defines character encoding (UTF-8 supports all languages)|
|`viewport` | Makes the site responsive on mobile devices |
|`X-UA-Compatible`| Ensures compatibility with older IE browsers |
|`title` | "Baked trofie with speck and walnuts" - shows in browser tab |
|`description` | "A recipe that everyone likes, useful for family lunches" |
|`og:type` | Defines content as "article" for social media |
|`og:title` | "Recipe that everyone likes" - title shown when shared |
|`og:description` | Full recipe description for social media previews |

## HTML Elements Used
| Element | Purpose | Example in Project |
|---------|---------|-------------------|
| `<h1>` | Main header | "BAKED TROFIE WITH SPECK AND WALNUTS" |
| `<h3>` | Section headers with IDs | "Ingredients:" (id="Ingredients"), "Procedure:", "Sources" |
| `<nav>` | Navigation section | Contains internal navigation table |
| `<table>` | Organize data in rows/columns | Navigation menu, ingredient images, sources |
| `<thead>` | Table header section | "Main Ingredients", "Sources Images" |
| `<tbody>` | Table body section | Contains table data rows |
| `<tr>` | Table row | Each row of navigation or images |
| `<td>` | Table data cell | Individual cells with links or images |
| `<th>` | Table header cell | Column headers with colspan |
| `<ul>` | Unordered list | Ingredient lists for pasta and béchamel |
| `<ol>` | Ordered list | Step-by-step cooking procedure (6 steps) |
| `<li>` | List item | Each ingredient or cooking step |
| `<p>` | Paragraphs | Section separators and descriptions |
| `<u>` | Underlined text | "For the pasta:", "For the béchamel sauce:" |
| `<b>` | Bold text | "Sources recipe:" label |
| `<a>` | Hyperlinks | Internal navigation, external image sources, Instagram recipe |
| `<img>` | Display images | Ingredient photos, finished dish photos |
| `href` attribute | Link destination | `href="#Ingredients"`, `href="https://..."` |
| `id` attribute | Anchor points for internal links | id="Ingredients", id="Procedure", id="Sources" |
| `style` attribute | Inline CSS styling | Image width sizing (100px, 160px) |
| `colspan` attribute | Spans table cells across columns | Merges header cells for "Main Ingredients" and "Sources Images" |
| `border` attribute | Adds borders to table | `border="1"` on sources table |
| `&#9758;` | HTML entity for symbol ☞ | Decorative pointing hand before ingredient sections |

## Technologies Used
* **HTML5** - Document structure
* **Tables** - Data organization and layout
* **Lists** - Structured ingredient and procedure presentation
* **Inline CSS** - Basic image styling

## Browser support
This HTML supports all modern browsers:  
✅ Chrome  
✅ Microsoft Edge  
✅ Firefox  
✅ Opera  
✅ Safari on iPhone and iPad  
✅ Chrome on Android 

## Resources
- [MDN Web Docs - HTML Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
- [W3Schools - HTML Tables](https://www.w3schools.com/html/html_tables.asp)
- [W3Schools - HTML Lists](https://www.w3schools.com/html/html_lists.asp)
- [HTML Validator](https://validator.w3.org/) - Check your HTML code
- [Original Recipe Video](https://www.instagram.com/reel/DPbP2FQDLO5/?utm_source=ig_web_button_share_sheet) - Watch the recipe on Instagram

**_Made by Gaia Giachero_**