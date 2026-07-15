# homebrew-tap

Homebrew tap for [JS Recon](https://github.com/shriyanss/js-recon) — a JavaScript reconnaissance tool for mapping API endpoints and analyzing client-side security issues in modern web applications.

## Installation

```bash
brew tap shriyanss/tap
brew install js-recon
```

## Updating

```bash
brew update
brew upgrade js-recon
```

## Channels

`js-recon` always tracks the latest **stable** release. It is automatically updated whenever a new stable version is published to npm.

For the latest alpha or beta prerelease, install the corresponding versioned formula instead:

```bash
brew install shriyanss/tap/js-recon@alpha
brew install shriyanss/tap/js-recon@beta
```

These formulas are keg-only (they install the same `js-recon` binary name as the
stable formula, so they don't link into the shared `bin/` automatically) — see
`brew info js-recon@alpha` / `brew info js-recon@beta` for how to run them.

For the latest alpha or beta build via npm instead:

```bash
npm i -g @shriyanss/js-recon@alpha
npm i -g @shriyanss/js-recon@beta
```

## Browser requirement

The `lazyload` subcommand (and `run` pipelines that use it) require a Chromium-based browser at runtime. After installing via Homebrew, run `brew info js-recon` for setup instructions.

Subcommands that work without a browser: `strings`, `map`, `analyze`, `report`, `endpoints`, `mcp`, `cs-mast`, `refactor`, `sourcemaps`.

## Documentation

Full documentation at [js-recon.io](https://js-recon.io).

## License

MIT
