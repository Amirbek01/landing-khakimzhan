# SANA AI Conference
A one-page website for an artificial intelligence conference featuring the event program, speakers, and registration.

## Live Website
`https://Amirbek01.github.io/landing-khakimzhan/`

## Features
- semantic HTML5 structure using `header`, `nav`, `main`, `section`, `article`, and `footer`;
- sections covering the hero area, event information, benefits, program, speakers, registration, and contacts;
- an accessible registration form with name, email, and message fields;

- SEO metadata, responsive viewport settings, and an SVG favicon;
- responsive layout for mobile and desktop screens;
- visible focus states, a skip-to-content link, and support for `prefers-reduced-motion`;
- an original illustration created for the hero section.

## Bootstrap 5

This version of the website uses Bootstrap 5 through the jsDelivr CDN. The navigation is built with the Bootstrap navbar and collapse components. The advantages and speaker sections use the Bootstrap grid and card components.

## Responsive

### Mobile — 375 px

![Mobile layout](/assets/screenshots/375px.png)

### Tablet — 768 px

![Tablet layout](/assets/screenshots/768px.png)

### Desktop — 1280 px

![Desktop layout](/assets/screenshots/1280px.png)

## Why I Used Bootstrap

I used Bootstrap 5 because its grid system makes responsive layouts easier to organize. The `col-12`, `col-md-6`, and `col-lg-4` classes let the same cards use one, two, or three columns depending on the screen width. The navbar component provides a working mobile menu without requiring my own JavaScript. Bootstrap cards also give the content a clear and consistent structure. Bootstrap can sometimes get in the way when a design requires unusual spacing or component styles because it includes default rules. Unlike Tailwind, Bootstrap provides ready-made components instead of relying mainly on utility clas ses. Unlike Sass, it works directly in the browser and does not need a compilation step.

## AI Tools

I used ChatGPT to clarify the Bootstrap requirements, check the responsive structure, and review the HTML and CSS. I reviewed the suggested code and adapted it to the design of my own landing page.

## Author
Khakimzhan Amirbek
