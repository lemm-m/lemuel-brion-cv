# Lemuel Brion — Personal CV

## Student information

- **Complete name:** Lemuel Brion
- **Year level:** 4th year
- **Set/Section:** 4G
- **Subject:** IT 415 – APPLICATION DEVELOPMENT AND EMERGING TECHNOLOGIES
- **School:** Davao del Norte State College
- **Course:** Bachelor of Science in Information Technology

## About this project

A responsive personal Curriculum Vitae webpage featuring my profile, education, skills, and contact information. Created for the first GitHub repository and personal CV webpage assignment.

## Files

- `index.html` — the webpage content and semantic HTML structure.
- `style.css` — colors, typography, spacing, responsive layout, and print styles.
- `README.md` — student information and project documentation.

- `assets/lemuel-brion.jpg` — your original supplied photo.
- `vendor/bootstrap.min.css` — Bootstrap 5.3.8, included for offline use.
- `vendor/LICENSE` — Bootstrap MIT license.

## Easy editing

Edit text and Bootstrap classes in `index.html`. Change colors and typography in `style.css`. Replace `assets/lemuel-brion.jpg` to change your photo. Leave the vendor files unchanged. Keep the whole folder together when uploading to GitHub.

Bootstrap reference: https://getbootstrap.com/docs/5.3/getting-started/introduction/

## Run locally

Open `index.html` in a web browser. No internet connection, installation, or build command is needed. Bootstrap and the photo are included locally. To edit, open this folder in Visual Studio Code.

## Technologies

HTML5, CSS3, and Bootstrap 5.3.8 (local CSS). JavaScript is not needed for the static components used here. Python and Figma are personal skills, not project dependencies.

## Understanding the code

- `<header>` contains the initials and navigation.
- `<main>` contains the profile, education, skills, and contact sections.
- Each navigation link uses an `href` such as `#education` to jump to a matching section `id`.
- `<section>`, `<h1>`, `<h2>`, and `<h3>` organize the content for readers and assistive technology.
- `mailto:` links open the visitor's configured email application.
- CSS variables in `:root` store the shared colors.
- Bootstrap `container`, `row`, `col-md-4`, and `col-md-8` arrange the responsive sections.
- `col-md-6`, `col-md-5`, and `offset-md-1` arrange the introduction and photo.
- Bootstrap `d-flex`, `gap-*`, `btn`, `badge`, and `img-fluid` format the navigation, buttons, skills, and photo.
- The `@media (max-width: 767.98px)` rule switches the page to a mobile layout.
- `:focus-visible` highlights keyboard navigation. The skip link jumps to the main content.

## Credits

AI assistance was used to help structure and style the webpage. Personal details were supplied by Lemuel Brion. Education and personal strengths were adapted from my resume.
