# Ghar Ka Swad Tiffin Service

A simple, responsive landing page for a homemade tiffin service. The site highlights the weekly menu, service benefits, and contact information for placing orders.

## Overview

This project is a static HTML website built as a promotional page for **Ghar Ka Swad Tiffin Service**. It is designed to work well on desktop and mobile, with a warm food-focused visual style, animated section reveals, and a clear call to action for customer inquiries.

## Features

- Full-screen hero section with service positioning and CTA
- Weekly rotating menu for Monday through Sunday
- Benefits section for freshness, hygiene, affordability, and homemade food
- Contact section with phone/WhatsApp call-to-action
- Responsive layout for mobile, tablet, and desktop
- Lightweight implementation with no build step required

## Tech Stack

- `HTML5`
- `CSS3`
- Vanilla `JavaScript`
- Vercel for deployment

## Project Structure

```text
.
|-- index.html
|-- alias-response.html
|-- qr-code.svg
|-- .gitignore
`-- .vercel/
```

## Running Locally

Since this is a static site, you can preview it in either of these ways:

1. Open `index.html` directly in your browser.
2. Serve the folder with a local static server.

Example using Node:

```bash
npx serve .
```

Then open the local URL shown in your terminal.

## Deployment

This project is connected to Vercel through the local `.vercel/project.json` metadata.

If you want to deploy manually:

```bash
npx vercel --prod
```

Note: the current Vercel alias response checked in this repo indicates deployment protection is enabled for that URL, so public access may require authentication unless that setting is changed in Vercel.

## Customization

You can update business content directly in `index.html`, including:

- service name
- weekly menu items
- contact name
- address
- phone number
- colors, typography, and section copy

## Repository Purpose

This repository is best suited for:

- a small business showcase site
- a tiffin or food subscription landing page
- a low-maintenance static marketing page

## License

This project does not currently include a license file. Add one if you want to define reuse permissions.
