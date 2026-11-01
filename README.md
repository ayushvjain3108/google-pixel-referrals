
# PixelPerks — Google Store Referral Codes

A free, responsive static website for sharing Google Store
referral codes offering 10% off eligible Pixel purchases.

## Features

- Seven currently listed active referral codes
- One-click copy buttons
- Mobile-friendly responsive design
- SEO and Open Graph metadata
- No frameworks, dependencies, or backend
- Free hosting through GitHub Pages

## Updating referral codes

Open `index.html` and find:

```javascript
const referrals = [
  {
    code: "REF-EXAMPLE",
    status: "active"
  }
];
```

To mark a code as redeemed, change:

`status: "active"`

to:

`status: "pending"`

The site automatically hides pending codes and updates
the active-code count.

Update the `lastUpdated` variable whenever you verify
the codes against your Google Store referral dashboard.

Commit the changes to publish the update.

## GitHub Pages deployment

1. Create a public GitHub repository.
2. Upload index.html, robots.txt, and README.md.
3. Open Settings > Pages.
4. Select Deploy from a branch.
5. Select main and / (root).
6. Save and wait for deployment.

## Important

This is an independent referral listing, not an official
Google website.

The owner may receive $50 in Google Store credit for
qualifying referrals.

All offers are subject to Google's promotion terms.
