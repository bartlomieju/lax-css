# lax-css

CSS, SCSS, and Less formatter that never reinterprets your styles.
Usable as a Rust library or as a dprint plugin.

Source of truth: https://github.com/bartlomieju/lax (monorepo, `crates/lax-css`).
This repo hosts the published dprint Wasm plugin releases.

## Usage (dprint)

```jsonc
{
  "plugins": ["https://plugins.dprint.dev/bartlomieju/lax-css-0.2.4.wasm"]
}
```