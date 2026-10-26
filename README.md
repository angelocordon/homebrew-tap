# angelocordon/homebrew-tap

Homebrew formulae for [doppio](https://github.com/angelocordon/doppio), a macOS
utility that keeps your Mac awake for a set time with a live countdown.

```sh
brew install angelocordon/tap/doppio
```

This installs both `doppio` and its short name `dop`. Upgrade with
`brew upgrade doppio`.

## Updating

The [update workflow](.github/workflows/update.yml) regenerates
`Formula/doppio.rb` from the latest stable doppio release every day, and can be
run on demand from the Actions tab. Prereleases are ignored. To update locally,
run `bin/update-doppio` (requires an authenticated `gh`) and commit the result.
