# Note:
# Work in progress fixing some Issues.
# My-Linux-Configuration-files

![arch](https://user-images.githubusercontent.com/53271289/211332449-7908045c-9db2-4e27-b0fb-5449d37c93a2.png)

It's just my back up files for the theming as I keep breaking my install lol.
If anyone wants to use it they're free to use it.
This is a work in progress and the development will be dry for atleast 3 months.

# Start by updating the system:
```bash
$ sudo pacman -Syyu
```

#Installing paru (AUR Helper):
---------------------------
```bash
$ sudo pacman -S --needed base-devel git 
```
CLoning the Repository:
---------------------------
```bash
$ git clone https://aur.archlinux.org/paru.git
```
```bash
$ cd paru
```
```bash
$ makepkg -si
```
---------


#Installing the required applications:
---------------------------------------
```bash
$ paru -S gnome openbox obmenu-generator obconf nitrogen vscodium-bin kitty polybar conky conky-manager2-git termite gnome-tweaks xfce4 lxappearance python-pywal rofi betterlockscreen zorin-desktop-themes zorin-icon-themes windows-xp-themes-git windows-xp-icons-git pfetch calc networkmanager-dmenu-git kvantum picom 
```
Note: Since I used anarchy installer I already have KDE installed so install plasma if not installed.

#For people who only want openbox:

```bash
$ paru -S openbox obmenu-generator obconf nitrogen polybar conky conky-manager2-git termite lxappearance python-pywal rofi betterlockscreen zorin-desktop-themes zorin-icon-themes calc networkmanager-dmenu-git picom 
```
#Clone the Repository:
---------------------
```bash
$ git clone https://github.com/ColdWistler/My-Arch-Linux-Backupfiles.git 

```
#Finally copying the configurations:
```bash
$ cd My-Arch-Linux-Backupfiles 
$ cd config
$ mv -f * ~/.config 
$ cd ~/My-Arch-Linux-Backupfiles
$ mv Wallpapers ~/Pictures
```

# Setting up polybar:

#Instaling required fonts:
```bash
paru -S ttf-iosevka-lyte-nerd-font ttf-icomoon-feather ttf-material-design-icons siji-git
```
#Cloning from a repository: Credit:adi1090x
```bash
$ git clone --depth=1 https://github.com/adi1090x/polybar-themes.git
$ cd polybar-themes
$ chmod +x setup.sh
$ ./setup.sh
```
# Setting up Rofi:

```bash
$ git clone --depth=1 https://github.com/adi1090x/rofi.git
$ cd rofi
$ chmod +x setup.sh
$ ./setup.sh
```
Use rofi theme selector to switch themes
Note:Copy the files to the theme switcher folder  [/usr/share/rofi/themes/]

[Windows key + Space (Openbox)]

# Optional Applications:
These are applications I prefer so it's optional to install them.

```bash
$ paru -S vlc librewolf-bin discord chromium tor-browser 
```
#Oh My Zsh with Power level 10K

![ospwl10k](https://user-images.githubusercontent.com/53271289/211332329-c228eff4-0f7e-48d5-8ba3-8b1fd3505d31.png)

```bash
$ paru -S zsh oh-my-zsh-git zsh-theme-powerlevel10k-git
```



# Openbox configuration:

#ColorBlocks:
-------------

![pic1](https://user-images.githubusercontent.com/53271289/211317940-573b5402-6f27-46ed-a21c-99492ad03b80.png)

#Cuts:
-------

![pic2](https://user-images.githubusercontent.com/53271289/211318059-8afc8199-4307-4a2d-b98e-02655950cd83.png)

#GrayBlocks:
------------

![pic3](https://user-images.githubusercontent.com/53271289/211318129-27c17b83-82c2-4de0-8294-8e4504794dc8.png)

#Elementary:
------------

![pic4](https://user-images.githubusercontent.com/53271289/211318346-15d462f3-3d1d-4f5d-94ed-4afa02bd7521.png)

#Zorin:
-------

![pic5](https://user-images.githubusercontent.com/53271289/211318439-18845fb9-f0de-4033-adf6-ed6ce2e0e79f.png)

#Themes for Openbox: Credits:(addy-dclxvi)

```bash
$ git clone https://github.com/addy-dclxvi/openbox-theme-collections ~/.themes
```


# Some Important Shortcut keys:
-------------------------------------
Change Polybar: ctrl + Alt + (1-0 & O & k)


Change wallpaper and generate color schemes according to the bar: Windows key + (1-0,O & k)

# Some other themes:

|Openbox|Themes|
|--|--|
|![ob1](https://user-images.githubusercontent.com/53271289/211343893-c86fbac6-d6ce-42b5-8ac6-3b92ed62a1e7.png)|![ob2](https://user-images.githubusercontent.com/53271289/211343900-3c28f926-8907-451e-96d5-da3b58c4b7d2.png)|
|![ob3](https://user-images.githubusercontent.com/53271289/211343916-a4ed8b13-da06-4d25-851b-b27a3b462609.png)|![ob4](https://user-images.githubusercontent.com/53271289/211343929-c19ccad8-e53f-468f-b2c9-319173a50503.png)
|![ob5](https://user-images.githubusercontent.com/53271289/211343936-1fdbfcfa-cf95-4b10-a23b-c56afcf11f06.png)|![ob6](https://user-images.githubusercontent.com/53271289/211343951-3b229637-ed8e-4d28-a712-36aee654f2d3.png)


# Desktop Environments:
=======================



#KDE Plasma:
------------

![pic9](https://user-images.githubusercontent.com/53271289/211326683-cbb6d431-fe76-4e45-a3c6-11e769e49cd0.png) 



#xfce4 (Nostalgia):
-------------------

![pic8](https://user-images.githubusercontent.com/53271289/211318683-51392c21-1a0b-4144-9b5c-aa817a41de30.png)

Switch the themes to Xp and the wallpaper is in the pictures folder. And remove the bottom panel and move the top pannel to the bottom.

#Gnome:
-------
![gnome](https://user-images.githubusercontent.com/53271289/211318851-4a0acfaf-6394-41e4-9272-ac69e3ca124b.png)


======================================================================

Some of the works aren't done by me and are a part of other projects.

Thank you and please let me know if there is any issue with me using these works.

I'm Sorry if I cause any trouble I'm a little new to this.

Hope you enjoy.!!!

=======================================================================

Credits:
1. Adi1090x (Polybar and Rofi)
