# QR Code Website

Static site for the Tech Made Simple QR code — a Southern barbecue menu demo.

Live at **https://qr.techmadesimple.help**

## Hosting

Hosted on **Cloudflare Pages as a Git-connected project**: `qr-code-website-git`,
bound to `bvalvik/qr-code-website`, production branch `main`.

Pushing to `main` deploys automatically. There is no manual upload step and no
build command — the files are served as-is.

Build settings:

- Framework preset: None
- Build command: *(empty)*
- Build output directory: `/`

## Files

| File | Purpose |
|---|---|
| `index.html` | The menu page |
| `banner.jpg` | Top banner |
| `404.html` | Not-found page |
| `robots.txt` | Crawler rules |

## History worth knowing

The site started as a Direct Upload project named `qr-code-website`, deployed with
`wrangler`. **Cloudflare does not allow converting a Direct Upload project to Git
integration** — a new project is required. That is why the current project is
`qr-code-website-git`, and why the custom domain was moved from the old project to
this one.

Editing files here and pushing is now the whole workflow.
