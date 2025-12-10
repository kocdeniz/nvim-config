# My Neovim Setup

This is my personal Neovim configuration that I use across my Macs.

## Getting Started

First, you'll need Neovim installed:
```bash
brew install neovim
```

Then grab this config:
```bash
git clone https://github.com/kocdeniz/nvim-config.git ~/.config/nvim
```

Just run `nvim` and everything should work. Plugins will install automatically the first time.

## What's Inside

- `init.lua` - where all the magic happens
- `lazy-lock.json` - keeps plugin versions in sync

## Daily Use

I just use `nvim filename` to edit files. The setup uses lazy.nvim for plugins because it's fast and reliable.

Update plugins when needed with `:Lazy update` inside nvim.

Pull latest changes with `git pull` from the config directory when I make updates.

That's pretty much it - keep it simple!
