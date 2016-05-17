# Development

Install the dependencies:

    npm install webpack -g
    npm install

To build the project:

    webpack --watch

And run the tests:

    npm run test

### Loading the extension in Chrome

1. Go to [chrome://extensions/](chrome://extensions/)
2. Enter Developer Mode
3. Load Unpacked Extension
4. Select "extension" directory in this repo

### Generating the bookmarklet

Run `node ./dev/generate-bookmarklet.js`.

### Update website

`git subtree push  --prefix gh-pages origin gh-pages`

### Upload to Chrome Web Store

Run `./dev/make-dist-directory.sh` and then upload dist.zip.

## Other releases to update

- bookmarklet
- NPM module
- live demo