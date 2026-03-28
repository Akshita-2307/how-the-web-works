# Web Development Learning Journey

This repository documents a structured journey toward becoming a full-stack web developer. Each section records concepts studied and practiced during daily learning sessions.

---

## Table of Contents

- [Day 1 – How the Web Works](#day-1--how-the-web-works)
- [Day 2 – HTTP, HTTPS, DNS and Status Codes](#day-2--http-https-dns-and-status-codes)
- [Day 3 – Browser Rendering and Developer Tools](#day-3--browser-rendering-and-developer-tools)
- [Day 4 – HTML Basics](#day-4--html-basics)
- [Day 5 – HTML Concepts and Web Performance](#day-5--html-concepts-and-web-performance)
- [Day 6 – HTML Mini Project](#day-6--html-mini-project)
- [Day 7 – Introduction to CSS and Selectors](#day-7--CSS-Application-Methods-and-Selectors)
- [Day 8 – CSS Box Model](#day-8--css-box-model)
- [Day 9 – CSS Fonts, Text Styling, and Colors](#day-9--css-fonts-text-styling-and-colors)
- [Day 10 – CSS Cascade Algorithm and Specificity](#day-10--css-cascade-algorithm-and-specificity)
- [Day 11 – CSS Sizing Units and Display Properties](#day-11--css-sizing-units-and-display-properties)
- [Day 12 – CSS Shadows, Outline, List Styling, and Overflow Properties](#day-12--css-shadows-outline-list-styling-and-overflow-properties)

# Day 1 – How the Web Works

## What is the Internet?

The internet is a global network of computers connected to each other to share information. It allows devices to communicate using standardized protocols.

## Client and Server

- **Client** – The user’s device or browser that requests information.
- **Server** – A powerful computer that stores websites and responds to client requests.

## Role of the Browser

A browser acts as the bridge between the client and the server. It sends requests to the server and displays responses in a user-friendly format.

## What Happens When You Type a URL?

When a user enters a URL in the browser, the browser sends a request to the server. The server processes the request and sends the required data back to the browser. The browser then renders and displays the webpage.

---

# Day 2 – HTTP, HTTPS, DNS and Status Codes

## DNS (Domain Name System)

Every website has a unique technical address called an IP address. Since numerical IP addresses are difficult for humans to remember, domain names such as `google.com` are used. DNS converts these human-readable domain names into their corresponding IP addresses.

## HTTP Protocol

HTTP is responsible for transferring data between the browser and the server. It defines a set of rules that specify how requests are sent and how responses are returned.

## HTTPS

HTTPS protects sensitive information while it is transmitted over the network by encrypting communication between the browser and the server.

## HTTP Status Codes

- **404 Error** – Occurs when the requested resource cannot be found.
- **500 Error** – Indicates that the server encountered an internal error.
- **200 Status Code** – Indicates that the request was successfully processed.

A `200` status code only confirms successful communication and does not guarantee that the website is free of bugs or performance issues.

---

# Day 3 – Browser Rendering and Developer Tools

## What a Browser Does

After receiving HTML from the server, the browser parses the HTML document and constructs the **Document Object Model (DOM)**.

## Browser Rendering Process

The browser processes a webpage in the following steps:

- Parses HTML to construct the DOM
- Applies CSS rules to style elements
- Executes JavaScript
- Renders the final page on the screen

## Developer Tools

Developer Tools allow developers to inspect and debug webpages.

### Elements Tab

Used to inspect HTML structure and debug CSS layout issues.

### Network Tab

Displays all requests made by the browser and helps analyze loading behavior and status codes.

### Application Tab

Allows inspection of cookies, local storage, and session storage.

---

# Day 4 – HTML Basics

HTML provides the basic structure of webpages.

## HTML Tags Practiced

- `<head>` – Contains metadata
- `<body>` – Contains visible page content
- `<title>` – Defines the browser tab title
- `<h1>` – Main heading
- `<p>` – Paragraph text
- `<a>` – Hyperlinks
- `<img>` – Images
- `<ol>`, `<ul>`, `<dl>` – Lists
- `<table>` and `<caption>` – Tabular data

## Practice Work

A personal HTML profile page was created to practice structure, nesting of elements, and the use of lists and tables without CSS or JavaScript.

---

# Day 5 – HTML Concepts and Web Performance

## Core Web Vitals

Core Web Vitals measure user experience performance.

- **LCP (Largest Contentful Paint)** – Measures how long it takes for the largest visible element to load.
- **CLS (Cumulative Layout Shift)** – Measures unexpected layout movement during page load.
- **FID (First Input Delay)** – Measures delay between the user's first interaction and the browser’s response.

## Lighthouse Report

The Lighthouse report is a Google tool used to evaluate webpage performance, accessibility, SEO, and overall user experience.

## HTML Forms

The `<form>` element collects user input using elements such as text fields, checkboxes, and radio buttons.

## Block-Level vs Inline Elements

**Block elements**

- Start on a new line
- Take full width

Examples: `<div>`, `<p>`

**Inline elements**

- Do not start on a new line
- Occupy only necessary width

Example: `<a>`

## ID and Class

- `id` – Unique identifier for a single element
- `class` – Used to group multiple elements

## Media Elements

- `<video>` – Embeds video content
- `<audio>` – Embeds audio content

## Iframe

The `<iframe>` element embeds external webpages or content within the current webpage.

## SVG

SVG (Scalable Vector Graphics) allows the creation of scalable graphics that retain quality when resized.

## Semantic HTML

Semantic elements provide meaningful structure to webpages.

Examples:

- `<header>` – Top section of a webpage
- `<main>` – Primary content area
- `<footer>` – Bottom section of a webpage

## Practice Work

Enhanced the existing HTML profile page by adding a contact form, embedded media (video and audio), an iframe for external content, and an SVG graphic to practice advanced HTML elements.

## Day 6 – HTML Mini Project

Created a personal portfolio landing page using HTML. The page includes semantic structure, navigation links, lists, tables, embedded media, and a contact form to practice combining multiple HTML concepts into a single webpage.

## Day 7 – CSS Application Methods and Selectors

Introduced CSS and explored different methods of applying styles to HTML documents.

### Types of CSS

Practiced three approaches for styling webpages:

- **Inline CSS** – Applied styles directly inside HTML elements using the `style` attribute
- **Internal CSS** – Applied styles using the `<style>` tag within the `<head>` section of the document
- **External CSS** – Applied styles using a separate stylesheet linked to the HTML document with the `<link>` element

### CSS Selectors

Studied commonly used selectors for targeting HTML elements:

- **Element selector** – Targets all elements of a specific type (e.g., `p`)
- **Class selector** – Targets elements sharing the same class name (e.g., `.text`)
- **ID selector** – Targets a uniquely identified element (e.g., `#header`)
- **Child selector** – Targets elements that are direct children of another element (e.g., `div > p`)
- **Descendant selector** – Targets elements located anywhere inside another element (e.g., `div p`)
- **Universal selector** – Targets all elements on the webpage (e.g., `*`)

### Pseudo Selectors

Explored pseudo selectors used to apply styles based on element states and structure:

- `a:link` – Styles unvisited links
- `a:visited` – Styles visited links
- `a:hover` – Styles elements when the mouse pointer moves over them
- `a:active` – Styles elements when they are clicked
- `p:first-child` – Styles the first child element inside a parent element

### Practice Work

Applied inline, internal, and external CSS while styling the portfolio page and experimented with multiple selector types to control element appearance and interaction behavior.

## Day 8 – CSS Box Model

Learned the structure of how spacing and sizing work in CSS using the Box Model.

### CSS Box Model Components
Every HTML element consists of:

- Content → actual text/image inside the element
- Padding → space between content and border
- Border → wraps padding and content
- Margin → outer space between elements

### Width & Height Behavior
- Width and height apply only to the content area by default
- Padding and border increase total element size unless box-sizing is changed

### Margin Collapse
Learned that vertical margins between block elements can collapse into a single margin instead of adding together.

Example:
- If element A has margin-bottom: 20px
- and element B has margin-top: 30px
Final spacing becomes 30px (not 50px)

### box-sizing Property
Studied difference between:

content-box (default):
- width = content only
- padding and border added outside width

border-box:
- width includes content + padding + border
- makes layout easier and predictable

## Day 9 – CSS Fonts, Text Styling, and Colors

Explored CSS font properties, text formatting techniques, and different methods of applying colors to improve the readability and visual presentation of webpages.

### Font Properties

Studied commonly used font-related properties:

- **font-family** – Defines the typeface applied to text
- **fallback fonts** – Backup fonts used when the primary font is unavailable
- **font-style** – Controls italic or normal text appearance
- **font-weight** – Adjusts thickness of text characters
- **font-size** – Defines the size of text

Also explored methods for importing custom fonts into webpages.

### Text Formatting Properties

Practiced styling and structuring text using:

- **line-height** – Controls vertical spacing between lines of text
- **letter-spacing** – Adjusts spacing between characters
- **text-decoration** – Adds underline, overline, or line-through effects
- **text-decoration-color** – Changes decoration color
- **text-decoration-style** – Applies styles such as solid, dotted, or dashed decorations
- **text-decoration-thickness** – Controls thickness of text decoration lines
- **text-transform** – Converts text to uppercase, lowercase, or capitalized format
- **text-indent** – Adds indentation to the first line of text
- **text-align** – Controls horizontal alignment of text

Explored text overflow handling techniques:

- **text-overflow** – Controls how hidden overflow text is displayed
- **word-break** – Controls word wrapping behavior inside containers

### CSS Color Systems

Studied different ways of applying colors in CSS:

- **Color keywords** (e.g., red, blue, green)
- **Hex color codes** (e.g., #ff5733)
- **RGB values** (e.g., rgb(255, 0, 0))
- **RGBA values** (adds transparency using alpha channel)
- **HSL values** (hue, saturation, lightness)
- **HSLA values** (HSL with transparency)

## Day 10 – CSS Cascade Algorithm and Specificity

Studied how CSS determines which styles are applied when multiple rules target the same element. Explored the cascade algorithm, rule priority order, and specificity calculation.

### CSS Cascade Algorithm

The cascade algorithm defines how browsers resolve conflicts between multiple CSS rules applied to the same element. The final style is determined based on:

- Origin of styles
- Importance of declarations
- Selector specificity
- Position in order of appearance

### Order of Appearance

When selectors have equal specificity and importance, the rule written later in the stylesheet overrides earlier rules.

### Origin of Styles

CSS rules can come from different sources:

- Browser default styles
- External stylesheets
- Internal stylesheets
- Inline styles

Inline styles generally have higher priority than internal and external styles.

### Importance

Declarations marked with `!important` override normal CSS rules regardless of specificity (except when another `!important` rule with higher specificity exists).


### Specificity

Specificity determines which selector has higher priority when multiple selectors target the same element.

Specificity priority order:

- Inline styles
- ID selectors
- Class selectors, attribute selectors, pseudo-classes
- Element selectors and pseudo-elements

### Specificity Calculation

Specificity is calculated by counting selector types in the following order:

- Inline styles → highest priority
- Number of ID selectors
- Number of class selectors and pseudo-classes
- Number of element selectors

Selectors with higher specificity override selectors with lower specificity when conflicts occur.

## Day 11 – CSS Sizing Units and Display Properties

Explored CSS sizing units and display properties used to control element dimensions and layout behavior across different screen sizes.

### CSS Sizing Units

Studied commonly used relative and viewport-based sizing units:

- **vw (viewport width)** – Sets size relative to the width of the viewport
- **vh (viewport height)** – Sets size relative to the height of the viewport
- **vmin** – Uses the smaller value between viewport width and height
- **vmax** – Uses the larger value between viewport width and height
- **rem** – Sets size relative to the root (`html`) font size
- **em** – Sets size relative to the font size of the parent element

These units help create responsive layouts that adapt to different screen dimensions.

### Minimum and Maximum Size Properties

- **min-width** – Defines the minimum allowed width of an element
- **max-width** – Defines the maximum allowed width of an element
- **min-height** – Defines the minimum allowed height of an element
- **max-height** – Defines the maximum allowed height of an element

### Display Properties

Explored different display behaviors that control how elements appear and interact in layouts:

- **display: inline** – Elements remain in the same line and take only required width
- **display: inline-block** – Elements stay inline but allow width and height adjustments
- **display: none** – Completely removes the element from the layout
- **visibility: hidden** – Hides the element while preserving its layout space

### Flexbox Layout

- **display: flex** – Enables flexible block-level layout
- **display: inline-flex** – Enables flexible inline layout behavior

Flexbox allows efficient alignment, spacing, and distribution of elements inside containers.

### Grid Layout

Explored grid-based layout using:

- **display: grid** – Enables two-dimensional layout control using rows and columns

Grid layout helps organize complex page structures with better control over positioning and spacing.

## Day 12 – CSS Shadows, Outline, List Styling, and Overflow Properties

Explored visual styling techniques using box shadow and text shadow, learned the outline property and its differences from borders, practiced styling lists, and studied overflow behavior for handling content that exceeds container boundaries.

### Box Shadow

Studied the `box-shadow` property used to apply shadow effects around elements.

Common attributes include:

- **Horizontal offset (H-offset)** – Controls shadow position along the horizontal axis
- **Vertical offset (V-offset)** – Controls shadow position along the vertical axis
- **Blur radius** – Controls the softness of the shadow
- **Spread radius** – Controls the size expansion of the shadow
- **Color** – Defines the shadow color
- **Inset** – Creates an inner shadow inside the element
- **Outset** – Creates a shadow outside the element (default behavior)

Box shadows help improve visual depth and element separation in layouts.

### Text Shadow

Studied the `text-shadow` property used to apply shadow effects to text.

Attributes include:

- **Horizontal offset**
- **Vertical offset**
- **Blur radius**
- **Color**

Text shadows improve readability and visual emphasis in headings and highlighted text.

### Outline Property

Learned the `outline` property used to draw a line around elements without affecting layout spacing.

Outline attributes include:

- **outline-width**
- **outline-style**
- **outline-color**

### Difference Between Border and Outline

Compared borders and outlines based on layout behavior:

- **Border** occupies space and affects element dimensions
- **Outline** does not affect layout size
- Outline appears outside the border area
- Outline is commonly used for accessibility focus indicators

### List Styling

Explored different techniques for customizing list appearance:

- Removing default markers using `list-style: none`
- Changing marker styles using `list-style-type`
- Replacing markers with custom emojis
- Replacing markers with images using `list-style-image`
- Adjusting marker placement using `list-style-position`

These techniques help improve visual presentation of navigation menus and structured content.

### Overflow Properties

Studied how CSS handles content that exceeds container boundaries.

Common overflow values include:

- **overflow: scroll** – Adds scrollbars regardless of content size
- **overflow: auto** – Adds scrollbars only when needed
- **overflow: clip** – Clips overflowing content without scrollbars
- **overflow-x** – Controls horizontal overflow behavior
- **overflow-y** – Controls vertical overflow behavior

### Text Overflow Handling

Learned techniques for managing text that exceeds container width:

- **white-space: nowrap** – Prevents text from wrapping onto the next line
- **text-overflow: ellipsis** – Displays truncated text with an ellipsis



