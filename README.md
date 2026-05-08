# Laundry Services - Mobile Hamburger Menu

## Problem Statement
Develop a Hamburger Menu for the mobile view of the Laundry Web App using only HTML and CSS.

## Description
This project implements a responsive landing page for a laundry service. As part of the mobile responsiveness, the standard navigation links are hidden on smaller screens (768px and below) and replaced with a hamburger menu icon. Clicking the icon reveals a side menu sliding out from the right side of the screen.

## Key Features & CSS Logic
* **Responsive Design:** The layout adapts to desktop, tablet, and mobile views using CSS Media Queries.
* **Pure CSS Interactive Menu:** The hamburger menu functions entirely without JavaScript. 
* **Focus State Tracking:** To achieve the click-to-open functionality with only CSS, the hamburger icon is wrapped in a `<button>` element. We use the `:focus` pseudo-class on this button.
* **Sibling Combinator:** When the button is focused (`.hamburger-btn:focus`), it targets the adjacent side menu using the general sibling combinator (`~`) to change its display property from `none` to `flex`, making the menu visible.

## Technologies Used
* HTML5
* CSS3 (Flexbox, Media Queries, Pseudo-classes)
* **No Bootstrap or JavaScript was used in this project.**

## How to Run the Project
1. Extract the downloaded `.zip` folder.
2. Ensure `index.html`, `style.css` (if external), and the `img` folder are in the same directory.
3. Double-click the `index.html` file to open it in your default web browser.
4. To test the mobile menu, either view the page on a mobile device