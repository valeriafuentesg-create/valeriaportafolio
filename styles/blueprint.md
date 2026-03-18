# Project Blueprint

## Overview

This project is a personal portfolio website for Valeria, a UX/UI designer. The design is clean, modern, and visually showcases her work and personality. It is a single-page layout built with semantic HTML5 and styled with modern CSS (Flexbox/Grid).

## Design and Style

*   **Typography**: Poppins (from Google Fonts), with a range of weights (400, 500, 600, 700, 900).
*   **Color Palette**:
    *   Primary Text: `#333` (Dark Gray)
    *   Headings: `#000` (Black)
    *   Header Text & Icons: `#e53935` (Red)
    *   Background: `#ffffff` (White)
    *   Link: `#2979ff` (Blue)
*   **Layout**:
    *   The main content grid vertically centers the text and image.
    *   The "Latest Work" section is a full-width section with a centered title and a two-column grid for projects.
*   **Imagery**:
    *   The main hero image has rounded corners.
    *   Work thumbnails fill their containers, which adapt to the image aspect ratio.

## Features

*   **Header**:
    *   Main navigation menu.
    *   Social media links.
*   **Side Navigation**:
    *   Vertical text links.
*   **Main Content**:
    *   Hero image and introductory text, now vertically centered.
*   **Latest Work**:
    *   A grid of recent projects in two columns.
    *   "view all" link.
*   **Footer**:
    *   Copyright information.

## Current Plan

The main content has been vertically aligned.

*   **CSS**: In `.content-grid`, the `align-items` property was changed to `center` to vertically center the image and the text section next to it.
