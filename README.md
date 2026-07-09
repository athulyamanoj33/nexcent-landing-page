# Nexcent Landing Page

A responsive landing page built for a UI Developer take-home assignment. The goal was to recreate a given Figma design as closely as possible using HTML, CSS, and Bootstrap, while keeping the code clean and easy to follow.

Figma reference: https://www.figma.com/proto/7xXNdeCrRNEizqbACKjUIj/Minimal-Landing-Page-Design-%7C-Website-Home-Page-Design-%7C-Agency-Website-UI-Design--Community-?node-id=5-573&p=f&t=IKrLDdY6wCQhR7TR-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=5%3A573

## What's included

- Navigation bar (responsive, collapses on mobile)
- Hero section
- Clients strip
- Community management section
- Feature highlights
- Stats section
- Testimonials
- Blog preview
- CTA section
- Footer

Tested across desktop, tablet, and mobile breakpoints.

## Built with

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons

## Folder structure

├── assets/
│   ├── images/
│   └── icons/
│
├── index.html
├── style.css
└── README.md

## Running it locally

```bash
git clone <repository-url>
cd <project-folder>
```

Then just open `index.html` in a browser — no build step needed.

## Notes on the approach

I mainly relied on Bootstrap's grid for the responsive layout instead of writing custom media queries everywhere, since it kept things consistent across breakpoints. Tried to keep the HTML semantic and split the CSS logically so it's not a pain to go back and tweak sections later.

Most of the effort went into matching spacing, typography, and section proportions to the Figma file rather than just getting something "close enough."

## Author

Athulya N
