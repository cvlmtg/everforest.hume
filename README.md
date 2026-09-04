# everforest.hume

[Everforest](https://github.com/sainnhe/everforest) for [HUME](https://github.com/cvlmtg/hume)
— a green-based, low-contrast color scheme designed to feel warm and comfortable on the eyes,
inspired by forest colors in fall.

Created by [sainnhe](https://github.com/sainnhe), originally for Vim/Neovim, and ported to
Helix's theme format by the Helix project. This repo brings that same Helix-format theme to
HUME.

Two variants: `everforest_dark` and `everforest_light`.

## Requirements

- HUME 0.12.0 or later.

## Install

With PLUM ([HUME](https://github.com/cvlmtg/hume)'s plugin manager — `(declare-plugin "core:plum")` in `init.scm`):

```
:plum-install-theme cvlmtg/everforest.hume
```

`:plum-update-themes` later pulls the latest version.

### Manual install

```sh
git clone https://github.com/cvlmtg/everforest.hume
cp everforest.hume/themes/*.toml ~/.config/hume/themes/
```

(or symlink the two files instead of copying, to pick up future updates with `git pull`).

## Usage

```
:theme everforest_dark
```

or from `init.scm`:

```scheme
(set-option! "theme" "everforest_dark")
```

Swap in `everforest_light` for the light variant. Tab-complete either name with `:theme <Tab>`.

## License

MIT — see [LICENSE](LICENSE).
