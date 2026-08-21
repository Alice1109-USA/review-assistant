# Massage Review Assistant - GitHub Pages Version

This folder is the public customer-facing site.

## Files

- `index.html` is the customer review page.
- `clients.json` stores the public business settings for short Vercel links.
- `vercel.json` makes random-number subpages open the customer page on Vercel.
- Keep `builder.html` local if you want the setup page to stay private.

## Vercel URL

The public customer page is:

```text
https://review-assistant-sigma.vercel.app/
```

Each client can use a short random-number URL, for example:

```text
https://review-assistant-sigma.vercel.app/69785975
```

The random number is the company ID. The public page looks up that ID in `clients.json`.

## Workflow

1. Open your local `builder.html` file.
2. Fill in the business name, city, Google review link, Yelp review link, and SEO keywords.
3. Click `Save to List`.
4. Click `Export clients.json for Vercel`.
5. Replace the online `clients.json` file with the exported one.
6. Use the short `Client NFC / QR URL` for the NFC tag or QR code.

## What Customers See

Customers only see the review page. They can select their massage experience, get a generated review, and open Google or Yelp.

## What You Keep Private

Keep the link builder local on your computer, or host it privately somewhere else. It is not included in this public folder.
