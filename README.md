# EdgeCitadel Homebrew tap

Install the latest stable EdgeCitadel release:

```sh
brew tap EdgeCitadelTeam/edgecitadel
brew trust --tap EdgeCitadelTeam/edgecitadel
brew install edgecitadel
```

Homebrew 6 requires the explicit trust step before it will load a formula from
a non-official tap.

For source builds from the current `main` branch:

```sh
brew install --HEAD edgecitadel
```

Project documentation and release notes are available in the
[EdgeCitadel repository](https://github.com/EdgeCitadelTeam/EdgeCitadel).
