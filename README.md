# Masthan Basha Shaik — Portfolio

Personal developer portfolio built as a single self-contained HTML file. No frameworks, no build tools, no dependencies — just HTML, CSS, and vanilla JavaScript.

Live at: **[your-deployed-url-here]**

---

## What's Inside

All content, styles, scripts, profile photo, and resume are embedded directly in one `index.html` file. Dropping it anywhere — a browser, a server, Netlify — works instantly with nothing else required.

---

## Sections

| Section | Content |
|---|---|
| Hero | Name, animated typewriter role, stats, profile photo, social links |
| About | Background, current focus, achievements, location |
| Skills | Frontend, Backend, Databases, Tools, Languages, CS Fundamentals |
| Projects | VectorShift AI Pipeline Builder (featured) + 4 other projects |
| Education | B.Tech CSE at RGUKT RK Valley, Pre-University course |
| Achievements | Awards, certifications, competitive programming profiles |
| Contact | Info panel + message form wired to Formspree |

---

## Features

- **Profile photo** — embedded as base64, no external image file needed
- **Resume download** — PDF embedded as base64, downloads on click from any of the four resume buttons
- **Contact form** — validates all fields, submits to Formspree, delivers messages directly to Gmail
- **Custom cursor** — dot with a lagging ring that scales on hover
- **Typewriter** — cycles through five roles with a blinking caret
- **Scroll animations** — every section fades up on enter using IntersectionObserver
- **Active nav** — highlights the current section as you scroll
- **Fully responsive** — single-column layout on mobile

---

## Activating the Contact Form

The form works out of the box as a mailto fallback. To receive messages directly in Gmail without opening the user's email client:

1. Go to [formspree.io](https://formspree.io) and sign up free
2. Create a new form — copy the endpoint ID (e.g. `xabcdefg`)
3. Open `index.html` and find this line near the bottom:
   ```js
   const FORMSPREE = "https://formspree.io/f/YOUR_FORM_ID";
   ```
4. Replace `YOUR_FORM_ID` with your actual ID and save

Every submission will arrive directly in your inbox.

---

## Deploying

**Netlify Drop** (fastest — 10 seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `index.html`
3. Get a live URL immediately

**GitHub Pages**
```bash
git init
git add index.html
git commit -m "init: portfolio"
git branch -M main
git remote add origin https://github.com/Masthan-Basha/portfolio_masthanbasha.git
git push -u origin main
```
Then go to repo Settings → Pages → deploy from `main` branch.

---

## Tech

Pure HTML, CSS, and vanilla JavaScript. No React, no bundler, no npm. The only external resource is Google Fonts loaded via a `<link>` tag (Space Mono + Outfit).

---

## Author

**Masthan Basha Shaik** — Full-Stack Developer  
B.Tech CSE, RGUKT RK Valley (Expected May 2027)

[GitHub](https://github.com/Masthan-Basha) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/masthan-basha-0316432b2) &nbsp;·&nbsp; [Email](mailto:masthanbasha758@gmail.com)
