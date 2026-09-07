# echoooh-support

Support and privacy pages for the Echo-Ooh iOS app, served by GitHub
Pages at <https://wz333.app/echoooh-support/>.

- `index.html` — Support: contact, common questions, publisher takedown.
- `privacy.html` — Privacy Policy.
- `assets/` — app icon and three-monkeys mark, taken from
  the app's own asset catalog.

No build step; the two pages are hand-written HTML with inline CSS.
They reproduce the app's design system (see `DESIGN.md` in the app
repo): warm paper ground, cream fill for anything touchable, one
saturated accent (Brush Red `#EE4B26`), no borders, no shadows, no
cards. Light-only, matching the app's pinned light colour scheme.

There is no `CNAME` file here on purpose: the apex domain is configured
on `wz333/wz333.github.io`, and project pages inherit it as
`wz333.app/<repo>/`.
