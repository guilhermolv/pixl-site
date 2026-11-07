# pixl-site

Static legal, support and share-link pages for the Pixl iOS app, served by GitHub Pages
at https://guilhermolv.github.io/pixl-site/.

- `privacy/`, `terms/`, `support/`: pages linked from the app and App Store Connect.
- `open/`: share-link page. `open/?g=<game id>` opens `pixl://games/<game id>` in the app.

Before publishing, replace every `[PLACEHOLDER]` (`[LEGAL_NAME]`, `[CONTACT_EMAIL]`,
`[EFFECTIVE_DATE]`, `[COMPANY_REGISTRATION]`, `[GOVERNING_LAW]`). This finds any left over:

    grep -rn "\[[A-Z_]*\]" --include=*.html .
