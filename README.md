# Sandeep Laxman Patil - HSE Portfolio Website

This package is a complete static website. It does not require a database, paid software, or a build process.

## Open the website

1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox, or Safari.
3. The training catalogue, sample dashboards, inspection checklists, legal register, downloads, theme switch, and contact email form work in the browser.

For the most reliable local preview, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish online

### Netlify Drop

1. Go to Netlify Drop.
2. Drag the entire unzipped website folder into the upload area.
3. Netlify will provide a public website address.

### GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this package.
3. In repository Settings > Pages, select the main branch and root folder.
4. Save and use the published address.

### Any web hosting provider

Upload `index.html` and the complete `assets` folder to the public website directory, usually named `public_html`, `www`, or `htdocs`.

## Main files

- `index.html` - website structure and page content
- `assets/css/styles.css` - design, responsive layout, dark theme, and print styling
- `assets/js/data.js` - editable profile, employment, training, inspection, legal, qualification, and document data
- `assets/js/app.js` - interactions, filters, dashboards, checklists, exports, and contact form
- `assets/cv/Sandeep_Laxman_Patil_CV.pdf` - downloadable CV

## Edit the content

Most editable website content is in `assets/js/data.js`. Open the file in a text editor, change the text inside quotation marks, and save.

Contact information also appears in `index.html` for SEO and quick-contact sections. Search for the old phone number or email and replace every occurrence when updating.

## Important notes

- Dashboard figures, legal status, inspections, and training records are clearly marked as sample demonstration data.
- The website does not publish passport, driving-licence, residential-address, or other sensitive identification information.
- The legal register is a portfolio example, not legal advice. Verify obligations against current legislation, factory approvals, MPCB consent conditions, and the exact site profile before operational use.
- The static contact form opens the visitor's default email application. To receive submissions directly through the website, connect a service such as Netlify Forms, Formspree, or your own secure backend.
- The website uses no external chart or font libraries, so it remains fast and works without third-party dependencies.

## Replace the CV

Replace `assets/cv/Sandeep_Laxman_Patil_CV.pdf` with a new PDF using the same filename. The existing website links will continue to work.
