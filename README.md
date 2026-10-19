# homebrew-perch

Homebrew tap for [Perch](https://github.com/yogeshvar/perch), a pull-down shelf for the Mac.

```
brew install --cask yogeshvar/perch/perch
```

Or tap it first:

```
brew tap yogeshvar/perch
brew install --cask perch
```

Perch is ad-hoc signed and not notarized, so macOS blocks the first launch. The install output explains how to open it (System Settings, Privacy & Security, Open Anyway). Apple Silicon, macOS 13 or later.

The cask in `Casks/perch.rb` is kept in step with each [Perch release](https://github.com/yogeshvar/perch/releases); see `RELEASING.md` in the main repository.
