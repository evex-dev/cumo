<div align="center">
  <a href="https://evex.land">
    <img src="https://raw.githubusercontent.com/evex-dev/cumo/main/docs/images/cumo-title.png" width="500" height="auto" alt="Cumo"/>
  </a>
</div>

<hr />

<!--
  [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/honojs/hono/ci.yml?branch=main)](https://github.com/honojs/hono/actions)
  [![GitHub](https://img.shields.io/github/license/honojs/hono)](https://github.com/honojs/hono/blob/main/LICENSE)
  [![npm](https://img.shields.io/npm/v/hono)](https://www.npmjs.com/package/hono)
  [![npm](https://img.shields.io/npm/dm/hono)](https://www.npmjs.com/package/hono)
  [![JSR](https://jsr.io/badges/@hono/hono)](https://jsr.io/@hono/hono)
  [![Bundle Size](https://img.shields.io/bundlephobia/min/hono)](https://bundlephobia.com/result?p=hono)
  [![Bundle Size](https://img.shields.io/bundlephobia/minzip/hono)](https://bundlephobia.com/result?p=hono)
  [![GitHub commit activity](https://img.shields.io/github/commit-activity/m/honojs/hono)](https://github.com/honojs/hono/pulse)
  [![GitHub last commit](https://img.shields.io/github/last-commit/honojs/hono)](https://github.com/honojs/hono/commits/main)
  [![codecov](https://codecov.io/github/honojs/hono/graph/badge.svg)](https://codecov.io/github/honojs/hono)
  [![Discord badge](https://img.shields.io/discord/1011308539819597844?label=Discord&logo=Discord)](https://discord.gg/KMh2eNSdxV)
-->

Play: https://www.typescriptlang.org/play/?#code/PQKhCgAIUgBA7AhgWwKaQMIFdkHsoywDGu8RqADgC6SAAcoCYMgdgyAVDIM8MgkwyC7DICUMrgEwyBzBkDgkYAdTRoFWlQDrygJIZAMhGAxBkBADAWDhwqAB4VcAJxpI0AZwqJymHLkgBvKJDubteyFQCeFdAEUsqHS8gBeSEMqHQBLeABzNTt7LV0acKofADNTdAAlVABHb2CAHgBJeCSdJAAbLx8-QMrfABpIABFEKkQAyCx4AGt4XAB3eAA+a1sYmJyqgC5IIpLy2pc60bHIABMWxGnm1uWAX2iYh3jnNwzs3KoAIVxV6shMieCAbQBdA9jHGld3SABlVqoWEM7QARIYsERyIZDCDIAAfSAg1KhMpYHSoEHvSBHJyJFJpe6oYykQyoQrFHzlf4tIHYjRJeCrYHUwHAwIsoENbZtQKdHr9IYjFYxYI0wzTWaUxBlDmGJbCuzrVpbDZ7LE4r6nQnE+Ck663dqZHWk17quJOb7oAASiEZZR87QAFAAjG4uaYPC5PEFKxAgl4ASgCwyN2l16ARAAUdLhkKFSXlQyTUIMzZ8Tj8bXafGzCSQdKs8gsGlnVvadKnlhqM+giskfEnw-qXHllmNJaVpZ6iVc3XSGUzCY9e7d5QqO+VS+XgZoB8CpznlsNAjYFZAnkVVppIOFIF1UC5cMkZhTO2Vu8Fmy8JafyheRy4N4zNC9+6hGcCrJAJr5puF6zokAeJA+xrmMAD8QFvh+e4HkeJ5zNKC46IYbZgXYkEAIJ9IgoRJIWmSAqUAAqpzkohZTIYYTweC8gypuhwrTPAqAAG4+GhTGQCx7E6Gq+zgCQuo0AAFraZaoPezbtIghguGQkB5EJwQIVK57nD20mzu+g7YHgAB0Ulug0yk0BOSHidO0G6RY+lUYMjrosOzY3hRRmjpAYnZihrlqVRAbTNGsbxmSth6bg+l1g2RJhnqbrkWp7mLKpZ72eAy7DKuMSmZA6LGqgLnmAZjZxQagSmmMyzJLokCOjlroGvBTkXM2QZZcKeWxQVbr6RQQIiY6iA4XhnmWTmTwNS4+k-i4Lwuj1voBgGarLOiRHwLlMXJtJslFRFUU6CV3W3AlZ5JQ05mUWNKGpgJoAQNAcCaCgFD2iogkkjQnXbX2gRDbholjUljpPMs7UrDN0xgqgVALgAcigGJjsKvpQxoACcAAcACMABMmJjPsLwNODpKw2NCNoNMjoAPqTUG-jDI64NjKKrJQ+CkJEjCyMrKjQqMaE2OY-A0ws4LqzTNjnErLsvNrrooQROE0oALLc4gESoFDRBeVrqyQIeaKjdm3GIwTCqgTEuzLTbajAMAm3JKh4AO5AgAIRoA+UqAEJmDS0IAFwkCMwgCXDIAPwyADIMgBeboA+K6AOoMgD6DN7waQLjAAMADsruO4AVwyAPUMzCAJ0MfCMIAqwyAJUMoeAHsMgDDDHw4eAKoJ8jJwALKnqfgEAA

Cumo - _**means cloud☁ in Japanese**_ - is a small, simple, and ultrafast multi request handler on single endpoint built on Web Standards.

Fast, but not only fast.
Inspired by [Hono](https://github.com/honojs/hono).

```ts
import { Hono } from "hono"
import * as cumo from "cumo"
import cumoMiddleware from "cumo/hono"

const app = new Hono()

app.use("/api", cumoMiddleware(
  // TODO
))

export default app
```

## Quick Start

```bash
npm i cumo
bun i cumo
deno add npm:cumo
```

## Features

- **Ultrafast** 🚀 - Optimized for single request.
- **Lightweight** 🪶 - The size is minimal so that it can be used in Edge.
- **Multi-runtime** 🌍 - We provide a [Hono](https://hono.dev) integration.
- **Delightful DX** 😃 - Super clean APIs. First-class TypeScript support. Now, we've got "Types".

## Documentation

Coming soon...

## Communication

[X](https://x.com/amex2189) and [Discord channel](https://discord.gg/evex) are available.

## Contributing

Contributions Welcome! You can contribute in the following ways.

- Create an Issue - Propose a new feature. Report a bug.
- Pull Request - Fix a bug and typo. Refactor the code.
- Share - Share your thoughts on the Blog, X, and others.
- Make your application - Please try to use Hono.

For more details, see [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md).

## Contributors

Thanks to [all contributors](https://github.com/evex-dev/cumo/graphs/contributors)!

## Authors

EdamAme-x <https://github.com/EdamAme-x>

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
