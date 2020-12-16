# Requirement

## On Mac

```sh
brew tap bramstein/webfonttools
brew update
brew install woff2

brew install fontforge --with-python
brew install eot-utils
gem install fontcustom
```

## FAQ

Q: Error: invalid option: --with-python

A:

```sh
brew tap bramstein/webfonttools
brew install woff2 sfnt2woff eot-utils
brew install --cask fontforge
sudo gem install fontcustom
```

- and edit your PATH to include FontForge path: `/Applications/FontForge.app/Contents/Resources/opt/local/bin`
