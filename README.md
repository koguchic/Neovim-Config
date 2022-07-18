# Koguchi's Neovim Config

This config is forked from Neovim-from-scratch by LunarVim.  It contains many plugins and default keymaps/options that enable Neovim to have a full IDE experience.

## Try out this config

Make sure to remove or move your current `nvim` directory

### Installing Neovim

I find installing using the AppImage the easiest.  For some reason using apt-get was giving me the wrong version of Neovim. 
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
curl -LO https://github.com/neovim/neovim/releases/download/nightly/nvim.appimage
chmod u+x nvim.appimage
sudo mv nvim.appimage /usr/local/bin/nvim
```

**IMPORTANT** Requires [Neovim v0.8.0]](https://github.com/neovim/neovim/releases).  [Upgrade](#upgrade-to-latest-release) if you're on an earlier version. 
```
git clone https://github.com/koguchic/Neovim-Config.git ~/.config/nvim
```

Run `nvim` and wait for the plugins to be installed 

**NOTE** (You will notice treesitter pulling in a bunch of parsers the next time you open Neovim) 

## Get healthy

Open `nvim` and enter the following:

```
:checkhealth
```

---

> The computing scientist's main challenge is not to get confused by the complexities of his own making. 

\- Edsger W. Dijkstra
