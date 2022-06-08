# Development Server (Fedora)

Update the default package manager and it's dependencies.

```
sudo dnf update
```

Install `zsh` in order to replace the current `bash` shell.

```
sudo dnf install zsh
```

Switch the default shell from `bash` to `zsh`. Restart terminal and confirm that the shell has been updated.

```
sudo chsh -s $(which zsh)
```

```
echo $SHELL
```

## OhMyZsh

Install `wget` and `curl`.

```
sudo dnf install wget curl
```

Install OhMyZsh.

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
