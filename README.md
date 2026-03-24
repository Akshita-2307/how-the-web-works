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

Applied font styling and color properties to improve typography and visual structure of the portfolio webpage.
