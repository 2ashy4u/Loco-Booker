# Client website previews

Two standalone, responsive static website MVPs:

- [Loco-Motion Pro](./Locomotive/index.html)
- [BookerLAB](./BookerLabs/index.html)

Open either site's `index.html` in a browser to preview it locally. No dependency installation or build command is required.

## Brand themes

The modern layouts retain the original sites' visual themes:

- BookerLAB: its original purple (`#824d9f`), black and white palette, with Oswald headlines and Heebo body text.
- Loco-Motion Pro: stormy charcoal and metallic gray, red-orange accents, and the original teal (`#3f6f75`) and deep teal (`#1f373b`) section colors.

## Deploy to Vercel

Import this repository twice to create two separate Vercel projects:

| Project | Root Directory | Framework Preset |
| --- | --- | --- |
| `locomotionpro-preview` | `Locomotive` | Other |
| `bookerlab-preview` | `BookerLabs` | Other |

Leave the Build Command empty and use `.` as the Output Directory. Each project will receive its own Vercel URL. Do not connect the live domains for the initial client previews.

These are presentation MVPs, not replacements for the existing commerce or support systems. Product/support buttons on BookerLAB link to the existing live site; Loco-Motion Pro enquiries open an email application.

Fonts and stock hero photography load from external services and require an internet connection. Product artwork is illustrative rather than product photography. Confirm copy, current prices, imagery permissions and product availability before a production launch.
