# Salary Calculator

A simple, client-side salary calculator that converts salaries between currencies and time periods. Runs entirely in the browser — no backend or build step required.

![License: MIT](https://img.shields.io/badge/license-MIT-blue)

## Live Demo

If GitHub Pages is enabled for this repository, the calculator is available at:

```
https://<username>.github.io/salary/
```

## Features

- Convert salaries between hourly, daily, monthly, and yearly rates
- Live currency conversion between GBP, EUR, and USD
- Save and review multiple results locally (session storage)
- Dark / light mode support via `prefers-color-scheme`
- Fully responsive UI

## Usage

Open `index.html` in any modern web browser, or use the live GitHub Pages link above.

1. Enter an amount
2. Select a currency and time period
3. Click **Calculate**
4. Optionally click **Save Result** to store the calculation for this session

## Local Development

No build tools required. Simply open `index.html` in a browser, or serve the folder with any static server:

```bash
npx serve .
```

## GitHub Pages Setup

To publish this calculator as a GitHub Page:

1. Go to **Settings → Pages** in the repository
2. Under **Source**, select **Deploy from a branch**
3. Choose the branch (e.g. `main`) and `/root` (or `/docs` if configured)
4. Click **Save**

The site will be available at `https://<username>.github.io/salary/`.

## License

MIT
