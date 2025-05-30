# Developer Portfolio Site

This repository contains a static portfolio website that can be used to showcase projects, skills and contact information. The site is built with plain HTML, CSS and JavaScript and is ideal for hosting through [GitHub Pages](https://pages.github.com/).

## Folder structure

```
css/          Stylesheets for the site
js/           JavaScript files
index.html    Main page of the portfolio
favicon.ico   Website icon
experiment1/  Alternate design 1
experiment2/  Alternate design 2
experiment3/  Alternate design 3
```

The `css` folder contains `styles.css` with all styling rules. The `js` folder contains `main.js` for interactivity. The main HTML entry point is `index.html`.

## Local preview

You can preview the site locally using any simple web server. If you have Python installed, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser to view the site.

Alternatively you can use the "Live Server" extension in editors like VS Code.

## Editing content

Open `index.html` and replace placeholder text (such as project names, descriptions, contact details, etc.) with your own information. Adjust styles in `css/styles.css` and behaviors in `js/main.js` as needed.

### Experimental designs

Alternate versions of the profile are available at `/experiment1`, `/experiment2` and `/experiment3`. Each page features a distinct neon-inspired theme.


## Deployment with GitHub Pages

After pushing your changes to GitHub, enable GitHub Pages in the repository settings. Select the branch you want to publish from (often `main` or `gh-pages`). GitHub will build and host the site, providing a public URL.

