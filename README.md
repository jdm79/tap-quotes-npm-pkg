![npm](https://img.shields.io/npm/v/tap-quotes-npm-pkg)
![npm](https://img.shields.io/npm/dm/tap-quotes-npm-pkg)
![npm](https://img.shields.io/npm/l/tap-quotes-npm-pkg)

# tap-quotes-npm-pkg

This function will return a random quote or lyric from an array of over 11 (570 to be precise) strings.
WARNING: Some of these quotes and lyrics contain rather rude (NSFW) words. They used to be tweeted every hour on the hour on [this Twitter bot](https://twitter.com/QuotesTap), until Alan Musk cut off my access to the Twitter API.

The Github repo can be found [here](https://github.com/jdm79/tap-quotes-npm-pkg).

The array contains back tick multi-line strings - a different line for each person speaking (see example below). 

The NPM page is [here](https://www.npmjs.com/package/tap-quotes-npm-pkg).

## How to use this package

```console
npm i tap-quotes-npm-pkg
```

```js

const { randomTapQuote } = require("tap-quotes-npm-pkg");

randomTapQuote();
// MARTY: If you were to have something written as your epitaph...
// DAVID: “Here lies David St. Hubbins...and why not?”
// MARTY: You feel that sums up your...your life?
// DAVID: No, ‘s the first thing I could think of.
// MARTY: Oh, I see...
```
