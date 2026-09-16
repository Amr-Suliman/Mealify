<div align="center">

# Mealify

**A modern, responsive restaurant landing page — built with pure HTML & CSS.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Responsive](https://img.shields.io/badge/Responsive-Design-success?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](#license)

<br>

<!--
  Replace this with a real screenshot of the hero section.
  Recommended size: 1200x675px, save it in /screenshots/banner.png
-->
<img src="./screenshots/banner.png" alt="Mealify banner" width="100%">

</div>

<br>

## About the Project

**Mealify** is a restaurant landing page designed to give visitors a warm, appetizing first impression. It includes a hero section, a chefs showcase, a photo gallery, and a contact section with a map — all wrapped in a clean, editorial layout with a built-in dark / light mode toggle.

The project is fully responsive, with dedicated breakpoints for mobile, tablet, laptop, and desktop screens.

<br>

## Features

| Feature | Description |
|---|---|
| Dark / Light Mode | CSS-only theme switch (no JavaScript) using a checkbox hack + CSS variables |
| Fully Responsive | Custom breakpoints for small mobile, mobile, tablet, laptop, and large screens |
| Chefs Section | Cards with social icons that reveal on hover |
| Photo Gallery | Asymmetric grid layout with hover overlays showing dish info |
| Contact Section | Embedded Google Map + contact form + contact details |
| Hamburger Menu | CSS-only mobile navigation (no JavaScript) |

<br>

## Built With

- **HTML5** — semantic structure
- **CSS3** — custom properties (variables), Flexbox, CSS Grid, animations
- **[Font Awesome](https://fontawesome.com/)** — icons
- **Google Fonts** — *Amatic SC*

<br>

## Screenshots

<!--
  Add your own screenshots inside a /screenshots folder in the repo,
  then update the paths below. PNG or JPG, ~1200px wide looks best.
-->

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./screenshots/home-light.png" alt="Home section - light mode" width="100%"><br>
      <sub><b>Home — Light Mode</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="./screenshots/home-dark.png" alt="Home section - dark mode" width="100%"><br>
      <sub><b>Home — Dark Mode</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./screenshots/chefs.png" alt="Chefs section" width="100%"><br>
      <sub><b>Chefs Section</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="./screenshots/gallery.png" alt="Gallery section" width="100%"><br>
      <sub><b>Gallery Section</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./screenshots/contact.png" alt="Contact section" width="100%"><br>
      <sub><b>Contact Section</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="./screenshots/mobile.png" alt="Mobile view" width="100%"><br>
      <sub><b>Mobile View</b></sub>
    </td>
  </tr>
</table>

<br>

## Project Structure

```
Mealify/
├── CSS/
│   ├── index.css        # Base styles (variables, layout, components)
│   └── media.css        # Responsive breakpoints
├── images/
│   └── images/
│       ├── chefs/        # Chef photos
│       ├── gallery/       # Gallery photos
│       └── favicon.png
├── index.html
└── README.md
```

<br>

## Getting Started

No build tools, no dependencies — just open it in a browser.

```bash
# 1. Clone the repository
git clone https://github.com/Amr-Suliman/Mealify.git

# 2. Move into the project folder
cd Mealify

# 3. Open index.html in your browser
#    (or use a live server for auto-reload while editing)
```

> In VS Code, install the **Live Server** extension, right-click `index.html` → **Open with Live Server**.

<br>

## Responsive Breakpoints

| Breakpoint | Target Devices |
|---|---|
| `≤ 480px` | Small mobile phones |
| `481px – 768px` | Mobile / small tablets |
| `769px – 1024px` | Tablets |
| `1024px – 1200px` | Large tablets / small laptops |
| `1201px – 1440px` | Laptops / desktops |

<br>

## Customization

Colors are controlled through CSS variables in `CSS/index.css`, so re-theming the whole site only takes a few edits:

```css
:root {
    --color-bg: #ffffff;
    --color-text: #000000;
    --color-accent: #ce1212;
    --color-bg-home: #eeeeee;
}
```

<br>

## Roadmap

- [ ] Connect the contact form to a real backend / form service
- [ ] Add a JavaScript-based mobile menu close animation
- [ ] Add real chef and gallery photography
- [ ] Deploy a live demo (GitHub Pages / Netlify / Vercel)

<br>

## Contributing

Contributions are welcome.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<br>

## License

Distributed under the MIT License. Feel free to use this project for learning or as a base for your own restaurant site.

<br>

## Author

**Amr Sulieman**

[![GitHub](https://img.shields.io/badge/GitHub-Amr--Suliman-181717?style=flat&logo=github)](https://github.com/Amr-Suliman)