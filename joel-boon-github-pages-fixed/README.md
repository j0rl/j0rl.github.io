# Joel Boon — Engineering Portfolio

Complete website source for GitHub Pages, with project images, résumé PDFs, final design reports, the robot clip, and both parts of the sermon. The latest design includes the Resume link label, the 300 lbf wing load, and the compact project media layouts.

This site uses plain HTML, CSS, and JavaScript. It needs no installation, build command, API key, or ChatGPT account to run.

## Publish using the GitHub website

1. Sign in to GitHub and create a **public** repository named `YOUR-USERNAME.github.io`, replacing `YOUR-USERNAME` with your exact GitHub username. Leave the repository initialization options unchecked; this package already includes a README.
2. Unzip this package. In the new repository, choose **uploading an existing file** (or **Add file → Upload files**).
3. Upload the extracted contents, including the entire `assets` folder. The repository root must contain `index.html` beside `styles.css`, `favicon.svg`, and `assets`. Upload the contents, not the ZIP or an extra enclosing folder. Keep `.nojekyll` at the root; if your file picker hides it, create a file with that name in GitHub and put `# Static website` in it.
4. Commit the upload to `main`.
5. Open **Settings → Pages**. Select **Deploy from a branch**, then **main** and **/(root)**, and save.
6. Once the Pages deployment finishes, open the published address shown in Settings → Pages. For the repository name above, the address is `https://YOUR-USERNAME.github.io/`.

GitHub Free supports Pages in public repositories, so this route makes the website code and included assets public. If `YOUR-USERNAME.github.io` already hosts another site, use a new repository such as `portfolio`; its default address will be `https://YOUR-USERNAME.github.io/portfolio/`. The relative links in this package support either route.

## Upload with Git instead (optional)

After creating the empty public repository, open a terminal in the extracted folder containing `index.html`. Replace both occurrences of `YOUR-USERNAME` below before running the commands:

```bash
git init
git branch -M main
git add .
git commit -m "Publish Joel Boon engineering portfolio"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

Sign in through Git's supported GitHub authentication prompt if requested. Then enable Pages using step 5 above.

## Edit and update

- `index.html`: all text, sections, project links, and video behavior.
- `styles.css`: colors, typography, image sizing, and responsive layout.
- `assets/`: images, PDFs, and videos; retain these names to preserve existing links.
- `.nojekyll`: tells Pages to serve the static files without Jekyll processing.

Commit changes to `main` to publish updates automatically. Edits to the original ChatGPT-hosted site do not automatically update this repository. After publishing, check the résumé, all three project reports, both sermon parts, and robot video in a signed-out browser window.

## Connect a domain you own

The GitHub address is available without buying a domain. To use your own address, first verify ownership in GitHub, then add it under **Settings → Pages → Custom domain**. Configure the matching DNS records at your domain registrar using GitHub's official instructions below. Enable **Enforce HTTPS** when available. Keep the generated `CNAME` file when updating the site. Domain registration is paid separately.

## Size and setup references

This package contains about 92.5 MiB of website content. Its largest asset is about 24.7 MiB, within GitHub's 25 MiB browser-upload limit. The published site is below Pages' 1 GB size limit. Pages has a soft bandwidth limit of 100 GB per month; video plays and PDF downloads contribute to bandwidth use.

Official documentation checked September 16, 2026:

- [What is GitHub Pages?](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [Upload files](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [Configure the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Pages limits](https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits)
- [Custom domains](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
