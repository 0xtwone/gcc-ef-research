# GCC Ethereum Independent Research Program

A bilingual website introducing the Ethereum Independent Research Program, research directions, available support, the research ecosystem, and the application process.

## Applications

Applications are collected through GCC's LimeSurvey service:

- English: https://survey.gccofficial.org/ethereum-research?lang=en
- 简体中文: https://survey.gccofficial.org/ethereum-research?lang=zh-Hans

The form has nine bilingual questions covering name/team, contact email, research direction, project title, research value, approach and timeline, open outputs, support needs, and team experience. The website's application links follow its selected language. The website itself does not store application responses.

## Run locally

Requires Node.js 18 or later. No dependency installation is required.

```sh
npm run dev
```

Open http://127.0.0.1:8765. To choose another port:

```sh
PORT=9000 npm run dev
```

## Deployment

Serve the `dist/` directory as a static website. On Vercel, use Framework Preset `Other`, repository root as Root Directory, an empty Build Command, and Output Directory `dist`.

## Features

- English and Chinese page content
- Expandable research directions
- A worldwide participation FAQ
- Official organization logos and a transparent circle favicon
- Direct links to GCC's active application form
- Responsive layouts and keyboard-accessible controls

## Brand assets

- GCC wordmark: https://www.gccofficial.org/
- GCC circle mark and ETH Hub logo: supplied by the project owner
- Ethereum Foundation logo: https://ethereum.org/foundation/
- OpenBuild logo: https://logo.openbuild.xyz/
- GitHub icon: https://github.com/primer/octicons/blob/main/icons/mark-github-24.svg

Official logos retain their source artwork and proportions. Brand assets remain subject to their owners' rights.

The hero artwork is original, generated using the built-in imagegen tool. Visual reference: https://ethereum.foundation/infinitegarden. Prompt summary: botanical garden, lavender sky, mint and teal foliage and water, a delicate butterfly, a faceted diamond among plants, and quiet space for text.

Internal documents, recordings, source notes, and credentials are excluded from this repository.
