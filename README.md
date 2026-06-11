# Dhruvraj Singh Bhati — Portfolio

Film producer portfolio. Single static `index.html`, no build step.

## Deploy on Vercel

1. Go to [vercel.com/new](https://vercel.com/new) and sign in (GitHub login is easiest).
2. Import this repository (`dsb-portfolio`).
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Click **Deploy**. The site goes live at `dsb-portfolio.vercel.app` (or similar).

Every push to `main` auto-deploys from then on.

## Updating content

All content lives in `index.html`. See `CONTENT_TODO.md` for the full list of placeholders to replace before sharing the site professionally.

- **Hero trailer:** set the `HERO_VIDEO_SRC` constant at the top of the `<script>` block to a direct `.mp4`/`.webm` URL. A Vimeo page link will not work; use a progressive file link or a self-hosted file.
- **Projects:** each project is a `.strip` element plus a matching `.detail` panel. Copy an existing pair, change the text, and swap the gradient placeholders for real stills (`<img>` tags inside the `.frame` divs).
- **Email / socials:** search for `hello@example.com` and the `#` links in the contact section.
