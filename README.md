# Birthday website

A no-build birthday page that works in current Safari and Chrome. Edit the birthday person's name, message, sign-off, and public photo link with **Edit this page**. Changes are saved in that browser; **Copy link** and **Share on WhatsApp** create a URL containing the current customizations so recipients see the same page.

## Publish with GitHub Pages

The included workflow publishes the site on every push to `main`.

1. In the repository on GitHub, open **Settings > Pages**.
2. Set **Build and deployment > Source** to **GitHub Actions**.
3. Push the repository to `main` and wait for the **Publish birthday website** workflow to finish.
4. Open the Pages URL shown in the workflow or in **Settings > Pages**. It will look like `https://OWNER.github.io/Birthday-pooja/`.

After the first setup, pushing updates to `main` republishes the site. Use a public image URL for a photo so it is available to everyone opening the shared link.