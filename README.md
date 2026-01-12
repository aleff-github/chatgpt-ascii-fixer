# ASCII Punctuation Fixer

A single-file, client-side web tool that converts "smart punctuation" and other common Unicode troublemakers (curly quotes, em/en dashes, NBSP, ellipsis, zero-width characters, ligatures, etc.) into plain ASCII.

This is useful when you paste text into environments that expect ASCII (config files, CSV/JSON, shell scripts, code, or strict parsers).

## Demo (GitHub Pages)

After enabling GitHub Pages, your site will be available at:

- https://aleff-github.github.io/chatgpt-ascii-fixer/

## Features

- One static page: no build step, no dependencies
- Client-side only: your text never leaves the browser
- Optional NFKC normalization
- Optional removal of invisible characters (ZWSP, BOM, soft hyphen, etc.)
- Diagnostics table showing codepoints and applied replacements
- Copy/download output

## Local usage

Just open `index.html` in your browser.

No server required.

## License (GPLv3)

This project is licensed under the GNU General Public License v3.0 (GPL-3.0-only). See the `LICENSE` file.

To ensure GitHub recognizes the license automatically, use GitHub's "Add a license" flow to create the standard GPLv3 license file, or paste the official text from GNU into `LICENSE`.
