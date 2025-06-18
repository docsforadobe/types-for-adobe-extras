# Officially Unsupported Types for the Adobe API

## Contents

- Premiere Pro
  - QE DOM

## Prerequisites

Install [Node.js](https://nodejs.org/en/download/) and [TypeScript](https://www.typescriptlang.org/#download-links) and git.

## Example Usage in Premiere Pro

```
/// <reference path='node_modules/types-for-adobe-extras/Premiere/12.0/qeDom.d.ts' />
```

## Publish New Versions

To publish a new version of this project on npm for use in projects, please follow the steps below:

**1. Auth and Access**

- Ensure you are logged in to your npmjs.com account with `npm login` and follow the prompts to complete your login
- Ensure your npmjs.com account has access to publish to the npm package, if not, reach out to an admin for access

**2. Version and Publish**

- Version up the `package.json`
- Run `npm publish`
- Push the commit with the new version to GitHub

## More typings

- [Types for Adobe](https://github.com/bbb999/types-for-adobe)
- [Adobe's offical typings](https://github.com/Adobe-CEP/Samples/tree/master/TypeScript/typings)
- [BrightShadow/CSInterface-TS](https://github.com/BrightShadow/CSInterface-TS)
