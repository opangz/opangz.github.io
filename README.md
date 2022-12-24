# Owen Pang's Personal Website

[![github pages](https://github.com/opangz/opangz.github.io/actions/workflows/gh-pages.yml/badge.svg)](https://github.com/opangz/opangz.github.io/actions/workflows/gh-pages.yml)
[![powered by Hugo](https://img.shields.io/badge/powered%20by-Hugo-blue)](https://gohugo.io/)
[![theme Anatole](https://img.shields.io/badge/theme-Anatole-blue)](https://github.com/lxndrblz/anatole)
[![MIT License](https://img.shields.io/github/license/opangz/opangz.github.io?color=blue)](https://github.com/opangz/opangz.github.io/blob/main/LICENSE.md)

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

## Updating Theme

To get the latest update of the Anatole theme, run

```
git submodule update --remote --merge
```

