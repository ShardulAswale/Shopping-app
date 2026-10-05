# Shopping App

React shopping-cart prototype with a fixed product catalogue.

## How it works

`App.js` manages products and cart state, persists the cart in browser local storage and routes to a checkout summary. `PayNow` uses react-to-print to print the displayed summary.

## Usage

Requires Node.js and npm. From the repository root:

```sh
npm install
npm start
```

Open `http://localhost:3000`. `npm run build` creates static files in `build/`.

## Notes

Checkout displays and prints a summary; it does not process payments. No database or application backend is included. The current `deploy` script calls `master` rather than the installed `gh-pages` tool and needs correction before use.
