# Configurations of my Dev Environment

- [Powerlevel10k](https://github.com/romkatv/powerlevel10k)
- [OhMyZsh](https://github.com/ohmyzsh/ohmyzsh)
- [OhMyZsh plugins setup](https://gist.github.com/liamwilk/3a8b19bc9f862f16c5836deaecbdb52b)
- [Catpuccin Alacritty Mocca](https://github.com/catppuccin/alacritty)
- [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

## Use my actual Alacritty settings
- Make the alacritty directory in .config
  ```
  mkdir $HOME/.config/alacritty
  ```

- Copy the `alacritty.toml` of the repo into the config of alacritty
  ```
  cp ./alacritty.toml $HOME/.config/alacritty
  ```

## Use my actual Tmux settings
- Copy the `.tmux.conf` of the repo into the home directory
  
  ```
  cp ./.tmux.conf $HOME
  ```
>[!IMPORTANT]
>
>It's necessary that after you do this, press Ctrl-a and then Shift-I to install all the necessary TPM plugins