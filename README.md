# My Airport Taxi NI — Premium Website Package

This is a premium multi-page Next.js website package for **My Airport Taxi NI**.

## What is included

- Premium homepage
- Quote-first enquiry tool
- No online booking checkout on the public site
- No vehicle names, vehicle models, people carrier wording, or fleet section
- Green/blue brand style and logo placeholder in `/public/logo.svg`
- Multiple SEO-friendly pages:
  - Airport Transfers
  - Belfast International Airport
  - Belfast City Airport
  - Dublin Airport
  - Cruise & Ferry Transfers
  - Corporate Travel
  - Tourist Attractions
  - Areas We Cover
  - FAQ
  - Contact
  - Legal / Policies
- Tailwind CSS styling
- Vercel-ready project structure

## How the payment flow should work

This version is quote-first:

1. Customer submits a quote request.
2. You review the job and confirm the price.
3. You send the customer a secure SumUp payment link after accepting the journey.

This keeps you in control and avoids automatic bookings at the wrong price.

## Setup

```bash
npm install
npm run dev
```

Then open:

```bash
http://localhost:3000
```

## Deploying

Recommended setup:

1. Create a GitHub repository.
2. Upload these files.
3. Connect the repository to Vercel.
4. Add the domain `www.myairporttaxini.co.uk` in Vercel.
5. Update DNS records with your domain provider.

## Important edits before going live

- Replace `/public/logo.svg` with your real logo file if you have the final artwork.
- Replace `info@myairporttaxini.co.uk` in the quote form with your preferred receiving email.
- Add your real WhatsApp number if different.
- Add real Google Reviews when available.
- Expand each SEO page with more local content over time.
