# bspwm-dots
Let's use bspwm window manager for Archlinux.
# bspwm Setup

## install bspwm,Sddm ,Git,vim :
```bash 
sudo pacman -S bspwm sddm git vim
``` 
# What is Sddm?
The Simple Desktop Display Manager (SDDM) is a display manager.

## config Sddm :
```bash 
sudo systemctl enable sddm 
``` 

## clone dot-Config File :
```bash
git clone https://github.com/Komi7/bspwm-dots.git
```
## Packages install :
```bash 
sudo pacman -S --needed - < packages.sh
``` 

**NOTE!** These were made for my computer specifications. So use it at your own risk! 

## Polybar-Theme
```bash
git clone --depth=1 https://github.com/adi1090x/polybar-themes.git
```
• Change to cloned directory and make setup.sh executable -
```bash
cd polybar-themes
chmod +x setup.sh
```
• Run setup.sh and select a style -
```bash
./setup.sh
```

[*] Installing Polybar Themes...

[*] Choose Style -
[1] Simple
[2] Bitmap

[?] Select Option : 1

[*] Installing fonts...
[*] Creating a backup of your polybar configs...
[*] Successfully Installed.

 
• That's it, These themes are now installed on your system.
Note : These themes are like an ecosystem, everything here is connected with each other in some way. So... before modifying anything by your own, make sure you know what you are doing.

• Open the terminal and enter the following command -
```bash
bash ~/.config/polybar/launch.sh
```
• You can add the same command to your WM autostart file to launch the bar on login.
## Launch Polybar
```bash
bash ~/.config/polybar/launch.sh --blocks
```

## Aesthetic VSCode setup ☄️:


### Install required extension

  •
  <a href="https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui">Customize UI</a>

  •
  <a href="https://marketplace.visualstudio.com/items?itemName=antfu.icons-carbon">Carbon Product Icons</a>

### copy config file
```bash
cp misc/vscode/User/settings.json ~/.config/Code/User
```

# Used Stuff
- [Polybar](https://github.com/polybar/polybar) = A fast and easy to use statusbar. 
- [vim](https://www.vim.org/) = A useful text editor that i mostly prefer. 
- [neofetch](https://github.com/dylanaraps/neofetch) = System Fetching tool. 
- [zathura](https://github.com/pwmt/zathura) = A Document Viewer.
- [rofi](https://github.com/davatorium/rofi) = A window switcher, Application launcher and dmenu replacement
- [alacritty](https://github.com/alacritty/alacritty) = Alacritty Terminal Emulator 


***modify ongoing ! ...........🤞***


<h1 align="center">Hi , I'm Shousuke Komi <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
<p align="center">
 <h1 align="center"> <p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?multiline=true&lines=Linux+user+,+Learning+coding">
  </h1>
 
</p>


<div align="center">

  <img  src="https://github.com/Komi7/resources/blob/main/img/grid-snake.svg"
       alt="snake" /></a>
</div>

<details>
  <summary>☎️ contact me</summary>
<div>
  <samp>
    <h2 align="center">😎 you can reach me by:</h2>
    <p align="center">
      <br/>
      <a href="https://t.me/mahmud11507" target="blank"><img align="center"
         src="https://img.shields.io/badge/-Telegram-brightgreen.svg?style=for-the-badge&logo=Telegram&logoColor=white"
         alt="komii" height="30"/></a>
      <a href="https://discord.com/channels/@me/724963674477035561" target="blank"><img align="center"
         src="https://img.shields.io/badge/-Discord-blue.svg?style=for-the-badge&logo=Discord&logoColor=white""
         alt="komii" height="30"/></a>
      <a href="https://instagram.com/shousuke.komii" target="blank"><img align="center"
         src="https://img.shields.io/badge/instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"
         alt="komii" height="30"/></a>
