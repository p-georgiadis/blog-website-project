# Cyberpunk Blog - Frontend Web Development Nanodegree Project

Welcome to the **Cyberpunk Blog**, a project created as part of the **Udacity Frontend Web Development Nanodegree**. This project showcases advanced HTML and CSS skills, including Grid and Flexbox layouts, accessibility considerations, and custom styling. The blog explores the futuristic world of cyberpunk culture, with topics ranging from cybernetic enhancements to virtual realities.

This project is fully hosted on **GitHub Pages** and was developed under the **OneTen scholarship**.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Accessibility](#accessibility)
- [Installation](#installation)
- [Live Demo](#live-demo)
- [License](#license)

## Project Overview

The **Cyberpunk Blog** is a responsive website designed to provide users with an engaging experience through vivid imagery, neon colors, and a cyberpunk theme. It was created as part of Udacity’s Frontend Web Development Nanodegree, adhering to all project rubric requirements. The site uses a clean and organized directory structure with HTML, CSS, and an external design system.

### Key Features:
- **Responsive Design**: Ensures the site looks great on mobile, tablet, and desktop devices.
- **Grid & Flexbox Layouts**: Utilizes CSS Grid and Flexbox to create an intuitive layout for the blog homepage and blog post pages.
- **Custom Design System**: Separates design elements from the structure, utilizing a cohesive design system in a separate CSS file.
- **Accessibility**: Follows WCAG 2.0 guidelines to ensure proper color contrast and accessibility for all users.
- **Modular Components**: Each part of the website is modular, including reusable components like buttons, cards, and the navigation bar.

## Features

### Blog Homepage
- **Hero Section**: A hero image and CTA button, welcoming users to the futuristic blog.
- **Blog Post Previews**: A grid layout showcasing three blog post cards with images, descriptions, and "Read More" links.
- **Subscribe Section**: A subscription form in the footer allowing users to stay updated with the latest posts.

### Blog Post Page
- **Blog Content**: Detailed blog posts with large headers, images, and related content.
- **Author Info**: Section showcasing the author’s details, including social media links.
- **Related Posts**: Links to other blog posts, presented at the bottom of each blog post page.

## Technologies Used
- **HTML5**: For semantic and accessible structure.
- **CSS3**: For styling, including a custom design system.
  - **Flexbox & CSS Grid**: Used for creating the responsive layout.
- **Google Fonts**: For modern typography.
- **FontAwesome**: For social media icons in the footer.
- **GitHub Pages**: For deployment.

## Project Structure

The project follows a clean directory structure:
├── index.html            # Blog homepage
├── blog/
│   ├── post.html         # Example blog post page
│   └── 404.html          # 404 error page
├── assets/               # Static assets such as images and logos
├── styles/
│   ├── main.css          # Main CSS file that imports other CSS files
│   ├── design-system.css # The custom design system (colors, typography, etc.)
│   ├── home.css          # Styles specific to the homepage
│   ├── blog.css          # Styles specific to the blog post pages
│   ├── about.css         # Styles specific to the about page
└── README.md             # This README file

### Design System
A custom design system is implemented in `design-system.css` to ensure consistency across the site, including:
- **Colors**: Bright neon colors with high contrast.
- **Typography**: Futuristic fonts (Orbitron for headers and Roboto Mono for paragraphs).
- **Reusable Components**: Buttons, cards, forms, etc.

## Accessibility

This project adheres to WCAG 2.0 accessibility guidelines. Key features include:
- **High Contrast Ratios**: Colors were adjusted to meet the minimum contrast requirements for readability.
- **ARIA Attributes**: Ensures the website is accessible for screen readers.
- **Semantic HTML**: Proper use of semantic HTML tags like `<header>`, `<nav>`, `<main>`, and `<footer>` for better structure and accessibility.

## Installation

To run the project locally:
1. Clone this repository:
   ```bash
   git clone https://github.com/p-georgiadis/cyberpunk-blog.git
   ```
2. Open the `index.html` file in your browser to view the homepage.

### Requirements:
- A modern web browser that supports HTML5 and CSS3.

## Live Demo

You can view the project live at: [Cyberpunk Blog](https://p-georgiadis.github.io/blog-website-project/index.html)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

### Key Sections:
- **Project Overview**: Provides a general overview of the project and its purpose.
- **Features**: Describes the main features of the blog.
- **Technologies Used**: Lists the technologies used in building the project.
- **Project Structure**: Shows the directory structure to guide contributors or reviewers.
- **Accessibility**: Emphasizes the accessibility features.
- **Installation**: Gives steps for setting up the project locally.
- **Live Demo**: Provides a link to the deployed site on GitHub Pages.
- **License**: Specifies the licensing for the project.

## Authorship

This project was created by **Panagiotis Georgiadis** as part of the **Udacity Frontend Web Development Nanodegree**, fully sponsored through the **OneTen scholarship**. The project demonstrates skills in HTML, CSS (Grid & Flexbox layouts), and responsive web design.

### Connect with Me:
- [GitHub](https://github.com/p-georgiadis)
- [LinkedIn](https://linkedin.com/in/p-georgiadis)

Feel free to connect with me if you have any questions or feedback regarding this project!
