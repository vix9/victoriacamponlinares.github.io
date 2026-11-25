# Academic PhD Website

A responsive, modern academic profile website built with plain HTML, CSS, and JavaScript. It works with GitHub Pages and requires no build tools.

## Files

- `index.html` — page content and structure
- `style.css` — layout, colors, typography, and responsive styles
- `script.js` — mobile navigation and current footer year
- `assets/` — put your CV PDF and any images here

## Personalise it before publishing

Search in `index.html` for the sample text and replace it with your details:

- `asdf` — your name / university
- `asdfas` — your research field
- `your.email@university.edu` — your public contact email
- Sample research projects, publications, education, and links

Update the page title and meta description near the top of `index.html` too.

### Add your CV

Create an `assets` folder and add your PDF as `cv.pdf`. The CV link already points to `assets/cv.pdf`. If you do not want to publish a CV yet, remove the download button from `index.html`.

### Add real publication links

Replace the `href="#"` values in the publications section with the paper, DOI, or preprint URLs. Remove sample publication entries that do not apply.

## Publish with GitHub Pages

1. Sign in at https://github.com.
2. Create a **public** repository named exactly `YOUR-USERNAME.github.io` (replace with your GitHub username).
3. Upload the contents of this folder to the repository's root. Make sure `index.html`, `style.css`, and `script.js` are at the top level, not inside another nested folder.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait a few minutes, then visit `https://YOUR-USERNAME.github.io`.

If you use a repository with a different name, the default address is `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Custom domain (optional)

You can connect a domain such as `yourname.com` in **Settings → Pages → Custom domain**. You must own the domain and configure its DNS records with your registrar. GitHub Pages hosting is free; the custom domain itself usually has an annual cost.

## Notes

- This is a static website. It does not include a database, login system, or server-side form processing.
- The contact email link opens the visitor's email application.
- Google Fonts are loaded online; the site still works if they are unavailable, using fallback fonts.
