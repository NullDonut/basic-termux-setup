# basic-termux-setup
A basic termux file that configures fastest repo to download and also configures nerdfont as well as python with opencv2

## Installation 

#### 1. Update Packages and Setup Storage

> Allow Storage
```
termux-setup-storage
```
 upgrade -y
```
#### 2. Copy this repository
```
pkg install wget
```

> Run the script 
```
wget https://github.com/IamShivanshCoder/basic-termux-setup/raw/main/basic.sh && chmod +x basic.sh && ./basic.sh
```


#### 3. Nerd Font Installation 

By default, JetBrainsMono is installed , Press 1 > 12 in nerd font installer


### Final Steps

#### 4. NVim Configuration 

1. Enter Nvim
``` nvim```
2. Let it install and Go To Lazy Extras by pressing x and enable language:python by pressing x on circle in front of its name
3. Exit Neovim
4. Re-Enter Neovim and press : to enter command mode and type the following command
```
LSPInstall pyright
```
5.Exit NeoVim

#### 4. OpenCV2 Usage (Optional)

1.In a new terminal type to start display service 
```
termux-x11 :1 -xstartup "fluxbox"&
```

2.Run the file
```
DISPLAY=:1 python name.py
```
