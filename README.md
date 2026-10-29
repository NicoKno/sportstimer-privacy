# Sports Timer — Privacy & Support

Public German and English privacy policy and support page for Sports Timer for iPhone and Apple Watch.

**Privacy policy:** https://privacy.monastery-coding.de/

**Support:** https://privacy.monastery-coding.de/support/

**Privacy and support contact:** support@monastery-coding.de

## Hosting

GitHub Pages publishes branch `main`, folder `/`, using **Deploy from a branch**. The `.nojekyll` file keeps this plain HTML site buildless. No JavaScript, analytics, external fonts, or advertising are included.

## Updating the pages

Edit `index.html` or `support/index.html`, keep the German and English versions consistent, update the revision date when appropriate, and push to `main`. GitHub Pages automatically publishes the change.

This repository contains only the public privacy and support website. The app source code is maintained separately.

## Custom domain

The custom domain is `privacy.monastery-coding.de`. The domain is registered at INWX; authoritative DNS is managed by Cloudflare.

Required Cloudflare DNS record:

| Type | Name | Target | Proxy | TTL |
| --- | --- | --- | --- | --- |
| CNAME | privacy | nicokno.github.io | DNS only | Auto |

Keep the `CNAME` file in the published root and configure the same custom domain in the GitHub Pages settings. Enable **Enforce HTTPS** once GitHub has provisioned the certificate. Existing email records and nameservers do not need changes.
