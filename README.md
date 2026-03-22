# iliya.com

Personal website. Hosted on GitHub Pages.

## Adding a new writing

1. Drop your PDF into the `writings/` folder
2. Open `writing.html` and add a new entry before `</main>`:

```html
<a class="writing-card" href="writings/your-file.pdf" target="_blank" rel="noopener">
  <h3>Your Title</h3>
</a>
```

3. Push to GitHub:

```bash
git add .
git commit -m "add new writing: Your Title"
git push
```

Live within a couple minutes.

## Deploying changes

Any change to the site (text edits, new PDFs, CSS tweaks):

```bash
git add .
git commit -m "describe your change"
git push
```

## File structure

```
├── index.html          # Home page
├── projects.html       # Projects
├── experience.html     # Experience, education, publications
├── writing.html        # Writing index (links to PDFs)
├── styles.css          # Shared stylesheet
├── writings/           # Drop PDFs here
│   └── 1_Hello_World.pdf
└── README.md
```
