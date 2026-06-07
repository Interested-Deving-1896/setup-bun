[update-readmes]   Mode: rewrite — migrating to template structure...
# setup-bun

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/setup-bun)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/setup-bun.git
cd setup-bun
```

## Usage


```yaml
- uses: oven-sh/setup-bun@v2
```

By default, if no version is specified, the action will:

1. Check `package.json` for the `packageManager` field (e.g., `"packageManager": "bun@1.0.25"`)
2. If `packageManager` doesn't exist, check `package.json` for `engines.bun`
3. If neither exists or `package.json` is not found, use `latest`

You can also explicitly specify a version:

```yaml
- uses: oven-sh/setup-bun@v2
  with:
    bun-version: latest
```

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/setup-bun`](https://github.com/Interested-Deving-1896/setup-bun) and mirrored through:

```
Interested-Deving-1896/setup-bun  ──►  OpenOS-Project-OSP/setup-bun  ──►  OpenOS-Project-Ecosystem-OOC/setup-bun
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/setup-bun/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
