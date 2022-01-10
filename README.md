## My vim setup note
## Mac
### 1. Install powerline fonts
[https://github.com/powerline/fonts](https://github.com/powerline/fonts)
### 2. Select font for terminal
Select `Source Code Pro for Powerline 14 pt.`
### 3. Overwrite '~/.vimrc'
[https://github.com/kcokz/myvimrc/blob/master/.vimrc](https://github.com/kcokz/myvimrc/blob/master/.vimrc)
```
# Install Vundle
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
```
curl https://raw.githubusercontent.com/kcokz/myvimrc/master/.vimrc --output ~/.vimrc
```
### 4. Run Vundle to install plugin
```
vi ~/.vimrc
:source %
:PluginInstall
```
### 5. Change CapsLock to point to Esc
Do this in mac is to change "Keyboard shortcut" in "System Preference"
