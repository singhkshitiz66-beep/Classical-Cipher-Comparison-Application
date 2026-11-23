# CRYPTA — Classical Cipher & Compression Studio

CRYPTA is a complete, dependency-free web application for exploring classical ciphers and simple text encodings. All transformations run in your browser; no account, build step, or network service is needed.

## Run it

**Option 1 — open directly:** open `index.html` in a modern browser.

**Option 2 — run a local server:** install [Node.js 18 or newer](https://nodejs.org/), open a terminal in this project folder, and run:

```sh
npm start
```

Then visit `http://127.0.0.1:4173`.

## Included tools

- **Caesar shift:** encrypt or decrypt with a configurable shift from 0 to 25.
- **Vigenère cipher:** keyword-based encryption and decryption, preserving case, spaces, and punctuation.
- **Atbash** and **ROT13:** reciprocal alphabet substitution ciphers.
- **Run-length encoding:** lossless encoding and decoding of repeated characters using `count#character` tokens.
- **Base64:** UTF-8 text encoding and decoding. Base64 is an encoding, not encryption.
- UTF-8 byte-size comparison, copy-to-clipboard, and save-result-as-text actions.

## Project files

- `index.html` — app interface, styling, and browser-side transformation logic
- `server.js` — optional tiny Node.js static server
- `package.json` — project metadata and `npm start` command
- `README.md` — usage and project notes

## Security note

This is a learning tool. Classical ciphers and Base64 are not suitable for protecting sensitive information. The displayed byte counts cover the UTF-8 text only, not any storage or transport overhead.
