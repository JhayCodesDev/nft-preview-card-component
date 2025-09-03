# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The challenge focuses on building a responsive card layout with hover states for interactive elements. It was a great opportunity to practice HTML structure, CSS positioning, hover effects, and responsive design techniques.

Users should be able to:

View the optimal layout depending on their device's screen size

See hover states for interactive elements

Through this project, I was able to:

Reinforce my understanding of flexbox and positioning for layout.

Learn how to create a hover overlay effect with an icon that stays perfectly inside the image container.

Improve my workflow by structuring code for both desktop and mobile views.

This project helped me strengthen my ability to translate a design mockup into a functional component, while paying attention to spacing, typography, and accessibility.

### Screenshot
![screenshot for desktop](./Screenshot%202025-09-03%20at%2020-49-29%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2020-50-05%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)
![screenshot for active state](./Screenshot%202025-09-03%20at%2021-09-10%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)

### Links
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/nft-preview-card-component/)

## My process
1. Setup

Downloaded the starter files and extracted them into a new project folder named nft-preview-card-component-main.

Reviewed the provided documents (style-guide.md, README-template.md, README.md, and design mockups) to understand the requirements.

2. Structure

Built the HTML structure with semantic tags to ensure accessibility and readability.

Wrapped the main content inside a .container for layout control.

Added an .image-container to hold the NFT image, and placed an .eye-viewer overlay with an eye icon inside it for the hover effect.

Created sub-sections for the NFT title, description, price, time remaining, and creator information.

Included an attribution section at the bottom for credits.

3. Styling

Linked the custom Google Font specified in the style guide.

Added base styles for the body, headings, and container.

Styled each section in order:

NFT image with hover overlay (.image-container and .eye-viewer)

NFT title and description

Price and time left (using flexbox for side-by-side alignment)

Creator information (profile image and name)

Added hover states for interactive elements such as the NFT title and creator name.

Styled the attribution at the bottom of the page.

4. Responsiveness

Used a desktop-first approach, designing for larger screens first and then applying media queries for smaller devices.

For mobile optimization, applied the following:

@media screen and (max-width: 400px) {
  .container {
    width: 80%;
  }
}


This ensured the component scaled properly on devices down to 320px while maintaining spacing and readability.

5. Finishing Up

Cleaned up the CSS by grouping selectors logically.

Tested the component across different screen sizes to confirm that the hover effects, overlay, and responsiveness worked as intended.

Wrote the README and prepared the project for deployment.
### Built with

- Semantic HTML5 markup

- CSS custom properties for consistent styling

- Flexbox for layout and alignment

- CSS hover effects & overlay for interactivity

- Mobile-first responsive design with media queries

- External Google Fonts for typography


## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.
