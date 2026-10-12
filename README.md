# Narrative

The content of the White Page First website: the article *White Page First & Contract First*
and every page of the site. The website reads these files from the raw endpoint of this repository, so a change
here is live on the site a few minutes after it is pushed to `main`.

- `wpf.yaml` holds the overview page (`home`) and the contact page. Its header lists every section type.
- `pages/<name>.yaml` are the reading pages, served at `/<name>`.
- `contact.md` is included from the YAML with `$ref`; other Markdown files can be included the same way.

To preview edits before pushing, run the website with `CONTENT_BASE_URL=../public/Narrative npm run dev`.

Licensed under [CC0-1.0](LICENSE).
