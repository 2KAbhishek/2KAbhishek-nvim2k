<div align = "center">

<h1><a href="https://2kabhishek.github.io/nvim2k">nvim2k</a></h1>

<a href="https://github.com/2KAbhishek/nvim2k/blob/main/LICENSE">
<img alt="License" src="https://img.shields.io/github/license/2kabhishek/nvim2k?style=flat&color=eee&label="> </a>

<a href="https://github.com/2KAbhishek/nvim2k/graphs/contributors">
<img alt="People" src="https://img.shields.io/github/contributors/2kabhishek/nvim2k?style=flat&color=ffaaf2&label=People"> </a>

<a href="https://github.com/2KAbhishek/nvim2k/stargazers">
<img alt="Stars" src="https://img.shields.io/github/stars/2kabhishek/nvim2k?style=flat&color=98c379&label=Stars"></a>

<a href="https://github.com/2KAbhishek/nvim2k/network/members">
<img alt="Forks" src="https://img.shields.io/github/forks/2kabhishek/nvim2k?style=flat&color=66a8e0&label=Forks"> </a>

<a href="https://github.com/2KAbhishek/nvim2k/watchers">
<img alt="Watches" src="https://img.shields.io/github/watchers/2kabhishek/nvim2k?style=flat&color=f5d08b&label=Watches"> </a>

<a href="https://github.com/2KAbhishek/nvim2k/pulse">
<img alt="Last Updated" src="https://img.shields.io/github/last-commit/2kabhishek/nvim2k?style=flat&color=e06c75&label="> </a>

<h3>Your Personalized Development Environment ❤️👨‍💻</h3>

<figure>
  <img src= "images/screenshot.jpg" alt="nvim2k Demo">
  <br/>
  <figcaption>nvim2k screenshot</figcaption>
</figure>

</div>

## What is this

Handcrafted `neovim` configs for the ultimate CLI dev experience, completely in `lua`, [video walkthrough](https://youtu.be/WfhylGI_F-o)

## Inspiration

Have been using `neovim` as my editor of choice for a while, with the introduction of vim 9 and the breaking changes to `viml` I decided to rewrite my configs in pure `lua`.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of `neovim`
- Python proivder is necessary for some operations: `pip install neovim`
- To use nvim2k for notes, make sure to add `export NOTES_DIR=your/notes/path` as a env var [video with more info](https://youtu.be/FP7sQhc8kek)

## Getting `nvim2k`

To get `nvim2k`, follow these steps:

```bash
git clone https://github.com/2kabhishek/nvim2k
# On Linux and Mac
ln -sfnv $PWD/nvim2k $HOME/.config/nvim
cmd /c mklink /d %LOCALAPPDATA%\nvim %CD%\nvim2k
```

```powershell
# On Windows
New-Item -ItemType SymbolicLink -Path "$env:LOCALAPPDATA\nvim" -Target "$PWD\nvim2k" -Force
```

## Plugins

For a list of plugins, see the [plugins file](./lua/plugins/list.lua)

Hit the ⭐ button if you found this useful.

## More Info

Looking for my `zsh` and other `cli` configs? See [Dotfiles](https://github.com/2kabhishek/Dotfiles)

Looking for my tmux configs? See [tmux2k](https://github.com/2kabhishek/tmux2k)

Want the CLI experience on your Android too? Have a look at [Oh-My-Termux](https://github.com/2kabhishek/Oh-My-Termux)

<div align="center">

<a href="https://github.com/2KAbhishek/nvim2k">Source</a> | <a href="https://2kabhishek.github.io/nvim">Website</a>

</div>
