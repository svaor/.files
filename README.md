# .files
Various configuration files:
Bash, ConEmu[^1] (Settings -> General -> Fonts -> DejaVu Sans Mono for Powerline), Windows Terminal (App in MS Store)

# Zsh
```
cd ~
sudo apt-get install zsh
sudo apt-get install git
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
# Fonts
```
git clone https://github.com/powerline/fonts.git
cd fonts
```
```
powershell -ExecutionPolicy Bypass -File .\install.ps1
```
# Highlight
```
cd ~
curl https://raw.githubusercontent.com/seebi/dircolors-solarized/master/dircolors.ansi-dark --output ~/.dircolors
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

[^1]: [Setting up Windows Subsystem for Linux with zsh + oh-my-zsh + ConEmu](https://blog.joaograssi.com/windows-subsystem-for-linux-with-oh-my-zsh-conemu/)
