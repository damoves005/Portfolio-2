# Portfolio Website

A modern portfolio website built with HTML, CSS, and JavaScript, featuring particle effects, dynamic text, and a responsive design.

## Features

- Responsive design
- Dark/Light theme toggle
- Particle effects background
- Dynamic text animations
- Project carousel
- Portfolio showcase with expandable project cards

## Installation & Setup

1. Clone the repository

```bash
git clone [your-repository-url]
```

2. Install dependencies

```bash
npm install bootstrap parcel validator
```

3. Start the development server

```bash
npx parcel index.html
```

The website will be available at `http://localhost:1234`

## Development

The project uses Parcel as a bundler and includes the following dependencies:

- Bootstrap: For responsive design components
- Validator: For input validation
- Parcel: For bundling and development server

## Project Structure

```
├── css/
│   ├── reset.css
│   └── styles.css
├── js/
│   ├── main.js
│   └── particles.js
├── modules/
│   ├── activeHoverReplace.js
│   ├── carousel.js
│   ├── dynamicText.js
│   ├── headerShrink.js
│   ├── particleConfig.js
│   ├── scheduler.js
│   ├── screenshot.js
│   ├── themeToggle.js
│   └── toggleNavMenu.js
└── img/
    └── [image assets]
```

## Git Ignore

Make sure to add these directories to your `.gitignore`:

```
node_modules/
dist/
.parcel-cache/
```
