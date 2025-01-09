# Portfolio

# Personal Portfolio Website

This is a personal portfolio website for Oishi Banerjee. The website showcases various sections, including Home, Resume, Projects, and Contact information. The project utilizes HTML, CSS, JavaScript, and AOS (Animate On Scroll) library for animations. A separate projects page displays a carousel of projects using the Slick carousel library.

## Features

- **Responsive Design**: The website is fully responsive and works on all device sizes.
- **Smooth Animations**: Utilizes the AOS (Animate On Scroll) library for smooth scroll animations.
- **Project Carousel**: A dedicated projects page with a carousel to showcase various projects.
- **Font Awesome Icons**: Integrates Font Awesome for social media and other icons.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox)
- Internet connection for fetching libraries and frameworks

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Oishi151/portfolio-website.git
    cd portfolio-website
    ```

2. **Open the Project**:
    Open the `index.html` file in your preferred web browser to view the website.

## File Structure

```plaintext
portfolio-website/
├── index.html
├── projects.html
├── style.css
├── script.js
├── download.png
├── Oishi Banerjee.pdf
└── README.md
```

## Usage

- **Home**: The main landing page with a brief introduction and social media links.
- **Resume**: Clicking on the "Resume" link will open Oishi Banerjee's resume in a new tab.
- **Projects**: The "Projects" link redirects to a page with a carousel of projects.
- **Contact**: The contact section includes an email link and social media profiles (GitHub, LinkedIn).

### Adding Projects to the Carousel

1. **Update `projects.html`**:
    Add or replace the `<div>` elements within the `.project-carousel` for each project you want to display.

    ```html
    <div class="project-carousel">
        <div><img src="path/to/project1.png" alt="Project 1"></div>
        <div><img src="path/to/project2.png" alt="Project 2"></div>
        <div><img src="path/to/project3.png" alt="Project 3"></div>
    </div>
    ```

2. **Modify Image Paths**:
    Replace `path/to/projectX.png` with the actual paths to your project images.

## Dependencies

- **AOS (Animate On Scroll)**: [AOS Documentation](https://michalsnik.github.io/aos/)
- **Font Awesome**: [Font Awesome Documentation](https://fontawesome.com/)
- **Slick Carousel**: [Slick Carousel Documentation](https://kenwheeler.github.io/slick/)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Special thanks to the AOS, Font Awesome, and Slick Carousel teams for their fantastic libraries.

