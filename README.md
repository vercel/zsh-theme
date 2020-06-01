# vercel.zsh-theme
▲Vercel's `zsh` theme

<p align="center">
  <img src="https://raw.githubusercontent.com/vercel/zsh-theme/master/screenshot.png?v=2">
</p>

## Install

### Using [antigen](https://github.com/zsh-users/antigen)

Add following line into your `~/.zshrc`, before `antigen apply`:

```
antigen theme vercel/zsh-theme
```

You can also preview theme without making it default by executing this command in active zsh session.

### Manual installation

First, download the theme into [`Oh My Zsh`](https://github.com/robbyrussell/oh-my-zsh)'s custom theme folder:

```
curl https://raw.githubusercontent.com/vercel/zsh-theme/master/vercel.zsh-theme -Lo ~/.oh-my-zsh/custom/themes/vercel.zsh-theme
```

Edit your `~/.zshrc`:

```
ZSH_THEME="vercel"
```

Then apply the theme:

```
source ~/.zshrc
```
