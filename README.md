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

Cumo - _**means cloud☁ in Japanese**_ - is a small, simple, and ultrafast validator built on Web Standards. It works on any JavaScript runtime: Cloudflare Workers, Fastly Compute, Deno, Bun, Vercel, AWS Lambda, Lambda@Edge, and Node.js.

Fast, but not only fast.
Inspired by [Hono](https://github.com/honojs/hono).

```ts
import * as c from "cumo"

const pageSchema = c.query({
  text: c.string(),
  page: c.int().min(0)
})
```

Note: In many frameworks, the variable `c` is a reserved word, so we use `x` here.

## Quick Start

```bash
npm i cumo
bun i cumo
deno add npm:cumo
```

## Features

- **Ultrafast** 🚀 - Optimized for request validation.
- **Lightweight** 🪶 - The size is minimal so that it can be used in Edge.
- **Multi-runtime** 🌍 - Works on Cloudflare Workers, Fastly Compute, Deno, Bun, AWS Lambda, Lambda@Edge, or Node.js. The same code runs on all platforms.
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
