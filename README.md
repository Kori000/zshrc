# Zshrc

## Usage

### Step1. Move zshrc.txt file
```zsh
cd /Users/YourMacName
open .
```
Put the zshrc.txt file in this directory

### Step2. Modify file name
zshrc.txt -> .zshrc

### Step3. Install spaceship
Unzip spaceship.zip -> spaceship (folder)
```zsh
cd /Users/YourMacName
mkdir .zsh
open .zsh
```
Put the spaceship folder in this directory
### Step4. Install
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
### Step5. Source
```zsh
source .zshrc
```

