# Local Business Website Factory

Reusable Astro template for creating clearly labelled local-business concept demos.

## Run locally

```sh
npm install
npm run dev
```

## Create a new client demo

1. Create a client brief from `client-briefs/template.md`.
2. Verify every real-business claim and allowed asset.
3. Update `src/config/business.json`, `services.json`, and `content.json`.
4. Replace project images in `public/images`.
5. Keep the concept-demo notice visible until the business approves publication.
6. Run `npm run build` and check desktop/mobile layouts.
7. Push a separate Git branch to create a Vercel preview URL.

`src/config/variations/calmcare-business.json` is a second fictional variation proving that branding and business data can be swapped without changing components.

## Deploy

Import this Git repository at Vercel. Framework preset: Astro. Build command: `npm run build`. Output directory: `dist`.

## Safety

The appointment form is intentionally local-only. It validates inputs, shows confirmation, and sends or stores nothing.
