Tidal
A study timer that fills up as you focus.

Overview
Tidal is a fictional product created as a UX design case study. 
This repository contains the interactive landing page prototype, 
built to demonstrate modern frontend development principles, accessible design, and responsive layouts without reliance on heavy frameworks.

Assets
Landing Page: tidal-landing-page.html

Features : 
Visual SVG Timer: A visual water-filling timer built with SVG paths and CSS animations, managed by vanilla JavaScript to calculate remaining time without relying on interval ticks alone. 
Accessible Segmented Controls: Custom-styled radio buttons for selecting session lengths (1-minute demo, 25 minutes, 50 minutes) and billing cycles.
Form Validation: A waitlist signup form featuring client-side email validation, dynamic error messaging, and ARIA state management.
Responsive Typography & Spacing: CSS clamp() functions are utilized for fluid typography and dynamic spacing, ensuring optimal display across mobile, tablet, and desktop viewports

UX & Accessibility Principles
This prototype was designed with the following core principles in mind:
Visibility of System Status: The water level, numerical countdown, and textual status message update synchronously. The browser tab title also reflects the remaining time during active sessions.   
Error Prevention: Session length controls are locked while the timer is active or paused to prevent accidental data loss, and the reset function is always available.  
Accessibility: Built with the Atkinson Hyperlegible font for low-vision readers, strict adherence to WCAG contrast ratios (minimum 4.5:1), touch targets of at least 44px, and full keyboard navigation support.   
Motion Preferences: Animations and transitions are halted if the user's system preferences are set to reduce motion utilizing @media (prefers-reduced-motion: reduce). 

Tech Stack
HTML5: Semantic structure including <header>, <main>, <section>, and <details> for the FAQ elements.   
CSS3: Custom properties for design tokens (color palette and typography), flexbox, grid layout, and modular scoping.   
JavaScript: No-dependency script utilizing an Immediately Invoked Function Expression (IIFE) for UI state management (idle, running, paused, done). 

Getting Started : 
Since this project uses vanilla web technologies, no build step or package manager is required.Clone the repository to your local environment.
Open tidal-landing-page.html in any modern web browser to interact with the prototype.   
Reference tidal.png for the finalized logo asset.
