# The Kahvi House — website

Transport branch. This is **not** part of apex-detail-demo; it lives here only
because the Claude GitHub App grant does not allow creating a new repository.
Move it to its own repo when convenient, then delete this branch.

    kahvi-site/index.html    the whole site, one file, no dependencies

## Deploy

Cloudflare Pages → Workers & Pages → Create → Pages → Connect to Git →
this repo → branch `kahvi-house-site` → build output directory `kahvi-site`.
No build command. Pushes to this branch then redeploy automatically.

Or download `kahvi-site/index.html`, put it in a folder, and drag that folder
into Pages as a direct upload.

## Status

18 of roughly 45 catalogue items. Every gap is marked in amber on the page
and listed in the comment block at the top of the file. Not ready to be the
public site until the menu is complete.
