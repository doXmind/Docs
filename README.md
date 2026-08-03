# doXmind Docs

Official documentation for [doXmind](https://doxmind.com), a fully local, Markdown-native knowledge workspace.

The product has one editable content type: a Page backed by one portable `.md` or `.markdown` file. PDF, spreadsheet, and HTML files are read-only Attachments. Existing sidecars are preserved only as legacy recovery evidence.

## Local development

```sh
npm install
npm run dev
```

Validate the documentation before publishing:

```sh
npm run validate
npm run check:links
```
