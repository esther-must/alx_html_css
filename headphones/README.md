# Headphones Web Page

## Overview
This repository contains the code for a responsive headphones webpage design. The project replicates a given Figma design while ensuring a smooth user experience across different screen sizes, including desktop and mobile views. The design adheres to strict styling and interactivity requirements, ensuring pixel-perfect implementation.

## Features
- **Responsive Design:** Automatically adjusts layout and styling for screens 480px wide or less.
- **Hover Effects:**
  - Links change color to `#FF6565` on hover or active.
  - Buttons adjust opacity to `0.9` on hover or active.
- **Content Centering:** Content is centered on the page with a maximum width of 1000px.

## Technologies Used
- HTML5
- CSS3
- Figma (for design reference)

## Prerequisites
1. **Figma Account:**
   - Create an account on [Figma](https://www.figma.com/).
   - Open the provided Figma project and duplicate it to your drafts for full access to the design details.

2. **Fonts:**
   - Ensure the following fonts are installed on your system:
     - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
     - [Spin Cycle OT](https://www.dafont.com/spin-cycle.font)

3. **Code Editor:**
   - Use any code editor (e.g., Visual Studio Code, Sublime Text) to modify the code.

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/esther-must/alx_html_css.git
   ```
2. Navigate to the project directory:
   ```bash
   cd alx_html_css/headphones
   ```
3. Open the files in your preferred browser or editor.

## Folder Structure
```
headphones/
|-- index.html       # Main HTML file
|-- style.css        # CSS file for styling
|-- README.md        # Documentation file
|-- images/          # Folder containing design assets
```

## Design Notes
- **Rounding Values:** Some design values in Figma are in float (e.g., `12.5px`). You can round these values to the nearest whole number for simplicity.
- **Interactions:**
  - **Links:** On hover or active, links should change their color to `#FF6565`.
  - **Buttons:** On hover or active, buttons should have an opacity of `0.9`.

## Responsiveness
- The webpage transitions to the mobile version when the screen width is `480px` or less.
- CSS media queries are used to adjust layouts, font sizes, and spacing for optimal display on smaller screens.

## Deployment
1. Open the `index.html` file in a browser to view the project locally.
2. Deploy the project to any static hosting service (e.g., GitHub Pages, Netlify) for online access.

## Contributing
Contributions are welcome! To contribute:
1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add your message here'
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## Author
Developed by Esther Ajayi as part of the ALX Software Engineering program.