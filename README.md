# Personal Landing Page

A clean, responsive single‑page portfolio site built with **HTML5, CSS3, and vanilla JavaScript**. It showcases projects, a short bio, and contact links—perfect as a lightweight online resume hosted on **GitHub Pages**.

> **Live demo →** https://aanh1009.github.io/tango/

---

## ✨ Highlights

| Feature | Details |
|---------|---------|
| **One‑page design** | Smooth in‑page navigation to *Home*, *About*, *Projects*, *Skills*, *Clients*, and *Contact* sections. |
| **Mobile‑first** | Flexible grid + media queries ensure it looks great on phones, tablets and desktop. |
| **Carousel component** | Lightweight JavaScript slideshow for testimonials/clients logos (see `showSlides()` in *index.html*). |
| **Contact form stub** | Ready‑made HTML form with `name`, `email`, and `message`; hook it up to Formspree, Netlify Forms, or your own backend. |
| **Font Awesome icons** | Easy social‑link icons via CDN. |
| **Zero build tools** | Pure HTML/CSS/JS—clone and deploy, no build step. |

---

## 🏗 Folder structure

```
.
├─ assets/
│  ├─ css/
│  │  └─ style.css          # main stylesheet
│  ├─ js/
│  │  ├─ custom.js          # custom behaviours
│  │  ├─ bootstrap.min.js   # vendor
│  │  ├─ jquery.js          # vendor
│  │  └─ ...
│  └─ img/                  # hero, project thumbs, etc.
├─ index.html               # entry point
└─ README.md                # you are here
```

---

## 🚀 Quick start

1. **Clone** the repo
   ```bash
   git clone https://github.com/aanh1009/personal-landing-page.git
   cd personal-landing-page
   ```
2. **Open** `index.html` in your browser (no server required), or run a tiny dev server—e.g.
   ```bash
   npx serve .      # or python -m http.server 8000
   ```
3. **Deploy** via GitHub Pages:
   * Push to `main` (or `gh-pages`) branch.
   * In repo *Settings → Pages*, select your branch and `/` root.
   * Your site will be live at `https://<username>.github.io/<repo>/`.

---

## 🔧 Customising

* **Colours & fonts** → edit `assets/css/style.css`.
* **Hero text / About section** → lines ~20‑100 in `index.html`.
* **Project cards / clients logos** → update corresponding HTML blocks and images under `assets/img/`.
* **Contact form action** → in `index.html` change `<form id="contact-form">` `action` / method attributes or hook up JS.
* **Analytics / meta tags** → add inside `<head>` of `index.html`.

---

## 📸 Screenshot

> *(Add a screenshot here—press `g i` in GitHub to upload)*

![Screenshot](assets/img/screenshot.png)

---

## 🗺 Roadmap / Ideas

- [ ] Dark‑mode toggle.
- [ ] Convert to a Jekyll/Hugo theme for easier markdown content.
- [ ] Replace jQuery with modern vanilla JS or Alpine.js.
- [ ] Add automated Lighthouse CI check via GitHub Actions.

---

## 🤝 Contributing

1. Fork ➜ create branch ➜ commit changes.
2. Follow the existing code style (2‑space indent, semantic HTML).
3. Open a PR—issues & suggestions welcome!

---

## 📝 License

[MIT](LICENSE)  © 2025 Tuan Anh Ngo

