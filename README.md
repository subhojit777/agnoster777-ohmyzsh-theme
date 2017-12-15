# agnoster777.zsh-theme

A ZSH theme for users who want more information of the Git repository on the prompt.

## Compatibility

**NOTE:** In all likelihood, you will need to install a [Powerline-patched font](https://github.com/Lokaltog/powerline-fonts) for this theme to render correctly.

To test if your terminal and font support it, check that all the necessary characters are supported by copying the following command to your terminal: `echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"`. The result should look like this:

![Character Example](./images/characters.png)

## Installation

After installing [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

1. Download the theme from [here](http://raw.github.com/subhojit777/agnoster777-ohmyzsh-theme/master/agnoster777.zsh-theme)
2. Put the file `agnoster777.zsh-theme` in `$ZSH_CUSTOM/themes`
3. Configure the theme in your `~/.zshrc` file:

```bash
ZSH_THEME="agnoster777"
```

## Git information

### Icons
|Icon|Meaning
|----|-------|
|`✔`|clean directory
|`☀`|new untracked files preceeded by their number
|`✚`|added files from the new untracked ones preceeded by their number
|`‒`|deleted files preceeded by their number
|`●`|modified files preceeded by their number
|`±`|added files from the modifies or delete ones preceeded by their number
|`⚑`|ready to commit
|`⚙`|sets of stashed files preceeded by their number
|`☊`|branch has a stream, preceeded by his remote name
|`↑`|commits ahead on the current branch comparing to remote, preceeded by their number
|`↓`|commits behind on the current branch comparing to remote, preceeded by their number
|`<B>`|bisect state on the current branch
|`>M<`|Merge state on the current branch
|`>R>`|Rebase state on the current branch

## Credits

This theme is highly inspired by the following themes:
- [Agnoster](https://github.com/agnoster/agnoster-zsh-theme)
- [agnosterzak-ohmyzsh-theme](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme)
