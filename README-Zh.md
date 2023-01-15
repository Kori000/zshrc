# Zshrc

## 使用

### 1. 移动文件 zshrc.txt
```zsh
cd /Users/YourMacName
open .
```
将zshrc.txt文件放入这个目录

### 2. 修改文件名
zshrc.txt 修改为 .zshrc

### 3. 安装 spaceship
解压 spaceship.zip 为 spaceship (文件夹)
```zsh
cd /Users/YourMacName
mkdir .zsh
open .zsh
```
将spaceship文件夹放入这个目录
### 4. 安装
```zsh
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1

ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
# ZSH_THEME="spaceship"
```
```zsh
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z
```
### 5. 启用
```zsh
source .zshrc
```

## 问题
+ 有问题可以直接提 issue, 每天都会回答 
+ 修改配置可以打开.zshrc 文件修改
```zsh
cd
open .zshrc
```

+ 注意, 配置中大部分使用到了我的 mac 电脑名字 "korix", 可以修改为自己的, 每次修改完成后记得启用最新配置
```zsh
source .zshrc
```
