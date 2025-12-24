# Bato-image-Rewritter

A JavaScript fix for the **Bato extension** on the **Mihon app**.  
It rewrites image URLs from `//k` to `//n` and removes the referrer.

## Features
- Updates images on Mihon pages
- Sets `referrerPolicy` to `no-referrer`
- Runs every 2 seconds to catch new images
- Only runs on Mihon domain

## Usage (Bookmarklet)
1. Copy code from `bookmarklet/bookmarklet.js`
2. Create a browser bookmark
3. Paste the code into the URL field
4. Click the bookmark while on Mihon

## Development
Source code is in `src/imageRewriter.js`

## License
MIT
