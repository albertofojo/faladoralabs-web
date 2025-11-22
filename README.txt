# Faladora Labs S.L. - Corporate Website

Corporate website for Faladora Labs S.L., an engineering company applied to intangible heritage. One-page design with smooth navigation between sections and multi-language support (Galician, Spanish, English).

## About Faladora Labs

Faladora Labs S.L. is a technological innovation laboratory based in Galicia. Our mission is to bridge the gap between centuries-old craftsmanship and digital precision, developing physical devices (hardware) and digital ecosystems (software) that bring objective metrics to subjective artistic processes.

### Services

- **Sensory Digitalization**: Development of non-invasive sensor technology for capturing physical variables in complex acoustic environments
- **Data Analysis and UX**: Translation of acoustic 'Big Data' into intuitive visual interfaces
- **Technological Consulting**: Advisory services for manufacturers and institutions on IoT solutions integration in the cultural and musical sector

## Project Structure

```
faladoralabs-web/
├── index.html          # Main page (Galician)
├── es/                 # Spanish version
│   ├── index.html
│   ├── cookies.html
│   ├── legal.html
│   └── privacidade.html
├── en/                 # English version
│   ├── index.html
│   ├── cookies.html
│   ├── legal.html
│   └── privacidade.html
├── assets/
│   ├── css/           # Compiled styles
│   ├── js/            # JavaScript scripts
│   ├── sass/          # SASS/SCSS sources
│   └── webfonts/      # Font Awesome fonts
├── images/            # Images and logos
└── README.txt         # This file
```

## Requirements

- Python 3.x (for local server)
- Modern web browser

## How to Run Locally

### Option 1: Python HTTP Server (Recommended)

1. Open a terminal in the project directory:
```bash
cd faladoralabs-web
```

2. Run the HTTP server:
```bash
python -m http.server 8000
```

3. Open your browser and visit:
```
http://localhost:8000
```

### Option 2: Custom Port

If port 8000 is already in use:
```bash
python -m http.server 8080
```

And visit `http://localhost:8080`

### Option 3: Access from Local Network

To access from other devices on your local network:
```bash
python -m http.server 8000 --bind 0.0.0.0
```

### Stop the Server

Press `Ctrl + C` in the terminal to stop the server.

## Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Styles and animations
- **SASS/SCSS**: CSS preprocessor
- **JavaScript**: Interactivity and navigation
- **jQuery**: JavaScript library
- **Font Awesome**: Iconography
- **Responsive Design**: Adaptive design for different devices

## Features

- ✅ One-page design with smooth navigation
- ✅ Multi-language support (GAL, ES, EN)
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Sidebar navigation with hamburger menu
- ✅ Sections: Home, About Us, R&D+i Cultural, Portfolio, Contact
- ✅ Legal pages: Cookies, Legal, Privacy

## Development

### SASS Styles

Styles are organized in SASS within `assets/sass/`:
- `base/`: Reset, typography, base page
- `components/`: Reusable components
- `layout/`: Section-specific layouts
- `libs/`: Variables, mixins, functions

To compile SASS to CSS, you'll need to have SASS installed:
```bash
sass assets/sass/main.scss assets/css/main.css
```

## Credits

### Base Template
- **Hyperspace** by HTML5 UP (html5up.net)
- License: CCA 3.0 (html5up.net/license)

### Libraries and Resources
- **jQuery**: jquery.com
- **Font Awesome**: fontawesome.io
- **Scrollex**: github.com/ajlkn/jquery.scrollex
- **Responsive Tools**: github.com/ajlkn/responsive-tools

### Images
- Demo images: Unsplash (unsplash.com)

## License

This project uses the Hyperspace template from HTML5 UP under CCA 3.0 license.

---

**Faladora Labs S.L.**
Engineering applied to intangible heritage
