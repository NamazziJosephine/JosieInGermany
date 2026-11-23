# JosieInGermany
Here we are creating and deploying a website.
# Student Life in Germany

A small, responsive multi-page website with practical basics for international and new students in Germany: registering an address, finding housing, and handling money and work.

**Live site:** https://delightful-monstera-da682a.netlify.app/

Github pages: https://namazzijosephine.github.io/JosieInGermany/

---

## About the project

This is a student web-design project built to practise **HTML, CSS, Bootstrap, responsive design, the grid system and CDNs**, then deploying a finished site to the web.

The content is a general starter guide, not official advice. Rules about visas, insurance and work change and depend on the person, so details should always be confirmed with the university, the immigration office or an official source such as the [DAAD](https://www.daad.de/en/) or [Make it in Germany](https://www.make-it-in-germany.com/en/).

## Pages

| Page | File | What it covers |
|---|---|---|
| Home | `index.html` | Overview, quick checklist, topic cards and a typical order for the first weeks |
| Arriving | `arriving.html` | Address registration (Anmeldung), residence permit, enrolling at university |
| Housing | `housing.html` | Student residence, shared flat or own flat, comparison table, rental scam warnings |
| Money & Work | `money.html` | Health insurance, bank account, transport tickets, working as a student |

## Built with

- **HTML5** for structure
- **CSS3** with CSS variables for the colour theme (`css/style.css`)
- **[Bootstrap 5.3.3](https://getbootstrap.com/)** loaded from the **jsDelivr CDN**, so nothing needs to be installed
- A little **JavaScript** from Bootstrap's bundle (responsive menu and accordion)
- **[Netlify](https://www.netlify.com/)** for hosting

## Concepts practised

- **Responsive design:** the viewport meta tag, mobile-first layout and Bootstrap breakpoints
- **Grid system:** `container` → `row` → `col-*`, with a 12-unit layout (for example `col-12 col-sm-6 col-lg-4` gives 1, 2 and 3 cards per row on phone, tablet and desktop)
- **Components:** navbar with a hamburger menu, cards, accordion, table, alerts
- **CDN usage:** linking a framework by URL instead of downloading it
- **Custom CSS:** overriding Bootstrap defaults, hover transitions, shared stylesheet across pages

## Project structure

```
student-life-germany/
├── index.html
├── arriving.html
├── housing.html
├── money.html
├── css/
│   └── style.css
├── images/            (add your own photos here)
└── README.md
```

## Run it locally

1. Download or clone this repository.
2. Open the folder in [Visual Studio Code](https://code.visualstudio.com/).
3. Install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.
4. An internet connection is needed, because Bootstrap loads from the CDN.

You can also double-click `index.html` to open it in a browser.

## Deployment

The site is a static folder, so it needs no build step.

1. Log in to Netlify and choose **Add new site → Deploy manually**.
2. Drag the project folder (the one that directly contains `index.html`) onto the upload area.
3. Netlify publishes the site and gives it a `.netlify.app` address.

To update the site later, open the site's **Deploys** tab and drag the updated folder in again. Alternatively, connect this GitHub repository to Netlify (build command empty, publish directory `/`) so every push redeploys automatically.

## Content and credits

- All text and the design were written for this project. No text, images or branding were copied from another website. The layout idea was inspired by a reference site studied during the course exercise.
- Images: add the photographer and source here, for example *"Photo by NAME on Unsplash"*.
- Bootstrap is released under the MIT licence.

## Author

**NAMAZZI JOSEPHINE**
Health Informatics, TH Deggendorf
GitHub: [@YOUR-USERNAME](https://github.com/NamazziJosephine)

## Disclaimer

This website is a learning project. It provides general information only and is not legal, medical or immigration advice.
