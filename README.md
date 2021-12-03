## Post-install Tasks

After running `install.sh` there are still a couple of things that need to be done.

* Add machine-specific configs as needed. (see Machine-specific Configs below)
* Set up iTerm2 or Alacritty profile (see details below).
* Complete [Brew Bundle][brew-bundle] with `brew bundle install`
* Add personal data to `~/.gitconfig.local`, `~/.vimrc.local`, `~/dotfiles/local/config.fish.local`, and `~/.zshrc.local` as needed.
* After opening Neovim, run [`:checkhealth`][checkhealth] and resolve errors/warnings.
* If using Fish, customize your setup by running the `fish_config` command.