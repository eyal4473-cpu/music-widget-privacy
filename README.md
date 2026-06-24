# Music Widget — public assets

This repository hosts the **public-facing privacy policy** for the [Music Widget](https://play.google.com/store/apps/details?id=com.eyalar.cloudtunes) Android app, served via GitHub Pages.

## Live URL

- Privacy policy: **<https://USERNAME.github.io/music-widget-privacy/privacy-policy.html>**
- Repo root redirects to the privacy policy.

Update `USERNAME` to match the GitHub account once the page is live, and use the privacy-policy URL in:

- Google Play Console → App content → Privacy policy
- Spotify Developer Dashboard → app settings → Privacy Policy URL
- (Optional) the in-app Settings screen "Privacy" link

## Updating the policy

The canonical source of the policy is `play-store-assets/privacy-policy.html` in the [Music Widget app repo](https://github.com/USERNAME/music-widget) (private). When the in-app copy changes:

1. Copy the new HTML into `privacy-policy.html` here.
2. Bump the `Last updated` date in both the in-app copy and this hosted copy.
3. Commit + push to `main` — GitHub Pages re-publishes within ~60 seconds.

## Files

| File | Purpose |
| --- | --- |
| `privacy-policy.html` | The actual policy Play / Spotify links to. |
| `index.html` | Bare-domain landing page that redirects to the policy (so the repo's GitHub Pages root doesn't 404). |
| `.nojekyll` | Tells GitHub Pages to serve the files verbatim, not feed them through Jekyll. |
