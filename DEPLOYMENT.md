# GitHub and Vercel Handoff

The project is production-build ready, but this environment has no GitHub or Vercel login token.

## Publish to GitHub

1. Create a new empty GitHub repository named `local-business-website-factory`.
2. Open a terminal in this project folder.
3. Add the GitHub repository as `origin`.
4. Push the `main` branch.

## Publish to Vercel

1. Sign in to Vercel and choose **Add New Project**.
2. Import `local-business-website-factory` from GitHub.
3. Confirm:
   - Framework: Astro
   - Build command: `npm run build`
   - Output directory: `dist`
4. Deploy and open the HTTPS URL on your phone.

## Prospect Preview Workflow

1. Create a branch named `demo/<business-slug>`.
2. Update only verified configuration and approved images.
3. Push the branch to create a Vercel preview URL.
4. Keep the unofficial-concept notice visible.
5. Ask permission before sending the preview to the prospect.

## Same-Network Mobile Preview

While the local preview server is running, open `http://192.168.1.45:4321` on a phone connected to the same Wi-Fi. This address may change when the computer reconnects.
