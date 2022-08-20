<h1 align="center">ColorStrip</h1>
<p align="center">Color strip generator</p>
<p align="center"><a href="https://github.com/info-mono/colorstrip"><img src="https://user-images.githubusercontent.com/43980777/185734792-4ad807a9-e5b9-4ede-9536-52a849cfaeee.png"></a></p>
<p align="center">
  <a href="https://github.com/info-mono/colorstrip/blob/main/LICENSE"><img src="https://img.shields.io/github/license/info-mono/colorstrip?labelColor=383838&color=585858&style=for-the-badge" alt="License: GPL-3.0"></a>
  <a href="https://gist.github.com/NNBnh/9ef453aba3efce26046e0d3119dab5a7#development-completed"><img src="https://img.shields.io/badge/development-completed-%23585858.svg?labelColor=383838&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></a>
</p>

## 💡 About

<img align="right" src="https://user-images.githubusercontent.com/43980777/185737381-12f63626-ca8a-4200-8c3d-979d7ee0f40c.png">

**ColorStrip** is a tool to generate color strip (for e.g: fetch tool) written in POSIX-shell.

Try it:

```sh
sh -c "$(curl -fsLS https://info-mono.github.io/colorstrip)"
```

```sh
sh -c "$(curl -fsLS https://info-mono.github.io/colorstrip)" -- <options>
```

You can just `curl` some pre-made colorstrip:

```sh
curl -fsLS https://info-mono.github.io/colorstrip/<file>
```

E.g:

```sh
curl -fsLS https://info-mono.github.io/colorstrip/block3
```

> **Note** The full list of pre-made colorstrip files can be found [here](https://github.com/info-mono/colorstrip/tree/main/docs).

## 🚀 Setup

### 🧾 Dependencies

- [POSIX compliance shell (`sh`, `bash`, `zsh`, ...)](https://wikipedia.org/wiki/Unix_shell)

### 📥 Installation

#### 🔧 Manually

Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/info-mono/colorstrip/main/bin/colorstrip > ~/.local/bin/colorstrip
chmod +x ~/.local/bin/colorstrip
```

Option 2: using `git`

```sh
git clone https://github.com/info-mono/colorstrip.git ~/.local/share/colorstrip
ln -s ~/.local/share/colorstrip/bin/colorstrip ~/.local/bin/colorstrip
```

#### 📦 Package manager

For [Bpkg](https://github.com/bpkg/bpkg) user:

```sh
bpkg install info-mono/colorstrip
```

For [Basher](https://github.com/basherpm/basher) user:

```sh
basher install info-mono/colorstrip
```

## ⌨️ Usage

Run `colorstrip` in the terminal:

```sh
colortest <options>
```

```console
Options:
  -h, --help               Print this help message
  -s, --string <string>    Set print string
  -m, --modes <modes>      Set modes list (normal, bright, bold, both)
  -c, --colors <colors>    Set colors list (0, 1, 2, 3, 4, 5, 6, 7)
  -t, --transition         Enable transition
  -T, --no-transition      Disable transition
```

> **Note** List are separated by space.

## 💌 Credits

Special thanks to:
- [**Shell Cheatsheet**](https://github.com/esamattis/shell-cheatsheet) by [Esa-Matti Suuronen](https://github.com/esamattis)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/info-mono"><code>@info-mono</code></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></a></p>
