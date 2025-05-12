# .dotfiles

most of it already configured, just download 0XProto nerd font from : https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/FiraCode.zip

or copy this into your terminal

```
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/FiraCode.zip \
&& cd ~/.local/share/fonts \
&& unzip FiraCode.zip \
&& rm FiraCode.zip \
&& fc-cache -fv
```

then change your terminal fonts
i'm using default xfce-terminal so thats located in "Edit > Preferenced > Appearance" 
