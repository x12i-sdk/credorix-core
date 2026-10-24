# @x12i/credorix-core usage example

Core contracts, schemas, errors, and security helpers for Credorix.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `1.5.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Core contracts, schemas, errors, and security helpers for Credorix.
- A Credorix integration needs to reuse the capabilities of @x12i/credorix-core inside a larger application.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/credorix-core)
- [Implementation monorepo](https://github.com/x12i/credorix)
- [Reviewed package source](https://github.com/x12i/credorix/tree/860e0eab139c54e2126a233d8c7b660c2390d3f4/packages/core)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
