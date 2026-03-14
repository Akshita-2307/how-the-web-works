# Web Development Learning Journey

This repository documents a structured journey toward becoming a full-stack web developer. Each section records concepts studied and practiced during daily learning sessions.

---

## Table of Contents

- [Day 1 – How the Web Works](#day-1--how-the-web-works)
- [Day 2 – HTTP, HTTPS, DNS and Status Codes](#day-2--http-https-dns-and-status-codes)
- [Day 3 – Browser Rendering and Developer Tools](#day-3--browser-rendering-and-developer-tools)
- [Day 4 – HTML Fundamentals](#day-4--html-basics)
- [Day 5 – HTML Concepts and Web Performance](#day-5--html-concepts-and-web-performance)

---

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
