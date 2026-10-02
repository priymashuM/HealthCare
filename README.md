# Harbor Lane Family Clinic — sample healthcare website

A static, multi-page healthcare clinic website built with plain HTML and CSS (no JavaScript, no build step).

> This is a demo site. Harbor Lane Family Clinic is fictional.

## Pages
- `index.html` — Home: hero with "today at the clinic" panel, services, first-visit steps, testimonial
- `services.html` — Detailed list of services
- `doctors.html` — Clinician profiles
- `contact.html` — Appointment request form, hours, location

## Features
- Responsive down to mobile, with a CSS-only menu toggle
- Accessible: skip link, visible keyboard focus, labelled form fields, reduced-motion support
- Fonts: Bricolage Grotesque (headings) and Atkinson Hyperlegible (body) from Google Fonts

## Structure
```
├── index.html
├── services.html
├── doctors.html
├── contact.html
├── css/
│   └── style.css
└── images/
    └── favicon.svg
```

## Publish with GitHub Pages
1. Create a new repository on GitHub and upload all files (keep the folder structure).
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. Your site will appear at `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Note on the form
The contact form has no backend. To receive submissions, connect it to a service such as Formspree or Netlify Forms by changing the form's `action` attribute.
