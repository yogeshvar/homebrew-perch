# homebrew-pullshelf

Homebrew tap for [Pullshelf](https://github.com/yogeshvar/pullshelf), a pull-down shelf for the Mac.

```
brew install --cask yogeshvar/pullshelf/pullshelf
```

Or tap it first:

```
brew tap yogeshvar/pullshelf
brew install --cask pullshelf
```

Pullshelf is ad-hoc signed and not notarized, so macOS blocks the first launch. The install output explains how to open it (System Settings, Privacy & Security, Open Anyway). Apple Silicon, macOS 13 or later.

The cask in `Casks/pullshelf.rb` is kept in step with each [Pullshelf release](https://github.com/yogeshvar/pullshelf/releases); see `RELEASING.md` in the main repository.

> Pullshelf was called Perch before 0.1.1. If you installed `perch`, run `brew uninstall --cask perch` and then install `pullshelf`; your data moves over automatically.
