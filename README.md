# GCC × EF Research — website concept

A bilingual concept website for the Ethereum Independent Research Program. It combines a garden-inspired visual direction with research tracks, support resources, a collaboration network, and a local proposal drafting experience.

This repository contains a design preview. It is not an official announcement of a confirmed GCC–EF partnership or a live application portal.

## Run locally

Requires Node.js 18 or later. No dependencies or installation step.

```sh
npm run dev
```

Open http://127.0.0.1:8765. To choose another port:

```sh
PORT=9000 npm run dev
```

The `dist/` directory can also be served directly by any static website host. Uploading to GitHub does not deploy the site.

## Features

- English and Chinese page content
- Original garden illustration and official GCC wordmark
- Expandable research directions and FAQs
- Proposal draft form with local text-file download
- Responsive layouts and keyboard-accessible controls

Proposal inputs remain in page memory. No backend, analytics, external submission, or data storage is connected.

## Files

- `dist/index.html`: page structure, content, translations, and interactions
- `dist/garden.css`: garden visual direction and responsive styles
- `dist/garden-hero.png`: original hero artwork
- `dist/gcc-logo.webp`: official GCC wordmark
- `server.mjs`: local static preview server

## Visual sources

Official logo: [GCC website](https://www.gccofficial.org/), downloaded from its existing header asset. The logo retains its original artwork, color, and proportions. Official [brand materials](https://www.gccofficial.org/static/GCC_Logo_PNG.zip) are available on GCC’s website. Brand assets remain subject to their owners’ rights.

Visual reference: [Ethereum Foundation Infinite Garden](https://ethereum.foundation/infinitegarden). The hero is original artwork generated using the built-in imagegen tool, rather than a copied EF illustration. Prompt summary: botanical garden, lavender sky, mint and teal foliage and water, a delicate butterfly, a faceted diamond among plants, and quiet space for text.

## Before launch

Confirm partnership wording, mentor names and roles, official brand usage, support terms, research briefs/RFPs, and application channels. Current copy describes GCC as the program initiator and coordinator and discussions with relevant EF teams as ongoing. No funding amount, mentor appointment, or university partnership is promised by this demo.

Internal documents, meeting recordings, transcripts, and source notes are excluded from this repository.

## Updated brand assets

- ETH Hub logo: official SVG supplied by the project owner.
- OpenBuild logo: black SVG from https://logo.openbuild.xyz/ (its linked public Google Drive brand folder).
- GitHub source-link icon: https://github.com/primer/octicons/blob/main/icons/mark-github-24.svg, from the official Primer Octicons collection.
- Browser favicon: circle mark supplied by the project owner, cropped and scaled without changing the artwork.
