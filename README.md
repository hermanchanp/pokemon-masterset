# Pokémon TCG Master Set Checklist

A single-page web app for tracking master sets across any Pokémon TCG set. No install, no build step — open `index.html` in a browser or visit the hosted version.

## Features

- **All sets supported** — dropdown is populated live from the [TCGDex API](https://tcgdex.net), so new sets appear automatically
- **4 languages** — English, Japanese, Simplified Chinese, Traditional Chinese
- **Sections** — cards grouped by type: Pokémon, Trainers & Items, Special Energy, Illustration Rare, Ultra Rare, Special Illustration Rare, Hyper Rare
- **Progress tracking** — checkbox state is saved to localStorage per set, survives page refreshes
- **Print / PDF** — hit the Print button to get a print-ready layout; use your browser's "Save as PDF" option
- **Reset** — clear all checkmarks for the current set

## Usage

Select a language, pick a set from the dropdown, and start checking off cards as you collect them.

## Data source

Card data and images via [TCGDex](https://tcgdex.net) — an open Pokémon TCG API.
