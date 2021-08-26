# linux 终端美化



## 安装zsh

```shell
apt-get install zsh
```



## 安装oh-my-zsh

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```



## 替换zsh

```shell
# zsh替换bash
chsh -s `which zsh`
```



## 修改终端主题

```shell
vim ~/.zshrc
# 修改以下参数为
ZSH_THEME="agnoster"
```



这时出现乱码，需要安装字体

```shell
apt-get install fonts-powerline
```

