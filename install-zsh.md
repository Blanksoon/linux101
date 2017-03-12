# Install zsh and theme oh my themes

### Zsh and oh-my-theme

```
sudo apt-get install -y zsh git
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

which zsh
sudo chsh
/usr/bin/zsh
restart or logout user
```

### Change theme
```
sudo vi ~/.zshrc
ZSH_THEME="agnoster"
```


[font Inconsolata](https://github.com/powerline/fonts/blob/master/Inconsolata/Inconsolata%20for%20Powerline.otf)

```
sudo cp Inconsolata\ for\ Powerline.otf /usr/share/fonts
```

```
color
background: #17303E
yellow: #FAEF0A
green: #41F732
blue: #3465A4
```