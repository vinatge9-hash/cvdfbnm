# Niyantri Coffee – Website Build

This repository contains a 5-page premium coffeehouse website built with Tailwind CSS (no external CSS files required). Pages:

- index.html (Home)
- cart.html
- checkout.html
- about.html
- contact.html

Branding defaults used:
- Name: Niyantri Coffee
- Tagline: Elevate your coffee ritual
- Vibe: Cozy, warm, refined premium coffeehouse look
- Location context: Hyderabad, Telangana, India

Image placeholders follow the required format: src="https://pixabay.com/get/g592079adc1cdcc5f2d105400bd80eed0e090c1546e2d7bc7ad0e547a158c110e45cb5a97e62908183231981e26058fa784da7ba1e798ac2c93aad1df0970cd2a_640.jpg".

Accessibility and semantics:
- Semantic HTML5 elements used (header, nav, main, section, footer).
- Proper headings (single h1 per page).
- Alt text for all images.
- Meta descriptions added.

Interactions and animations:
- All interactive elements (links, buttons, cards) include Tailwind transition utilities (transition-all duration-300 etc.).
- Body fades in on load.
- Sections reveal on scroll via IntersectionObserver.
- Buttons and links have hover effects, with a squishy/scale animation on hover where applicable.

Notes:
- Tailwind CSS is loaded via CDN for this build.
- Hero uses a full-viewport background image with a dark overlay to ensure contrast.
- The header is transparent over the hero and becomes solid as the user scrolls.
- The mobile navigation uses a hamburger toggle with a playful animation.
