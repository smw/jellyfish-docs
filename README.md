# Jellyfish docs

[![pages-build-deployment](https://github.com/jellyfish-dev/jellyfish-docs/actions/workflows/build_pages.yml/badge.svg)](https://github.com/jellyfish-dev/jellyfish-docs/actions/workflows/pages/pages-build-deployment)

The docs for the [Jellyfish](https://github.com/jellyfish-dev/jellyfish).
You can read the docs here: https://jellyfish-dev.github.io/jellyfish-docs/

## Installation

```
npm install
```

## Local Development

```
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Versioning

We follow [the versioning system provided by docusaurus](https://docusaurus.io/docs/versioning)

To create a new docs version:
* make sure that `sidebars.js` and files inside `docs/` directory are up-to-date and ready to be frozen
* create a new directory `versioned_docs/version-1.0.0`
* run `npm run docusaurus docs:version 1.0.0`

## Copyright and License

Copyright 2023, [Software Mansion](https://swmansion.com/?utm_source=git&utm_medium=readme&utm_campaign=jellyfish)

[![Software Mansion](https://logo.swmansion.com/logo?color=white&variant=desktop&width=200&tag=membrane-github)](https://swmansion.com/?utm_source=git&utm_medium=readme&utm_campaign=jellyfish)

Licensed under the [Apache License, Version 2.0](LICENSE)
