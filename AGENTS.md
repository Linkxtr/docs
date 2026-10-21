# Documentation project instructions

## About this project

- This is the documentation site for **Laravel QR Code** (`linkxtr/laravel-qrcode`), built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json`.

## Terminology

- Use "QR code" (two words, lowercase unless at start of sentence) rather than "qrcode" or "qr".
- Use "facade" for `QrCode::...`.
- Use "Blade component" for `<x-qr-code>`.
- Use "generator" for the underlying `Generator` instance.

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise — one idea per sentence.
- Use sentence case for headings.
- Bold for UI elements or emphasis.
- Code formatting for file names, commands, paths, config keys, env vars, and code references.

## Content boundaries

- Document all public API methods, configuration options, data types, and usage guides for `linkxtr/laravel-qrcode`.
- Do not document internal private methods or proprietary external services not part of the open-source package.
