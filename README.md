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

This tap tracks all published releases (including alpha and beta). The formula is automatically updated whenever a new version is published to npm.

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
