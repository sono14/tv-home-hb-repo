# TV Home Homebrew repository

This folder is a self-hosted Homebrew Channel repository for the TV Home webOS app.

## Host the repository

Homebrew Channel must be able to fetch these files from a public HTTPS address. The TV also needs internet access to that host.

For GitHub Pages:

1. Create a public GitHub repository and upload the contents of this folder to its top level.
2. In the repository, open Settings → Pages and publish from the main branch and root folder.
3. After GitHub Pages is available, the catalog URL will be:

   https://<your-github-username>.github.io/<repository-name>/apps.json

For another static HTTPS host, upload all files together and use the public URL to apps.json. Keep apps.json, the manifest, icon, and IPK in the same folder so the relative links work.

## Add it in Homebrew Channel

On the TV, open Homebrew Channel → Settings → Repositories → Add Repository. Enter the public apps.json URL, save it, then return to the catalog and select TV Home → Install.

This repository only describes the app and points to its IPK. It does not publish itself. Homebrew Channel must already be installed and usable on the TV.
