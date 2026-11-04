# SignBuddy review playground

A standalone, static testing site for reviewing ARASAAC pictograms and the starter BSL dictionary entries before anything is merged into the main SignBuddy app.

## Why this repository exists

- Separate from the main SignBuddy repository and its Vercel deployment.
- Does not trigger a Vercel build.
- Uses plain HTML, CSS and JavaScript, so GitHub Pages can host it without a Next.js server.
- Searches the public ARASAAC English pictogram endpoint directly from the browser.
- Includes a small review checklist for the six starter BSL entries. Review selections are stored only in the current browser's local storage.

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Pushes to the default branch run the workflow in `.github/workflows/pages.yml`.
4. GitHub Pages will publish the static site at `https://ray-seal.github.io/Sign-buddy-preview/`.

No Vercel project is connected to this repository.

## ARASAAC

Pictograms are the property of the Government of Aragón and were created by Sergio Palao for ARASAAC. They are distributed under the ARASAAC Creative Commons BY-NC-SA terms. The preview includes visible attribution. Check the official terms before commercial use or redistribution: https://arasaac.org/terms-of-use

The symbols are visual communication aids. They are not BSL signs and must not be presented as sign-language demonstrations.

## BSL content

The six entries (hello, thank you, please, help, family, school) are starter placeholders only. No entry contains verified signing guidance. Confirm actual signs with competent BSL users and source genuine demonstrations before treating any entry as reliable.


## Deployment

GitHub Pages deployment workflow is configured in `.github/workflows/pages.yml` and runs on pushes to `main`.


GitHub Pages setup confirmed. Static preview deployment can now run through GitHub Actions.
