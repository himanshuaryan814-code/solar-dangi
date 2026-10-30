# Dangi Solar Solutions — GitHub-ready website

Mobile-first React + TypeScript + Vite website for DANGI SOLAR SOLUTIONS. Designed for deployment to Vercel or GitHub-connected hosting.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Deploy

1. Create a GitHub repository and upload/push this project.
2. Import the repository into Vercel.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Deploy. No environment variables are required for this static starter.

## Important before public launch

- **No existing source repository was attached to the request.** This is a fresh implementation based on the supplied brief, not a patch to an inspected live project.
- Product and category photography currently uses remote Unsplash image URLs as illustrative imagery. Replace them with licensed/local assets in `public/images/` and update the `images` object in `src/App.tsx` before launch. Project gallery items are explicitly labelled illustrative and must not be presented as actual customer installations.
- Founder photo is a clearly identified placeholder; replace only after receiving an approved real photo.
- Brand blocks use editable wordmarks, **not official logo artwork**. Obtain and use authorized/official logo files only after verifying correct identity and permitted use. The displayed brands do not imply authorized dealer status.
- Customer review section intentionally contains no invented testimonials. Add verified source reviews only after receiving them.
- The calculator is functional but indicative. It uses simplified assumptions (1,450 kWh/kW/year, assumed self-consumption, an implied average rate from bill/units, and a default cost assumption). It does not yet use verified DHBVN/UHBVN tariff tables, fixed-charge modelling or live export-credit rules. Replace assumptions with verified current data before presenting it as a quote tool.
- Subsidy figures are indicative. Confirm current PM Surya Ghar official guidelines before launch. Subsidy is not guaranteed and is not applied to commercial/agricultural categories in the calculator.
- The enquiry form validates fields in-browser and opens WhatsApp with the enquiry details. It does not store submissions in a database. Verify the phone number and privacy practices before launch.
- Privacy policy and terms are starter summaries and should be reviewed against the final implementation and applicable requirements.

## Routes included

`/`, `/about`, `/residential-solar`, `/commercial-solar`, `/agricultural-solar`, `/solar-inverters`, `/solar-batteries`, `/solar-street-lights`, `/solar-water-pumps`, `/solar-savings-calculator`, `/pm-surya-ghar-subsidy`, `/products-and-brands`, `/projects`, `/installation-maintenance`, `/reviews`, `/faq`, `/contact`, `/privacy-policy`, `/terms`.

## Replaceable image folders

The requested folder structure is created under `public/images/` for hero, residential, commercial, agriculture, inverters, batteries, streetlights, water pumps, installation, founder, projects and brands.
