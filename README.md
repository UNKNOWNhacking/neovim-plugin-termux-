# neovim-plugin-install
Install neovim And neovim Plugin 


* 1). Your Termux Package Update And Requirements Tools Install
```
apt update -y && apt upgrade -y && apt install git python nodejs neovim wget -y
```
* 2). Create A Config Folder
```
mkdir -p .config/nvim
```
* 3). Install A Config Code
```
wget https://raw.githubusercontent.com/brxxlstxrs/VSCode/main/init.vim && mv init.vim .config/nvim
```
* 4). Install A Plugin
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
* 5). Open A Install Plugin 
```
nvim .config/nvim/init.vim
```
* 6). You Enter : PlugInstall
```
:PlugInstall
```

neovim Installed Successfully 
Now Start Your Coding

# Subscribe
```
https://youtube.com/channel/UCupIogax268Qq6kk_XTGf0A
```
