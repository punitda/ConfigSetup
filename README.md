### Setup steps to config everything on new machine:
##### Writing this over here so I don't have to open 10 different tabs everytime I upgrade/change machine :stuck_out_tongue:

1. Install [oh-my-zsh](https://ohmyz.sh/)
``` 
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

2. Install following Zsh plugins:
   - [Zsh Autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
      ```
      git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
      ```
   - [Zsh Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
      ```
      git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
      ```
   **Note:**  Setup of above plugins in `.zshrc` will be automatically done in later steps when we install your DotFiles setup.
2. Download [Hyper.js](https://hyper.is/) terminal. :pray:
3. Install following plugins for Hyper.js:
    - [hyper-snazzy](https://github.com/sindresorhus/hyper-snazzy)
    - [hypercwd](https://github.com/hharnisc/hypercwd)
    
   **Note:** Just open `~/.hyper.js` file and add above in list of plugins field like below:
   ```
   plugins: [ 'hypercwd','hyper-snazzy']
   ```
4. Create `DotFiles` folder and clone all the .config files, bash/zsh scripts/functions,etc. from the `DotFiles` private repo.
5. Run symlink setup scripts in that folder and done. :metal: 
