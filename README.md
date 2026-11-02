# RCCG Lighthouse Parish — Digital Platform

A modern, responsive digital platform for RCCG The Lighthouse Parish, built with HTML, CSS, and JavaScript.

**Live Site:** https://desmondazubuike.github.io/RCCG-Lighthouse-Parish/

## Overview

A digital platform designed to make church information and engagement more accessible. It brings together service information, announcements, an interactive Bible verse generator, and a prayer request form with email submission.

## Features

- Responsive layout for desktop and mobile devices.
- Sticky navigation with a mobile hamburger menu.
- Auto-scrolling announcement ticker.
- Editable and hideable special service announcements.
- Interactive Bible verse generator.
- Prayer request form with inline validation and email submission through Formspree.
- Semantic HTML and accessibility features.

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Formspree
- Google Fonts

## Project Structure

```text
RCCG-Lighthouse-Parish/
├── index.html
├── CSS/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── RCCG Light House Logo.jpg
└── README.md
```

## Running Locally

No build tools or additional dependencies are required.

1. Clone or download this repository.
2. Open `index.html` in a web browser.

## Updating Church Announcements

The announcement ticker and Special Service section can be updated directly in `index.html`. Look for the `EDIT:` comments marking the relevant sections.

These sections can also be hidden when there are no current announcements.

## Form Handling

The prayer request form uses Formspree to process and deliver submissions. The project does not currently use a custom backend or database.
