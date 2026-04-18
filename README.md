# Personal Web Portfolio

A modern, responsive portfolio website built with HTML, CSS, JavaScript, Bootstrap, and Sass.

## 🚀 Features

- **Responsive Design** - Mobile-first approach with Bootstrap
- **Modern Styling** - Custom Sass styling with animations
- **Interactive Navigation** - Smooth scrolling and active link highlighting
- **Skills Section** - Showcase your expertise
- **Portfolio Projects** - Display your work with descriptions and links
- **Contact Form** - Get in touch with visitors
- **Animations** - Smooth scrolling and element animations

## 📋 Sections

1. **Navigation Bar** - Sticky navbar with smooth scrolling
2. **Hero Section** - Eye-catching introduction
3. **About Me** - Personal profile and background
4. **Skills** - Technical expertise displayed in cards
5. **Projects** - Portfolio showcasing your work
6. **Contact** - Contact form and social media links
7. **Footer** - Copyright information

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3 & Sass** - Styling with SCSS preprocessing
- **Bootstrap 5** - Responsive framework
- **JavaScript (ES6+)** - Interactivity and animations
- **Font Awesome** - Icon library

## ⚙️ Setup Instructions

### 1. Install Node.js and npm

If you haven't already, download and install [Node.js](https://nodejs.org/) which includes npm.

### 2. Install Dependencies

Open a terminal in your project folder and run:

```bash
npm install
```

This will install Bootstrap and Sass.

### 3. Compile Sass

To watch for changes in your Sass files and automatically compile to CSS:

```bash
npm run sass
```

This command will:

- Watch the `style/` folder for changes
- Compile `style/style.scss` to `dist/css/style.css`
- Automatically update when you save changes

## 📁 Project Structure

```
project-folder/
├── dist/
│   └── css/
│       └── style.css       # Compiled CSS (auto-generated)
├── img                     # images
├── node_modules            # Bootstrap framework(libraryies)
├── style/
│   └── style.scss          # Sass source file
├── gitignore               #
├── app.js                  # JavaScript functionality
├── index.html              # Main HTML file
├── package-lock.json       #
├── package.json            # Dependencies configuration
└── README.md               # This file
```

## 📱 Responsive Breakpoints

The portfolio is designed to work on:

- Mobile devices (< 576px)
- Tablets (576px - 768px)
- Desktops (> 768px)

## 🚀 Deployment

You can deploy this portfolio to:

- **GitHub Pages** - Free hosting for static sites
- **Netlify** - Easy deployment with drag-and-drop
- **Vercel** - Fast and reliable hosting
- **Any web hosting service** - Upload files via FTP

## 📝 License

This project is open source and available for personal use.
