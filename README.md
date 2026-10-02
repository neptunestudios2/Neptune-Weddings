# Neptune Wedding Website

Standalone handoff copy of the Neptune Studios wedding website. The full website is in this repository's root, including all files from the original `neptune-portfolio-v1` folder.

## Download and preview

1. Click **Code → Download ZIP** on GitHub and unzip the download. No GitHub account is needed to download this public repository.
2. Open `index.html` in your browser. Keep the `assets` folder alongside it.

Alternatively, with Git installed:

```sh
git clone https://github.com/sovreignz/neptune-wedding-website.git
cd neptune-wedding-website
```

There is no package installation, build step, backend, or API key required. Google Fonts loads online; fallback fonts are included in the styling.

## Files

- `index.html`: all page copy, styles, carousel behavior, and enquiry links.
- `assets/final/`: the 28 category photos and their 28 thumbnail previews.
- Other images in `assets/`: earlier portfolio assets retained so the complete original folder is included.

All four enquiry buttons open https://neptunestudios.co.uk/pages/wedding-flowers. This repository does not process form submissions.

## Move to Nico's GitHub account

Once Nico has a GitHub account, he can **Fork** this repository to get his own copy immediately.

For a separate repository instead of a fork:

1. Clone this repository using the commands above.
2. Create an empty repository in Nico's GitHub account. Do not initialize it with a README or license.
3. In the cloned folder, run the following, replacing `YOUR_USERNAME` and `YOUR_REPOSITORY` with the new repository's details:

```sh
git remote rename origin handoff
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

GitHub will require authentication when pushing to the new account.

## Hosting later

This is a plain static website and can be hosted from the repository root. For GitHub Pages, choose **Settings → Pages → Deploy from a branch**, then **main** and **/(root)**. No custom domain is configured in this handoff repository.

The existing live preview remains at https://kxros.io/neptune-portfolio-v1/. Changes to this standalone repository do not automatically update that original site.
