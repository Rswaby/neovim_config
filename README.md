# Mac neovim Config setup

Yeah this config is pretty nice on mac 

### requirements/dependencies

```sh
brew install neovim && brew install ripgrep
```

Some of the fonts look better with iterm2 in my opinion 
```sh
brew install --cask iterm2
```

```sh
brew install node
```

(Optional) if you don't already have this installed :)
```sh
xcode-select --install
```
 Some key mapping rn 
 
```sh 
Neovim keymaps refs

<Leader>Sv - vertical split 
<Leader>Sh - horizontal split 
<Leader>Se - make split windows equal 
<Leader>Sx - close current split 

<Leader>To - open new tab 
<Leader>Tx - close current tab 
<Leader>Tn - go to next tab 
<Leader>Tp - go to prev tab 

<Leader>Fs - find files within directory 
<Leader>Fs - find files in working dir 
<Leader>Fc - find string under curser 
<Leader>Fb - list open buffers in nevoid 

<Leader>gc — list all git commits (use <cr> to checkout) ["gc" for git commits]
<Leader>gfc — list git commits for current file/buffer (use <cr> to checkout) ["gfc" for git file commits]
<Leader>gb -- list git branches (use <cr> to checkout) ["gb" for git branch]
<Leader>gs -- list current changes per file with diff preview ["gs" for git status]
```
