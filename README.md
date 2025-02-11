Minimal nvim config for installing molten.nvim plugin nvim-config for jupyter like experience inside neovim.

Steps to install:

1. Follow instructions (end-to-end) to create a python pip virtual env (https://github.com/benlubas/molten-nvim/blob/main/docs/Virtual-Environments.md)
2. Install kitty for linux or wezterm if you're using windows (molten works best with these terminals)
3. Install packages needed for lua-5.1:
  4. sudo pacman -S yay
  5. yay -S readline6 ncurses5-compat-libs
6. Install lua and related packages: mamba install -c conda-forge lua=5.1 luajit luarocks
7. If you have ~/.config/nvim then back it up and delete it. If you don't have it, proceed
8. Install this config: git clone https://github.com/mg104/minimal-jupynium-and-molten-nvim-config.git
9. Move this config to your nvim config folder: mv minimal-jupynium-and-molten-nvim-config.git ~/.config/nvim
10. Run: nvim (things will get set up automatically)
