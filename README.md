# Srujan Mothe — Portfolio

Exact static website export with all 17 QR-free portfolio artworks.
No build step, npm installation, ChatGPT login, or server is required.

## Publish with GitHub Pages

1. Extract this ZIP on your computer.
2. Create a GitHub repository named `portfolio` (public if using GitHub Free).
3. In the repository, choose Add file > Upload files. Drag in the extracted files AND the assets folder. Upload the contents, not the ZIP or an extra outer folder.
4. Commit the upload to the default branch (usually main).
5. Open repository Settings > Pages. Under Build and deployment, choose Deploy from a branch. Select your default branch and /(root), then Save.
6. Wait for deployment and use the Visit site link shown in Settings > Pages. The typical address is https://YOUR-USERNAME.github.io/portfolio/ . Replace YOUR-USERNAME with your actual GitHub username. This example is not an already-deployed URL.

## Expected repository structure

- index.html
- style.css
- app.js
- .nojekyll
- README.md
- assets/ (17 WebP artworks, one WOFF font, favicon.svg)

Keep filenames and the assets folder unchanged. All site paths are relative, so it works under a GitHub Pages repository subpath.

## Use your own domain

If you already own a domain, GitHub Pages supports a custom domain configured through Settings > Pages and your domain provider's DNS. Do not add a CNAME file until you have selected and configured your real domain.

## Editing

- index.html: intro, about section, email address and page metadata.
- app.js: projects, descriptions and artwork references.
- style.css: colours, spacing and responsive layout.
- assets/: local images and font.

The portfolio includes campaign artwork, not current property or business offers. No campaign performance totals have been invented.
