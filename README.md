# Snippety tap

Homebrew formulae for [Snippety](https://snippety.app) tools.

## snippety-migrate

Converts snippets exported from other text expansion apps — TextExpander, aText, Raycast, Rocket
Typist, espanso and Alfred — into a Snippety backup you can import.

```sh
brew install snippety-app/tap/snippety-migrate
```

Then run it with no arguments and it walks you through the migration:

```sh
snippety-migrate
```

Universal binary, macOS 13 or later. The releases live in
[snippety-app/snippety-migrator](https://github.com/snippety-app/snippety-migrator), which also has a
signed and notarized `.pkg` if you would rather not use Homebrew.

## About the formulae

They are generated and pushed by the release script that builds the binaries, so the version, url and
checksum always describe an artifact that exists. Don't edit them by hand — the next release
overwrites the file.
