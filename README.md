# Museum of Candy

A responsive landing page inspired by a whimsical candy museum experience. Built with HTML, CSS, Bootstrap, and jQuery, this project demonstrates modern front-end development techniques including responsive layouts, custom styling, smooth navigation effects, and mobile-friendly design.

---

# Overview

Museum of Candy is a visually engaging single-page website that showcases a fictional candy museum through colorful imagery, responsive content sections, and elegant typography.

The project was created to practice:

* Bootstrap grid layouts
* Responsive web design
* Custom CSS styling
* Navigation behavior with JavaScript/jQuery
* Modern UI design principles

---

# Features

## Responsive Design

* Mobile-first layout
* Fully responsive Bootstrap grid system
* Adaptive typography for different screen sizes
* Optimized image scaling

## Interactive Navigation

* Fixed navigation bar
* Mobile hamburger menu
* Dynamic navbar background on scroll
* Smooth visual transitions

## Custom Styling

* Custom color palette inspired by candy themes
* Google Fonts integration
* Elegant typography
* Section spacing and visual hierarchy

## Visual Content

* Large hero section
* Alternating content layouts
* Responsive images
* Decorative candy-themed graphics

---

# Technologies Used

* HTML5
* CSS3
* Bootstrap 4.1.3
* JavaScript
* jQuery
* Google Fonts (Nunito)

---

# Project Structure

```text
Museum-of-Candy/
│
├── index.html
├── app.css
│
├── imgs/
│   ├── hand2.png
│   ├── milk.png
│   ├── gumball.png
│   ├── sprinkles.png
│   └── lolli_icon.png
│
└── README.md
```

---

# Website Sections

## Navigation Bar

The navigation bar includes:

* Home
* About
* Tickets

Features include:

* Fixed-top positioning
* Responsive collapse menu
* Scroll-based styling changes

---

## Hero Section

The landing section introduces visitors to the Museum of Candy through:

* Large repeating title typography
* Custom color accents
* Featured candy-themed imagery

---

## Content Sections

### Candy & Milk

Introduces the museum concept with supporting imagery and descriptive content.

### Gumball Exhibit

Alternating layout showcasing responsive Bootstrap columns.

### Sprinkles Exhibit

A final content section maintaining visual consistency and responsive design.

---

# JavaScript Functionality

The project includes a jQuery scroll event that dynamically changes the navigation bar background color after the user scrolls beyond the navbar height.

Example:

```javascript
$(document).scroll(function () {
    var $nav = $("#mainNavbar");
    $nav.toggleClass(
        "scrolled",
        $(this).scrollTop() > $nav.height()
    );
});
```

This creates a cleaner user experience by improving navigation visibility during scrolling.

---

# Responsive Features

The site includes responsive behavior such as:

* Hidden hero text on smaller screens
* Mobile navigation menu
* Responsive image scaling
* Adaptive typography sizing
* Bootstrap grid reordering

Media query example:

```css
@media (max-width: 1200px) {
    #headingGroup h1 {
        font-size: 3rem;
    }

    .blurb h2 {
        font-size: 2rem;
    }
}
```

---

# Learning Objectives

This project demonstrates:

* Bootstrap grid systems
* Responsive layouts
* Fixed navigation bars
* CSS transitions
* JavaScript event handling
* DOM manipulation with jQuery
* Mobile-first design principles
* UI/UX fundamentals

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/museum-of-candy.git
```

Navigate to the project folder:

```bash
cd museum-of-candy
```

Open the project:

```text
index.html
```

Or use a local development server:

```bash
npx serve
```

---

# Future Enhancements

Potential improvements include:

* Smooth scrolling navigation
* Animated section transitions
* Interactive gallery
* Ticket reservation form
* Contact page
* Accessibility improvements
* Dark mode support
* CSS animations
* Bootstrap 5 migration
* Removal of jQuery dependency using modern JavaScript

---

# Screenshots

Create a screenshots directory and add project images:

```text
screenshots/
├── homepage.png
├── mobile-view.png
├── navbar-scroll.png
└── exhibits.png
```

Then include them in your README:

```markdown
![Homepage](screenshots/homepage.png)
```

---

# Key Concepts Practiced

* Bootstrap Containers
* Bootstrap Grid System
* Responsive Utilities
* Custom CSS Styling
* Google Fonts Integration
* Navigation Design
* DOM Events
* jQuery Scroll Effects
* CSS Media Queries

---

# License

This project is open source and available under the MIT License.

---

# Author

Created as part of a front-end web development learning journey focused on building responsive, visually appealing user interfaces and gaining practical experience with Bootstrap and JavaScript.
