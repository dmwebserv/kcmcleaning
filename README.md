# KCM Cleaning website

Static HTML/CSS marketing site for KCM Cleaning, a window, gutter, fascia and
soffit cleaning business serving Frinton, Walton and Clacton (Essex, UK).

There is no build step, framework, or package manager - every page is plain
HTML with inlined CSS.

## Pages

- `index.html` - main landing page (services, areas covered, contact form)
- `privacy-policy.html` - privacy policy
- `thanks.html` - post-enquiry thank-you page
- `images/` - site images, including the favicon and the Open Graph share
  image (`kcm-og.jpg`)
- `robots.txt`, `sitemap.xml` - SEO/crawler files
- `CNAME` - custom domain used by GitHub Pages (kcmcleaning.co.uk)

## Previewing changes locally

No build tools are required. From the repo root, serve the folder with any
static file server and open it in a browser, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Deploying

The site is deployed automatically via GitHub Pages, using the `CNAME` file
to serve it at `kcmcleaning.co.uk`. Pushing changes to the repository's
default branch (`main`) is enough to publish them - there is no separate
deploy step or CI pipeline.
