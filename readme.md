# 编译安装neovim

```bash
sudo apt install gettext autoconf gperf libluajit-5.1-dev libunibilium-dev libmsgpack-dev libtermkey-dev libvterm-dev libjemalloc-dev tmux && sudo pip3 install neovim
```

```bash
git clone https://github.com/neovim/neovim  
make CMAKE_BUILD_TYPE=RelWithDebInfo  
sudo make install  
```

# 编译安装neovim后


在 /etc/bash.bashrc 添加
```bash
alias vi="nvim"
alias vim="nvim"
```
```bash
source /etc/bash.bashrc
```

```bash
git clone https://github.com/474420502/nvim /etc/xdg/nvim
```

```bash
nvim anyfile

:PlugUpdate
```
