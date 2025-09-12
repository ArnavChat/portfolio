# Arnav Chaturvedi — Portfolio

**Personal portfolio / GitHub Pages**

Live demo: [https://arnavchat.github.io/portfolio/](https://arnavchat.github.io/portfolio/)

---

## Table of contents

* About
* Live demo
* Contact / Resume
* Projects (what's included)
* Education
* Skills
* Tech stack
* Project structure
* Run locally
* Contributing
* License
* Author / Contact

---

## About

This repository contains the static source files for the personal portfolio website of **Arnav Chaturvedi**. The site showcases a short biography, education details, projects, technical skills, and a link to a resume. It is a dependency-free static site built using plain HTML, CSS and Bootstrap and is hosted on GitHub Pages.

The portfolio is targeted at internship or junior web developer opportunities and highlights front-end work such as the AppVITite restaurant site and an IRCTC homepage clone.

---

## Live demo

Open the live site on GitHub Pages:

`https://arnavchat.github.io/portfolio/`

---

## Contact / Resume

* **Email**: linked on the site (visible on the page header).
* **Resume**: a Google Drive link is provided on the portfolio site (may require Google sign-in to view).

---

## Projects featured on the site

### AppVITite — Restaurant Website

* Small static restaurant demo with menu, catering and FAQ pages.
* Built with HTML, CSS and Bootstrap; designed as a mobile-friendly static demo.
* Live demo: `https://arnavchat.github.io/AppVITite/`

### IRCTC Homepage Clone

* A front-end clone of the IRCTC homepage built using Bootstrap and plain HTML/CSS.
* A useful demonstration of responsive layout and component composition.
* Live demo: `https://arnavchat.github.io/IRCTC-homepage-CSS-Bootstrap/`

(Each project includes a direct link from the portfolio and may also include separate image assets and pages in the project folders.)

---

## Education (as shown on the site)

* **Vellore Institute of Technology (VIT), Vellore** — B.Tech in Computer Science. Reported CGPA: 9.54. Graduation date: Aug 2026.
* **Tagore Public School, Jaipur** — CBSE 12th Grade: 93.4% (Mar 2022)
* **St. Anselm's Sr. Sec. School, Ajmer** — CBSE 10th Grade: 96.8% (Mar 2020)

---

## Skills and coursework

* **Skills:** C/C++, Python, Java, HTML, CSS, JavaScript, Node.js, Express.js, EJS, Git, GitHub
* **Coursework:** Data Structures, Algorithms, Object Oriented Programming

---

## Tech stack

* Static HTML + CSS + Bootstrap
* Hosted on GitHub Pages

---

## Project structure (root)

```
portfolio/
├─ css/            # stylesheets
├─ images/         # profile and project images
├─ index.html      # main portfolio page
├─ README.md       # (this file)
```

(If the repository contains project subfolders like `AppVITite/` or `IRCTC-homepage-CSS-Bootstrap/`, those hold the corresponding project sources.)

---

## Run locally

1. Clone the repository:

```bash
git clone https://github.com/ArnavChat/portfolio.git
cd portfolio
```

2. Quick preview: open `index.html` directly in your browser.

3. Recommended: serve with a local web server for correct relative paths:

```bash
# Python 3
python -m http.server 8000
# open http://localhost:8000
```

4. Make changes, then commit and push:

```bash
git add README.md
git commit -m "Add README"
git push origin master
```

(Replace `master` with `main` if your default branch differs.)

---

## Contributing

The site is intentionally lightweight. Suggested improvements:

* Add improved responsive layout and accessible navigation.
* Replace any placeholder images with higher-resolution originals.
* Add metadata for SEO (title, description, Open Graph).
* Add a contact form or connect "Email Me" to a working mailto or form handler.

To contribute: fork, create a branch, implement changes, and open a pull request.

---

## License

No license is included by default. Add a `LICENSE` file (e.g., MIT) if you wish to open-source the repository.

---

## Author

Portfolio content and code by **Arnav Chaturvedi**.

---

## Notes & TODO

* The site links to a Google Drive resume which may require authentication to view — consider hosting a public PDF in the repo or enabling direct download.
* Consider adding a `projects/` index page that links to each project repo and includes short write-ups and screenshots.
* Optionally add a `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md` for collaborators.

---
