# Homebrew tap for Arcflux

Homebrew tap publishing the Arcflux CLI and related developer tools.

## Install

```sh
brew install arcflux-ai/tap/arcflux
```

The first time you run that command, Homebrew auto-taps this repo (`arcflux-ai/homebrew-tap` — the `homebrew-` prefix is implicit) and installs the formula in one step.

## Formulae

* [`arcflux`](Formula/arcflux.rb) — the [`arcflux` CLI](https://github.com/arcflux-ai/cli)

## How this tap is maintained

Formulae land here automatically: every tagged release of [`arcflux-ai/cli`](https://github.com/arcflux-ai/cli) runs [GoReleaser](https://goreleaser.com), which commits the updated `Formula/<name>.rb` to this repo. Do not edit formulae here by hand — changes belong in the source repo's `.goreleaser.yaml`.

## License

[MIT](LICENSE)
