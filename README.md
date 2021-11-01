### My vim setup note
## 1. Install powerline fonts
[https://github.com/powerline/fonts](https://github.com/powerline/fonts)
## 2. Select font for terminal
Select `Source Code Pro for Powerline 14 pt.`
## 3. Overwrite '~/.vimrc'
[https://github.com/kcokz/myvimrc/blob/master/.vimrc](https://github.com/kcokz/myvimrc/blob/master/.vimrc)
```
curl https://github.com/kcokz/myvimrc/blob/master/.vimrc --output ~/.vimrc
```
## 4. Run Vundle to install plugin
```
vi ~/.vimrc
:source %
:PluginInstall
```
