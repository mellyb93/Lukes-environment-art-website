# Luke Bryant — 3D Environment Artist Portfolio

A responsive multi-page portfolio starter built with React + Vite. Designed with a dark, cinematic AAA game-art direction, acid-lime accent, editorial typography and project case-study pages.

## Pages
- `/` — landing page
- `/work` — all projects
- `/environment-art` — environment art
- `/sculpting` — sculpting
- `/texturing` — texturing / materials
- `/about` — profile and tools
- `/project/:slug` — individual project case study

## Run locally
1. Install Node.js (18+).
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL Vite prints.
4. Run `npm run build` to create the production build in `dist/`.

## Deploy to Vercel
1. Create a new GitHub repository and upload the contents of this folder.
2. In Vercel choose **Add New → Project**, import the GitHub repository.
3. Vercel detects Vite automatically. Keep the defaults and click **Deploy**.

No environment variables are required.

## IMPORTANT — personalise before publishing
The current project titles, descriptions and remote landscape images are presentation placeholders to demonstrate the layout. They are **not claimed to be Luke's actual artwork**. Replace the project data in `src/main.jsx` with the real ArtStation project titles, descriptions, categories and image URLs. Best practice is to download/export approved portfolio images into `public/images/` and reference them locally (e.g. `/images/project-01.jpg`) so the site does not depend on third-party image hosting.

Also update:
- `hello@lukebryant.art` to Luke's preferred public contact email.
- About copy, tools and availability statement to match his actual experience.
- Each project page with genuine breakdown images: beauty renders, wireframes, high-poly/low-poly, UVs, texture maps, material graphs and Unreal Engine screenshots where available.

The ArtStation link currently points to https://lukebryant987.artstation.com/.
