
# Project Blueprint

## Overview

This project is a **responsive, single-page application** built with Astro.js to showcase the developer's portfolio and services. The primary goal is to attract potential clients by presenting a professional and visually appealing online presence in a fluid, one-page layout that works seamlessly across all devices.

## Project Outline

### Style and Design

*   **Typography:** A combination of a bold, modern display font for headings ("Poppins") and a clean sans-serif for body text ("Roboto"). Font sizes are responsive and adapt to different screen sizes.
*   **Color Palette:**
    *   Primary (Yellow): `#FFD700`
    *   Text (Dark): `#2D2D2D`
    *   Background (Light Gray): `#F7F7F7`
    *   White: `#FFFFFF`
    *   WhatsApp Green: `#25D366`
*   **Layout:** A responsive, single-page layout with clear sections for Home, Services, About, and Contact. Smooth scrolling navigation is used to move between sections.
*   **Iconography & Imagery:** Use of modern, simple line icons and a friendly vector illustration on the hero section.
*   **Components:** Service items are styled as cards with a distinct shadow/outline effect.

### Features

A single-page layout containing the following sections:

*   **Hero Section (`#inicio`):** A welcoming hero section with a clear value proposition.
*   **Services Section (`#servicios`):** A detailed list of services offered.
*   **About Section (`#quienes-somos`):** An introduction to the developer and their background.
*   **Contact Section (`#contacto`):** Contact information for potential clients.
*   **Navigation:** A fixed header with smooth-scrolling links. It transforms into a hamburger menu on mobile devices.
*   **Footer:** Contains contact information.
*   **Floating WhatsApp Button:** A fixed button on the right side of the screen to allow users to easily initiate a conversation.

## Current Task: Make the Site Responsive

### Plan

1.  **Update `blueprint.md`:** Reflect the goal of making the application fully responsive.
2.  **Implement Hamburger Menu:** Modify `Layout.astro` to include the HTML, CSS, and JavaScript for a mobile-friendly hamburger navigation menu.
3.  **Adjust Typography and Spacing:** Add media queries in `index.astro` and `Layout.astro` to adjust font sizes, padding, and margins for smaller screens, ensuring content is readable and well-proportioned.
