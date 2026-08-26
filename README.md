# ADAM: ∆Ψ Website

A simple static promotional website for **ADAM: ∆Ψ — A Change in the Wavefunction**.

It is intentionally built with plain HTML, CSS, and JavaScript so it can be hosted for free with GitHub Pages and edited without a framework or build process.

## Files

- `index.html` — page structure and copy
- `styles.css` — all visual styling
- `script.js` — mobile navigation and current copyright year
- `assets/` — put your logo, comic artwork, social preview image, etc. here

## Before publishing

Search the project files for `YOUR_`.

Replace these placeholders:

- `YOUR_KICKSTARTER_URL`
- `YOUR_INSTAGRAM_URL`
- `YOUR_EMAIL_ADDRESS`
- Mailchimp form values in the newsletter form

## Mailchimp signup

The signup form in `index.html` is already structured to submit directly to Mailchimp.

In Mailchimp:

1. Open the Audience you want to use.
2. Find/create an embedded signup form.
3. Look at Mailchimp's generated `<form>` tag.
4. Copy the URL from its `action="..."` attribute.
5. Replace the placeholder `action` URL in `index.html`.
6. If Mailchimp gives you a hidden anti-bot field, copy that hidden input into the spot marked in `index.html`.

You do **not** need to put a Mailchimp API key into this website. Never expose an API key in public GitHub code.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all of these files to the repository root.
3. Commit the files.
4. Open the repository's **Settings**.
5. Open **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)`.
8. Save.

GitHub will give you a public site URL.

## Custom domain later

You can initially use the free GitHub Pages address. If you buy a domain later, add it in your repository's GitHub Pages settings and update the required DNS records with your domain registrar.

## Artwork

The current version is intentionally text-led so the site works before artwork is added.

When ready, the best next visual upgrade would be:

- Hero/cover artwork
- ADAM character art
- 2–4 finished/sequential comic panels
- Kickstarter trailer or embedded YouTube video
- Social preview image at `assets/social-preview.jpg`

## Editing the colors

The site's main colors are at the top of `styles.css` under `:root`.

The current accent is:

```css
--accent: #ff4f3d;
```

Change that one color family if you decide another color better matches the final ADAM branding.
