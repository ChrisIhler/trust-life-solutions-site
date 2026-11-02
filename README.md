# Trust Life Solutions website

Live site: **[trustlifesolutions.com](https://trustlifesolutions.com)**

![Trust Life Solutions homepage](docs/screenshot-home.webp)

A static, multi-page website for Trust Life Solutions, an independent life insurance practice in Washington State. Built with Claude Code in plain HTML, CSS and JavaScript (no framework or build step), versioned on GitHub and deployed on Cloudflare Pages.

## What's on the site

- **Coverage pages:** term life, whole life, IUL (plus an IUL explainer), final expense, mortgage protection and annuities
- **Interactive tools:** a life insurance needs calculator, a rate estimator and a policy-review scorecard
- **Lead capture:** quote and policy-review forms that post to Google Apps Script, with thank-you pages
- **Lead magnet:** "5 Life Insurance Mistakes" guide (HTML page plus PDF)
- **Blog** and **product** pages
- **Compliance pages:** privacy policy, terms, and a consumer health data privacy notice
- **SEO basics:** sitemap.xml, robots.txt and a custom 404 page

## Structure

```
/              site pages (index.html, coverage pages, tools, forms, legal)
/blog          blog articles
/products      product pages
/brand-assets  logos and brand images
/docs          README assets
```

## Running locally

No build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## About

Built and maintained by [Chris Ihler](https://github.com/ChrisIhler), AI implementation and automation consultant. Available for website and automation work on [Upwork](https://www.upwork.com/freelancers/chrisihler).
