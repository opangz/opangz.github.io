
## Prerequisites (macOS)

Update Homebrew
```
brew update && brew upgrade && brew cleanup
```

Install Hugo (extended edition)
```
brew install hugo
```

## Building

To locally build the site, run the following. The option `-D` includes drafts.

```
hugo server -D
```

## Publishing

Publishing creates the entire static site in `public`. This typically doesn't include drafts.

```
hugo
```