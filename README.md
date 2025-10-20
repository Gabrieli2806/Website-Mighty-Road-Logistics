# Mighty Road Logistics — Static Site

This is a minimal static website for Mighty Road Logistics, intended for hosting on Vercel. It includes basic company info, services, mission, and contact details.

Files added:
- `index.html` — main page
- `styles.css` — styling (black / gold / white palette)
- `img/logo/` — contains example logos `logo1.jpg`, `logo2.jpg`, `logo3.jpg` (site uses `logo1.jpg` by default)

How to deploy to Vercel:
1. Install Vercel CLI (optional) or use the Vercel dashboard.
2. From this project folder, run `vercel` and follow prompts to deploy.

Quick Vercel tips:
- If you use the Vercel dashboard, link the repo and set the root folder to this project.
- For a plain static site, no build command is necessary. Vercel will detect and deploy the static files.


Replace images:
- To replace the header logo, overwrite `img/logo/logo1.jpg` or update the `src` in `index.html`.
- Add a hero image at `img/hero-truck.jpg` or change the path in `index.html`.

Future improvements:
- Add pricing section and dynamic quote form.
- Add testimonials, tracking integration, and analytics.
- Add an FAQ and a page for detailed services.

Recommended next additions (priority):
- Contact form (serverless) so visitors can request quotes. Use Vercel Serverless Functions or a service like Formspree.
- Pricing table and a simple CMS (Sanity, Netlify CMS, or Vercel + Git) so you can update prices without redeploying.
- Testimonials / Reviews and a Google Maps embed for the address.
- Accessibility checks and mobile performance optimizations.

Colors:
- Black (#000), Gold (#bfa76b), White (#fff)

Contact info embedded in the page (English):
- Address: 1806 Glen Oaks Terrace, Chattanooga, TN 37412
- Phone: +1 (423) 490-22242
- Email: mightyroadlogistics7@gmail.com

If you want, I can:
- Add a contact form that sends emails using a serverless function.
- Create a pricing table and admin-editable CMS (e.g., Sanity/Contentful).
