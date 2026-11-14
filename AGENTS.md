# Nimbus site

Public support and privacy pages for Nimbus, a Mac download manager by Amr Ali. GitHub Pages can serve the live site from `main`. Do not merge, deploy, or push to `main` unless Dr Amr asks.

## Keep these stable

- These addresses must keep working: `/`, `index.html`, `support.html`, and `privacy.html`. Do not rename those files.
- App name: Nimbus. The optional purchase is Nimbus Pro. Do not rename either, and do not add or change a price.
- Contact email stays `amroqazzaz@gmail.com`.
- Do not change what the privacy policy promises. If a sentence looks wrong, flag it in the pull request. Do not quietly rewrite the claim.
- The header, footer, and `styles.css` are copied by hand. If navigation changes, update every page.
- Do not commit passwords, tokens, or keys.

## Notes left on purpose

- The privacy policy says Nimbus does not “otherwise process personal data,” while later sections describe information kept on the Mac. That wording was left as published.
- The policy does not say that a server you download from can see your IP address, the way any web request would. It does say those requests are not sent to the developer.
- No street address is published. Do not invent one.
- The app’s source code is not in this repository, so claims such as “no developer server” cannot be checked from here.

## Preview

From this folder, serve the files with any static server and open `index.html`, `support.html`, and `privacy.html`. Check a phone width and dark mode before finishing.
