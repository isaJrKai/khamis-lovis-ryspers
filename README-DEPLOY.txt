# Deploy to Netlify (drag & drop)

This folder is a static site, ready to deploy.

## Steps

1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page (or drag the .zip if you have one)
3. Wait ~10 seconds. You'll get a live URL like `https://random-name.netlify.app`

## Contact form

The contact form uses Netlify Forms. After your first deploy:

1. Open your site on Netlify and click **Forms** in the sidebar
2. You'll see a "contact" form there (it auto-detects after the first real submission)
3. Under **Form settings → Email notifications**, add your email
   (`unlimited.khamislovisryspers.com@gmail.com`) to get notified of every submission

## Re-deploying after edits

If you edit the source and want a new version online:

1. Run `bun run build` (regenerates this `out/` folder)
2. Drag the `out/` folder to Netlify again (it updates the same site)

## What's in here

- `index.html` - the portfolio
- `_next/` - JavaScript & CSS bundles
- `site/` - photos + logo
- `__forms.html` - tells Netlify to enable the contact form

That's it. No server, no database, no config needed.
