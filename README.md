# Rida Shah — Personal Portfolio (Lab 3: HTML Advanced)

CS344 Web Engineering — Lab 3: HTML Advanced - Personal Portfolio II

## About
A multi-page personal portfolio for Rida Shah, BS Software Engineering (Junior Year),
SEECS, NUST Islamabad. Built with plain HTML5 and CSS3 — no JavaScript, no CSS frameworks.

## Pages
- `index.html` — Home / introduction
- `skills.html` — Programming languages, tools, and areas of interest
- `hobbies.html` — Hobbies and interests
- `gallery.html` — Photo gallery (float + clear layout)
- `contact.html` — Contact details

## Folder structure
```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── profile.jpg
│   ├── gallery-1.jpg
│   ├── gallery-2.jpg
│   ├── gallery-3.jpg
│   ├── gallery-4.jpg
│   └── gallery-5.jpg
└── README.md
```

## Styling notes
- All CSS lives in a single external stylesheet: `css/style.css`, linked from every page.
- The navigation bar, the home page hero layout, and the image gallery are all
  arranged using CSS `float`, with `clear` (via a clearfix) used to contain floated
  children and fix layout issues.
- The site is responsive: floats are dropped on small screens via a media query.

## Live site
Deployed with GitHub Pages: `https://<your-username>.github.io/portfolio/`

## Repository
`https://github.com/<your-username>/portfolio`
