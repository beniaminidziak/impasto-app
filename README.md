# Impasto — Public Site

Public site for [Impasto](https://github.com/beniaminidziak/Impasto), a pizza dough recipe app for iOS.

Hosted on GitHub Pages: <https://beniaminidziak.github.io/impasto-app/>

## Structure

```
/                      Landing page (icon, wordmark, links to pages below)
/privacy/              Privacy Policy
icon.png               Shared app icon, referenced by every page
```

New pages live in their own folder with an `index.html` so URLs stay clean (`/support/` rather than `/support.html`). GitHub Pages serves `index.html` automatically for any folder.

## Updating

Edit the relevant HTML, commit to `main`, and GitHub Pages redeploys automatically. When the privacy policy substantively changes, bump the "Last updated" date in the footer and call out the change in the next app release notes.

## License

The markup in this repository is released under the MIT License (see `LICENSE`). The policy content itself describes the actual data practices of the Impasto app and is intended to be read, not reused.
