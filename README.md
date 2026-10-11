# FloatFlow Tech Summit

## Overview
This repository contains a responsive conference web page designed to practice specific CSS layout mechanics without relying on modern layout modules like Flexbox or CSS Grid. The project focuses on traditional structuring, flow manipulation, and positioning techniques to build a clean, multi-column user interface.

## CSS Concepts & Layout Mechanics Explored
This project was intentionally built to master the following foundational CSS properties:

*   **Float & Clearfix (via Overflow):** Utilizing `float: left` for the speaker cards to create a multi-column grid, and applying `overflow: auto` to the parent container to properly clear the floats and maintain document flow.
*   **Inline-Block Formatting:** Structuring the header navigation menu using `display: inline-block` to align list items horizontally while retaining block-level box model properties (such as margins and padding).
*   **Absolute & Relative Positioning:** Applying `position: absolute` relative to a `position: relative` parent to perfectly place overlapping UI elements, such as the "Keynote Speaker" badge on the cards.
*   **Semantic Table Layouts:** Designing a clean, readable event schedule using structural HTML `<table>` tags enhanced with CSS border-collapse and hover states.

## Technologies Used
*   **HTML5:** Semantic page structuring.
*   **CSS3:** Custom styling, float-based grid system, typography, and box-shadows.
*   **FontAwesome:** Integrated via CDN for lightweight vector icons.
*   **Google Fonts:** Utilizing 'Roboto Condensed' for typography.

## How to Run
Simply clone this repository and open `index.html` in your preferred web browser. No local development server or build tools are required.
