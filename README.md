English | [Leer en español](README.es.md)

# RIFF Magazine

A responsive music magazine website built with HTML, CSS, and Bootstrap.

Developed as part of the Front-End Development program at EBAC to practice responsive layouts and Bootstrap components.

The website includes a homepage with featured content and article previews, plus a contact page.

**Live demo:** [RIFF Magazine](https://riffmagazine.web.app/)

## Features

- Responsive navigation with a sidebar menu on smaller screens.
- A carousel for featured content.
- Article preview cards organized with Bootstrap's grid system.
- An accordion with information about the magazine.
- A subscription modal with an email field.
- A contact page with name, email, and message fields.
- Shared navigation and footer across both pages.

## Technologies

- **HTML5:** page structure and content.
- **CSS:** custom image styling.
- **Bootstrap 5.3.3:** responsive layout, navigation, cards, forms, and utility classes.
- **Bootstrap JavaScript bundle:** carousel, accordion, modal, and offcanvas menu interactions.

Bootstrap's styles and JavaScript are loaded through the jsDelivr CDN.

## Getting started

### Requirements

- A web browser.
- Git installed to clone the repository.
- An internet connection to load Bootstrap from the CDN.

### Installation and usage

1. Clone the repository:

```bash
git clone https://github.com/Y4E1-png/RIFF-Magazine.git
cd RIFF-Magazine
```

2. Open `index.html` in your browser.

No dependency installation or build step is required.

## Usage example

The website interface is in Spanish.

1. Open the homepage.
2. Use the carousel controls to switch between featured slides.
3. Browse the article preview cards.
4. Expand the questions in the **Sobre RIFF** accordion.
5. Click **Suscríbete** to open the subscription modal.
6. Click **Contacto** to visit the contact page.
7. Resize the browser window to explore the responsive navigation.

## Current scope

- Article cards contain preview content. Their **Leer más** links are placeholders.
- The contact form and subscription modal demonstrate the interface only. They are not connected to a backend or email service.
- The homepage references six images inside an `img/` folder. These files are currently missing from the repository, so their images will not appear when running a fresh clone.

## Project structure

```text
RIFF-Magazine/
├── index.html     Homepage
├── contacto.html  Contact page
└── .gitignore     Files excluded from version control
```

Custom CSS is included in the `<style>` element of `index.html`. Bootstrap provides the remaining styles and interactive components.


## Author

Developed by **Yael Aguilar** as part of the Front-End Development program at EBAC.

[GitHub profile](https://github.com/Y4E1-png)
