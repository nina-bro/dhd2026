# Default OER Template DH Erfurt

s. auch https://jupyterbook.org/en/stable/start/your-first-book.html 

## Installation 
`pip install -U jupyter-book`

## new Jupyterbook
auf Git `Use this template`

## Working with Jupyterbook
 Struktur/Gliederung: `_toc.yml`
    - Überschriften werden aus den Headings der Dateien übernommen
    - sonst kann man die Titel mit einem `title`-Feld auch spezifisch angeben

 weitere Einstellungen: `_config.yml`

 Verwendung BibTeX/Zitationen: 
 `pip install docutils==0.20`
 https://jupyterbook.org/en/stable/content/citations.html 
 

 # Building into HTML files
`jupyter-book build .`

Ergebnis im `_build/html`-Ordner, Preview via `index.html`


## Deployment:
s. https://yenchiah.me/jupyter-book-template/docs/home.html#step-5-deploy-the-book-online 

### Installation
`pip install ghp-import`

### Einstellung GitHub Pages
- `gh-pages`-Branch

### vom `main`-Branch
`ghp-import -n -p -f _build/html`
