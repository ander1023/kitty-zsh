https://www.jetbrains.com/lp/mono/

## archlinux
```
sudo pacman -S ttf-jetbrains-mono
```

## centos8 
```
sudo mkdir -p /usr/share/fonts/jet-fonts

unzip JetBrainsMono-*.zip
sudo cp JetBrainsMono-*/fonts/ttf/*.ttf /usr/share/fonts/jet-fonts/


fc-cache -fv
```