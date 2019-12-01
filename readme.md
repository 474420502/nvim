编译安装neovim
---

sudo apt install gettext autoconf gperf libluajit-5.1-dev libunibilium-dev libmsgpack-dev libtermkey-dev libvterm-dev libjemalloc-dev tmux && sudo pip3 install neovim

git clone https://github.com/neovim/neovim  
make CMAKE_BUILD_TYPE=RelWithDebInfo  
sudo make install  

编译安装neovim后
---

在 /etc/bash.bashrc 添加
```bash
alias vi="nvim"
alias vim="nvim"
```
source /etc/bash.bashrc

在 /etc/xdg/ 下 git clone https://github.com/474420502/nvim (/etc/xdg/nvim/init.vim)
