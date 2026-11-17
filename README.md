# Shell Lesson Data

A collection of files used for shell (command line) lessons, plus an interactive data explorer.

## 📊 Gapminder Explorer

An interactive HTML page for exploring the [Gapminder](https://swcarpentry.github.io/r-novice-gapminder/) dataset. Filter by **continent** and **year**, view a **summary table** of the filtered data, and see **charts** for life expectancy and population by country.

### 🌐 Live site (GitHub Pages)

**<https://emmanovak112.github.io/shell-lesson-data/gapminder_explorer.html>**

### Run it locally

The page is fully self-contained — no server needed. Just open the file in a browser:

```bash
open gapminder_explorer.html        # macOS
xdg-open gapminder_explorer.html    # Linux
```

> **Note:** The page fetches its dataset from `swcarpentry.github.io` and loads Chart.js from a CDN, so an internet connection is required when the page is open.

## How the site is published

This repository is served by **GitHub Pages** from the root of the `main` branch. After pushing changes to `main`, the live site updates automatically (usually within a minute or two).

| File | Description |
|------|-------------|
| `gapminder_explorer.html` | The interactive Gapminder explorer (the live page) |
| `gapminder_data.csv` | The raw Gapminder dataset |
| `README.md` | This file |

## Contributing

Pushing to `main` will update the live Pages site. Make sure to add, commit, and push your changes:

```bash
git add .
git commit -m "describe your change"
git push origin main
```
