# Etsy Workbench Site

Static landing site for `Etsy Workbench`, intended for a public-facing URL that can be used in partner and platform review flows.

## Why this repo exists

The main application repo currently includes private operational workflows and backend/storage assumptions that are not ideal for a quick public showcase deployment. This repo isolates the public-facing site so it can be deployed safely on Vercel with no build step and no runtime dependencies.

## Files

- `index.html` - public landing page
- `privacy.html` - privacy policy scaffold
- `terms.html` - terms of service scaffold
- `styles.css` - shared styles
- `assets/screenshots/` - drop real app screenshots here

## Before publishing

1. Replace `replace-with-real-email@example.com` everywhere.
2. Replace legal placeholders such as `[replace with legal entity or operator name]`.
3. Add real screenshots from the app.
4. Review copy so it matches the product's current state.
5. Review the legal pages before using them in any application or compliance flow.

## Screenshot suggestions

Recommended initial screenshot filenames:

- `assets/screenshots/theme-workspace.png`
- `assets/screenshots/prompt-workflow.png`
- `assets/screenshots/listing-workflow.png`

The current HTML uses visual placeholders. If you want to swap to real images, replace each `.screen-placeholder` block in `index.html` with an `<img>` tag.

## Vercel deploy

Because this is a plain static site, Vercel can deploy it directly with no framework configuration.

Typical flow:

1. Create a new GitHub repository for this folder.
2. Import that repository into Vercel.
3. Leave framework detection unset or let Vercel treat it as a static site.
4. Deploy.

No environment variables are required for the current version.
