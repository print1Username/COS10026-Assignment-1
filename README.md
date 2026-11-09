# COS10026 Assignment 1

[English](README.md) | [简体中文](README.zh-CN.md)

## Overview

This repository contains a static cactus and succulent store website created for the COS10026 Computing Technology Inquiry Project. It presents cactus-related products, customer registration and order forms, team profiles, and examples of HTML5 and CSS enhancements.

The website is built with HTML5 and CSS. It does not require a package manager, build process, database, or server-side application.

## Main Pages

- `index.html` - home page with an autoplaying background video and featured products
- `product.html` - product category overview
- `succulent.html` - cactus and succulent catalogue
- `pots.html` - plant pot catalogue
- `tools.html` - gardening tool catalogue
- `others.html` - soil, fertilizer, decorations, and other planting products
- `registration.html` - customer registration form
- `order.html` - product selection and order form
- `aboutus.html` - group overview
- `profile_1.html` to `profile_5.html` - individual group member profiles
- `enhancement.html` - demonstrations of hover effects, dropdown menus, HTML5 video, and figures

The registration and order forms submit through the user's email client using `mailto:`. This project has no backend or database, so submitted information is not stored by the website.

## Project Structure

```text
COS10026-Assignment-1/
|-- index.html              # Website entry point
|-- product.html            # Product category overview
|-- succulent.html          # Cactus catalogue
|-- pots.html               # Pot catalogue
|-- tools.html              # Gardening tool catalogue
|-- others.html             # Other product catalogue
|-- registration.html       # Customer registration form
|-- order.html              # Order form
|-- aboutus.html            # Group overview
|-- profile_1.html ...      # Group member profiles
|-- enhancement.html        # HTML5 and CSS enhancements
|-- style.css               # Shared styles for all pages
|-- images/                 # Product, profile, logo, and interface images
|-- videos/
|   `-- video.mp4           # Video used on the home and enhancement pages
|-- README.md               # English documentation
`-- README.zh-CN.md         # Simplified Chinese documentation
```

## Clone the Repository

```bash
git clone https://github.com/print1Username/COS10026-Assignment-1.git
cd COS10026-Assignment-1
```

## Run the Website

### Option 1: Open the file directly

Open `index.html` in a modern web browser. No installation is required.

### Option 2: Start a local web server

If Python 3 is installed, run this command from the project folder:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

To stop the server, press `Ctrl+C` in the terminal.

## Technologies

- HTML5
- CSS3
- Local image and MP4 assets

## Notes

- Keep the existing folder structure because the HTML files use relative paths for `style.css`, `images/`, and `videos/`.
- An internet connection is needed only when opening external links; the main site content uses local files.
- This website was created for educational and non-commercial use.
