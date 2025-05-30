# Responsive Sample Website

A simple, clean, and mobile-friendly responsive website layout built with HTML and CSS.  
This project demonstrates the use of CSS Flexbox and media queries to create a flexible layout that adapts seamlessly to different screen sizes, including desktops, tablets, and mobile devices.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Responsive Design Details](#responsive-design-details)
- [Testing Responsiveness](#testing-responsiveness)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Contact](#contact)

---

## Project Overview

This project is a basic website layout with a header navigation menu, main content area, sidebar, and footer. It uses CSS Flexbox for the desktop layout and CSS media queries to adjust the layout for mobile devices (screens 768px wide or less). An image is included in the content section to demonstrate responsive image handling.

---

## Features

- Responsive two-column layout on desktop (content + sidebar).
- Navigation menu that switches from horizontal to vertical on smaller screens.
- Responsive images that scale within their containers.
- Clean and simple design with accessible navigation.
- Uses CSS media queries to adapt layout and font sizes for mobile devices.

---

## Technologies Used

- HTML5
- CSS3 (Flexbox, Media Queries)
- No JavaScript required for basic responsiveness.

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari).
- Optional: VS Code or any text editor for editing code.

### Installation

1. Clone or download this repository to your local machine.

2. Open the project folder in your preferred code editor.

3. Open `index.html` in a web browser to view the website.

---

## Project Structure


---

## How It Works

- The `.container` uses Flexbox to create a two-column layout on wider screens.
- The navigation menu is a horizontal list on desktop.
- When the viewport width is 768px or less:
  - The `.container` switches to a vertical stack.
  - The navigation menu stacks vertically.
  - Font sizes can be adjusted (optional).
- Images inside `.content` scale responsively with `max-width: 100%` and `height: auto`.

---

## Responsive Design Details

The CSS media query used:


This ensures the website adapts smoothly to mobile devices by stacking elements vertically and improving readability.

---

## Testing Responsiveness

You can test the responsive behavior by:

- Opening the website in Google Chrome.
- Pressing `F12` to open Developer Tools.
- Clicking the **Toggle device toolbar** icon (or pressing `Ctrl+Shift+M`).
- Selecting different device presets or resizing the viewport manually.
- Observing how the layout and navigation menu adapt to smaller screen sizes.

---

## Future Improvements

- Add a collapsible hamburger menu for better mobile navigation.
- Improve accessibility with ARIA roles and keyboard navigation.
- Enhance styling with CSS Grid for more complex layouts.
- Add animations or transitions for menu interactions.
- Include more content sections and multimedia.

---

## License

This project is open-source and available under the MIT License.

---

## Contact

For questions or feedback, please contact:

- Jaividhyarthi V  
- Email: jaividhyarthivivekanand@gmail.com  
- GitHub: [Jaividhyarthi](https://github.com/Jaividhyarthi)

---

Thank you for checking out this Responsive Sample Website project!

