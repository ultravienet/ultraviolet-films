# Ultraviolet — Field Notes

A public gallery for six Remotion films about client-side validation on
Bitcoin:

**Live site:** [ultraviolet-films.pages.dev](https://ultraviolet-films.pages.dev/)

1. Ultraviolet compared with Shielded CSV, Taproot Assets, and RGB
2. Shielded client-side validation
3. Taproot Assets
4. RGB
5. Ultraviolet benchmarks
6. Formal verification, its trust boundary, and the Collatz/Lean incident

The site is static and deploys to Cloudflare Pages. Videos are optimized H.264
MP4 files with fast-start metadata for progressive native browser playback.

## Local development

```sh
npm install
npm run dev
```

## Deploy

```sh
npm run deploy
```

Film source is tracked in
[`ultravienet/ultraviolet` PR #17](https://github.com/ultravienet/ultraviolet/pull/17).
