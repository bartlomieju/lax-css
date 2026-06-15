# lax-css

CSS, SCSS, and Less formatter that never reinterprets your styles. Usable as a Rust library or as a dprint plugin.

> **Source of truth: the [`lax`](https://github.com/bartlomieju/lax) monorepo
> (`crates/lax-css`).** This repository only hosts the published dprint Wasm
> plugin releases; it carries no source of its own.

## Use as a dprint plugin

```jsonc
// dprint.json
{
  "plugins": ["https://plugins.dprint.dev/bartlomieju/lax-css-0.2.4.wasm"]
}
```

Or run `dprint config add bartlomieju/lax-css` to pull in the latest version.
