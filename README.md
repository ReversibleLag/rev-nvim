```
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt upgrade
sudo apt install make gcc ripgrep unzip git xclip neovim
```
Install Oh-My-ZSH
https://github.com/ohmyzsh/ohmyzsh
```
sudo apt install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```
mkdir ~/.config
git clone https://github.com/ReversibleLag/rev-nvim.git
cd rev-nvim
mv rev-nvim nvim
cd nvim
nvim init.lua
```
