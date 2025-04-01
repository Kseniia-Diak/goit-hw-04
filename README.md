### Project Overview

This project is part of the **GoIT Fullstack Development Course**. The goal is to enhance the previous project by adding styles for geometry (width, margins, paddings, and borders) and positioning content using Flexbox.

### Acceptance Criteria

#### Project Structure

- The project root contains an `images` folder with all necessary images.
- The project root contains a `css` folder with stylesheets.
- All styles are written in a single `styles.css` file located in the `css` folder.
- File names contain only lowercase English letters and words, without capital letters, spaces, or transliterations.
- The source code is formatted using **Prettier**.
- All images and textual content match the layout design.
- A style normalizer (`modern-normalize`) is connected on all HTML pages.
- The code follows the provided guidelines.

#### Styling Guidelines

- Global style resets are allowed for `<h1>...<h6>`, `<p>`, and `<ul>` elements.
- Elements do not have margin values that "break out" of their parent containers.
- The leftmost or rightmost margins in single-row collections of elements are removed (if present).
- Margins are used to create spacing between adjacent elements.
- Padding is used to create space between a parent element and its child elements.
- Margin and padding sizes strictly follow the design layout.
- A common `.container` class is created for centering and limiting content width.
- The `.container` width matches the design layout (1200px).
- The `.container` wraps content inside the header, footer, and sections.
- Flexbox is used only where necessary, such as in the header, navigation, section lists, and other horizontal layouts.
- The final dimensions of blocks in the browser match the design layout.
- Elements do not have fixed heights; their height is determined by their content.
- The header has a bottom border (visible when zooming in).
- Sections are stacked vertically without external margins.
- All sections use a common `.section` class with `94px` padding at the top and bottom.
- Grid layout techniques described in course materials are applied.
- Portfolio cards have a border at the bottom only.

## Live Demo

The project is deployed via **GitHub Pages**. You can view the live version [here](https://kseniia-diak.github.io/goit-hw-03/)

### Technologies Used

- HTML5
- CSS3 (Flexbox)
- Prettier (for code formatting)
- GitHub Pages (for deployment)

## Author

**Kseniia Diak** [GitHub Profile](https://github.com/Kseniia-Diak/)
