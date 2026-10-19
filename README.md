# Personal Portfolio Website

A beginner-friendly personal portfolio built with HTML and CSS for the Basic HTML & CSS course. It introduces the developer, describes current skills, showcases practice projects, links to GitHub, and provides a contact form connected to Formspree endpoint `https://formspree.io/f/xgaoqdeo` (test after deployment).

## Features

- Single-page sections: Home, About, Projects, GitHub, and Contact
- Customized copy about moving from transportation/dispatch operations into front-end development
- Original local SVG illustrations in the `assets/` folder
- Custom navy, blue, mint, and coral color palette
- Navigation hover underline, project-card hover states, button transitions, and subtle entrance animations
- Responsive layout for desktop, tablet, and mobile
- Accessible labels, alternative text, keyboard focus states, skip link, and reduced-motion support
- HTML contact form that can be connected to Formspree

## Open locally

1. Extract this project folder.
2. Open it in Visual Studio Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. Scroll through each section, test the navigation links, hover over the navigation and project cards, and resize the browser.

No build step is required. Google Fonts are requested online, but a system-font fallback is included.

## Personalize before submission

Search in `index.html` for and replace:

- Personalized for Harjeet Kaur
- GitHub profile: https://github.com/HarjeetAOL
- Each placeholder repository path with the actual URL of your course projects
- The introductory and About copy with the wording that best reflects your experience and goals

The project thumbnail cards are samples. Change the text and descriptions to match the work you actually complete and link them to working repositories or live demos only after those destinations exist.

## Connect the contact form

The form currently uses this placeholder:

```html
<form action="https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID" method="POST">
```

1. Create a form in your Formspree account and set the recipient email.
2. Copy your form endpoint from the Formspree dashboard.
3. Replace the placeholder URL in the `action` attribute with your actual endpoint.
4. Save and submit a test message. Confirm the submission in your Formspree dashboard and email.

Until the endpoint is replaced, the contact form is a visual/form-structure example and will not deliver to your inbox.

## Images

The included SVG artwork was made for this project and is stored locally, so the layouts do not depend on image hotlinks. If the assignment requires a personal photograph, replace `assets/hero-workspace.svg` in the hero with a cropped photograph of yourself or another image you have permission to use. Free photo options are available from [Pexels](https://www.pexels.com/), [Pixabay](https://pixabay.com/), and [StockSnap](https://stocksnap.io/). Read the applicable licence for the image you choose; Pexels says its photos and videos may be used for free, with attribution not required but appreciated: https://www.pexels.com/legal-pages/license/.

## Suggested repository description

> A personal front-end development portfolio built with HTML and CSS, including an introduction, current skills, course projects, GitHub links, and a contact form.

See `PUBLISHING-GUIDE.md` for GitHub Pages and custom-domain/hosting options.

## Push and publish

See `PUSH-TO-GITHUB.md` for steps to upload this folder to your Portfolio repository and enable GitHub Pages.


## GitHub

- GitHub profile: https://github.com/HarjeetAOL
- Portfolio repository: https://github.com/HarjeetAOL/Portfolio


## Assignment checklist

- Personalized Home, About, GitHub, Projects, and Contact content.
- Customized typography, colour palette, and hover interactions.
- Responsive layout and in-page navigation.
- Contact form configured with Formspree; test submissions from the live site.
