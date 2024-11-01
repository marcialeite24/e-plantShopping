# Conference Event Planner

Course: [Developing Front-End Apps with React](https://www.coursera.org/learn/developing-frontend-apps-with-react?specialization=ibm-full-stack-cloud-developer) - [IBM Full Stack Software Developer](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer)

## Table of contents

- [Overview](#overview)
- [Project Features](#project-features)
- [Live Demo](#live-demo)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)


## Overview
This project is a Shopping Cart Application created for an online plant shop, Paradise Nursery. Developed as part of the IBM Full Stack Software Developer course on Cognitive Class, this app allows users to browse various plant categories, view detailed information for each plant, and add items to a shopping cart with real-time updates. The project consolidates skills in React component development, state management with React Hooks and Redux, and dynamic UI rendering.

## Project Features
- **Landing Page:** Displays a welcoming landing page with a button linking to the product listing page.
- **Navigation Bar:** Provides quick access to the landing page, product listings, and shopping cart.
- **Product Listing Page:** Shows a list of plants, including their images, descriptions, and an "Add to Cart" button.
- **Plant Categories:** Displays plants by categories (e.g., Aromatic Plants and Medicinal Plants), organizing items for easy browsing.
- **Shopping Cart:** A dedicated cart page listing items added by the user, with features including:
    - Plant thumbnail, description, and cost per unit.
    - Dynamic cost calculation for quantities of each plant type.
    - Increase, decrease, and delete buttons to manage quantities.
    - "Continue Shopping" and "Checkout" buttons for enhanced user flow.
- **Cart Icon with Quantity Badge:** Updates in real-time to show the number of items in the cart.

## Live Demo
Check out the live demo of the website [here](https://marcialeite24.github.io/e-plantShopping/).

## Technologies Used
- **React.js:** To create interactive user interfaces with component-based architecture.
- **Redux Toolkit:** For efficient state management and managing global state changes.
- **JavaScript (ES6+):** For dynamic functionalities and logic.
- **HTML5 & CSS3:** For the application's structure and styling.
- **GitHub Pages:** For deployment, making the app accessible via a public URL.

## Getting Started
- Clone the repository (it was necessary to clone the repository of this course to start this project):

``` bash 
git clone git clone https://github.com/ibm-developer-skills-network/e-plantShopping.git
cd event-planner-landing-page
```

- Install dependencies:

``` bash
npm install
```

- Start the development server:

``` bash
npm run preview
```
- Open http://localhost:4173 to view the landing page in your browser.

## Acknowledgements
This project was developed as part of the IBM Full Stack Software Developer Specialization on Coursera. It provided valuable insights into creating component-based front-end applications using React.

## License
This project is open-source and available under the Apache 2.0 License.