# runti-test

This repository is a static site and can be published directly with GitHub Pages.

## Expected public URL

After GitHub Pages is enabled, the site URL should be:

`https://cheng-muyun.github.io/runti-test/`

## Publish steps

1. Push this repository to GitHub.
2. Open `Settings -> Pages`.
3. Set the source to `GitHub Actions`.
4. Wait for the `Deploy static site to GitHub Pages` workflow to finish.
5. Open the public URL above.

## Notes

- The site is a single `index.html` file, so no build step is required.
- The page currently depends on external CDNs for fonts, icons, and Chart.js.
- If the main audience is in mainland China, consider replacing those CDN links with local files later.
