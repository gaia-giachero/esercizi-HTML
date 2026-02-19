# __Astronaut Application Form__
**This is an HTML5 interactive form for astronaut applications with multiple input types, form validation, data collection, and integration with external services (SheetDB/Webhook).**

## Table of Contents
* [Features](#features)
* [Structure](#structure)
* [How to get started](#how-to-get-started)
* [What It Demonstrates](#what-it-demonstrates)
* [Meta tags explained](#meta-tags-explained)
* [HTML Elements Used](#html-elements-used)
* [Key Attributes Used](#key-attributes-used)
* [Technologies Used](#technologies-used)
* [Browser support](#browser-support)
* [Resources](#resources)

## Features 
* **HTML5** with semantic elements;
* **Meta tag SEO**: for optimization on browser web;
* **Responsive**: thanks to meta viewport configured for mobile device;
* **Open graph**: tag for share to social media with custom image;
* **Comprehensive form**: multiple input types and validation;
* **Data collection**: integration with SheetDB API (Google Sheets);
* **Form validation**: required fields, min/max values, and specific input types.

## Structure
```
giachero-gaia-units-01-03/                   # main folder
├── 01-html-css-js/                          # unit1 folder 
|    ├── 01-boilerplate                      # project folder ex1
|    └── 02-new-js                           # project folder ex2
|
├── 02-html-elements/                        # unit2 folder
|    ├── 01-basic-text                       # project folder ex1
|    ├── 02-favorite                         # project folder ex2
|    ├── 03-links-and-images                 # project folder ex3
|    ├── 04-list-and-tables                  # project folder ex4
|    └── 05-complete-html5-page              # project folder ex5
|
└── 03-html-form/                            # unit3 folder
     ├── astronaut-application-data.xlsx     # file Google Sheet to save data 
     ├── index.html                          # main application form HTML file
     └── README.md                           # this README file
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
This project showcases a **comprehensive astronaut application form** using fundamental HTML form elements:

### 1. Heading and Structure
* **h1**: Main page title
* **p**: Introductory text prompting users to complete the form.

### 2. Form Element
* **Action attribute**: Connects to SheetDB API (`https://sheetdb.io/api/v1/9tl5f6gncv5ov`)
* **Method**: POST request to submit data
* **Target**: Opens in new tab (`target="_blank"`)
* **Alternative option**: Commented webhook integration for advanced data handling

### 3. Fieldsets (Organized Sections)
The form is divided into **7 fieldsets**, each with a `<legend>` for clear section identification:

#### A. **ANAGRAPHIC**
* Text inputs for: Name (required), Second name (optional), Surname (required)
* Placeholder text guides users on what to enter
* `required` attribute ensures mandatory fields are filled

#### B. **PERSONAL INFORMATION**
* Text input for target mission (required)
* Number input for age with minimum value of 18 (required)
* Text input for nationality (required)
* Radio buttons for gender selection (Man, Woman, Other) with "Man" checked by default

#### C. **PHYSICAL CHARACTERISTICS**
* Color picker for hair color (`type="color"`)
* Dropdown select menu for eye color (Brown, Blue, Green, Grey) with required selection
* Number input for body weight with min (0) and max (100 kg) validation (required)

#### D. **OTHER INFORMATION**
* Email input with validation (`type="email"`, required)
* Telephone input (`type="tel"`) with max length of 10 digits (required)
* Text input for address (optional)

#### E. **ACADEMIC AND PROFESSIONAL PROFILE**
* Multiple checkboxes (`name="qualifications[]"`) allowing users to select one or more educational qualifications:
  * Middle School Diploma
  * High School Diploma
  * Professional Qualification
  * Bachelor's Degree
  * Master's Degree
  * Single-Cycle Degree
  * Specialization Diploma
  * PhD
  * AFAM Qualifications
  * ITS (Technical Institute for Technical Studies)

#### F. **CURRICULUM**
* File upload input accepting PDF files only (`accept=".pdf"`)
* Note: Only filename is saved with SheetDB; full file upload requires webhook

#### G. **BIOGRAPHY**
* Textarea for a personal biography (max 255 characters)
* Specified dimensions: 6 rows × 100 columns
* Character limit enforced with `maxlength="255"`

### 4. Form Controls
* **Submit button**: Sends form data to the specified action URL
* **Reset button**: Clears all form fields and returns them to default values

### 5. Input Types Demonstrated
| Input Type| Purpose | Example Fields|
|-----------|---------|---------------|
|`text`| Single-line text entry | Name, Surname, Nationality, Address |
|`number`| Numeric values with constraints | Age (min 18), Body weight (max 100kg) |
|`radio`| Single selection form options | Gender selection |
|`color`| Color picker | Hair color |
|`select`| Dropdown menu | Eye color selection |
|`email`| Email validation | Email address |
|`tel`| Telephone number | Phone number (maxlength 10) |
|`checkbox`| Multiple selections | Educational qualifications |
|`file` | File upload | Curriculum PDF |
|`textarea`| Multi-line text | Biography (max 255 chars) |

### 6. Form Validation Features
* **Required fields**: Ensure that the fields are filled in
* **Min/max values**: Age >= 18, Bodu witght <= 100kg
* **Input patterns**: Email format validation
* **Character limits**: Telephone (10 chars), Biography (255 chars)
* **File type restrictions**: Only PDF files accept for curriculum
* **Default selections**: "Man" for gender

### 7. Comments and Documentation
* Inline HTML comments explaining form action options (SheetDB vs Webhook)
* Note about curriculum upload functionality differences between services

## Meta tags explained
| **Meta Tag** | **Purpose** |  
|--------------|-------------|
|`charset` | Defines character encoding (UTF-8 supports all languages)|
|`viewport` | Makes the site responsive on mobile devices |
|`X-UA-Compatible`| Ensures compatibility with older IE browsers |
|`title` | "Astronaut Application" - shows in browser tab |
|`description` | "Apply now for the upcoming space mission. Fill out your academic and physical profile to join our astronaut program." |
|`og:type` | Defines content as "article" for social media |
|`og:title` | "Recipe that everyone likes" - title shown when shared |
|`og:description` | Full recipe description for social media previews |

## HTML Elements Used
| Element | Purpose | Example in Project |
|---------|---------|-------------------|
| `<h1>` | Main header | "Astronaut Application" |
| `<p>` | Paragraphs | "Complete the following fields:" |
| `<form>` | Form container | Contains all input fields and submit |
| `<fieldset>` | Groups related form elements | 7 sections: Anagraphic, Personal Info, Physical Characteristics, etc. |
| `<legend>` | Caption for fieldset | "ANAGRAPHIC:", "PERSONAL INFORMATION:", etc. |
| `<label>` | Labels for input fields | "Name:", "Age:", "Email:", etc. |
| `<input>` | Various input types | text, number, radio, color, email, tel, checkbox, file |
| `<select>` | Dropdown menu | Eye color selection |
| `<option>` | Dropdown options | Brown eyes, Blue eyes, Green eyes, Grey eyes |
| `<textarea>` | Multi-line text input | Biography field (6 rows - 100 cols) |
| `<button>` | Form buttons | Submit and Reset buttons |
| `<div>` | Division | Line breaks between checkboxes |
| `<b>` | Bold text | Fieldset legend labels |

## Key Attributes Used:
| Attribute | Purpose | Example |  
|-----------|---------|---------|
| `action` | Form submission URL | SheetDB API endpoint and Webhook option |
| `method` | HTTP method for submission | "POST" |
| `target` | Where to open response | "_blank" (new tab) |
| `name` | Field identifier for data | "user-name", "gender", "qualifications[]", etc. |
| `id` | Unique element identifier | "name", "age", "email", etc. |
| `for` | Associates label with input | Links label to input field |
| `type` | Input field type | text, number, email, radio, checkbox, etc. |
| `required` | Makes field mandatory | Applied to name, surname, age, mission, etc. |
| `placeholder` | Hint text inside input | "Insert your name...", "Insert your email..." |
| `min`/`max` | Numeric constraints | Age >= 18, Body weight <= 100kg |
| `maxlength` | Character limit | Telephone (10), Biography (255) |
| `value` | Default*submitted value | Radio button values ("man", "woman", "other") |
| `checked` | Pre-selected option | "Man" radio button default |
| `disabled` | Non-selected option | Eye color placeholder option |
| `selected` | Pre-selected dropdown option | Eye color placeholder |
|  `hidden` | Hides option from dropdown | Eye color placeholder |
| `accept` | File type restriction | ".pdf" for curriculum upload |
| `rows`/`cols` | Textarea dimensions | 6 rows x 100 columns for biography |
| `enctype` | Form encoding type | "multipart/form-data" |

## Technologies Used
* **HTML5** - Document structure and form elements
* **CSS3** - External stylesheet for custom styling
* **SheetDB API** - Backend data storage in Google Sheets
* **Form validation** - HTML5 built-in validation attributes

## Browser support
This HTML supports all modern browsers:  
✅ Chrome  
✅ Microsoft Edge  
✅ Firefox  
✅ Opera  
✅ Safari on iPhone and iPad  
✅ Chrome on Android 

## Resources
- [MDN Web Docs - HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [W3Schools - HTML Forms](https://www.w3schools.com/html/html_forms.asp)
- [W3Schools - HTML Input Types](https://www.w3schools.com/html/html_form_input_types.asp)
- [SheetDB Documentation](https://docs.sheetdb.io/) - API integration guide
- [HTML Validator](https://validator.w3.org/) - Check your HTML code
- [HTML Form Elements Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#forms) - Complete form elements guide

**_Made by Gaia Giachero_**
