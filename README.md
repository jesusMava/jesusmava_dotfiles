# jesusmava_dotfiles
By Jesus Mava

For Ubuntu 18.04

## How to install

Your old `.zshrc`, `.vimrc`, `.tmux_conf` will be rename with a suffix `.old`

```
Dotfiles:
curl -L https://raw.github.com/jesusMava/jesusmava_dotfiles/master/bin/dotfiles | bash

```

## Options

```
-h,  --help        Prints the help
-np, --no-packages Suppress packages updates
-ns, --no-sync     Suppress pulling from the remote repository
```

## After installation

Add to `~/.gitconf` your name and email.

```
[user]
	name  = John Doe
	email = example@gmail.com
```

Download your ssh pub and priv keys to `~/.ssh/id_rsa.pub` and `~/.ssh_id_rsa` respectively.

```
chmod 600 ~/.ssh/id_rsa
```

## How to update

`dotfiles`

## Shortcuts & Commands

[Functions](/shell/functions)

#TMUX

## TPM

[TPM](https://github.com/tmux-plugins/tpm)

```
cpu tpm
```

# vim plugins

```
nerdtree
```

## Scripts

```
install_nvm
install_rvm
```

# Troubleshooting

if you have problems installing dotfiles, maybe, you need to change user permissions from dotfiles.tar.gz

```
chmod 666 $HOME/dotfiles.tar.gz
```

