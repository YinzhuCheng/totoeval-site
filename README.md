# TotoEval dataset website

This repository hosts the official (English-language) dataset website for the accompanying paper:

**TotoEval: A Dataset for Evaluating LLM Reasoning**

## Repository structure

- `index.html`: static homepage (no build system)
- `data/TotoEval.zip`: dataset archive served as a direct download link

## Deployment (Cloudflare Pages)

This site is intentionally a pure static website:

- No package managers
- No build steps
- Relative paths only (Cloudflare Pages compatible)

For Cloudflare Pages, set:

- **Build command**: *(none)*
- **Build output directory**: `/`

## Updating the dataset

Replace `data/TotoEval.zip` with the updated archive when releasing new versions of the dataset.
