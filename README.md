# Development Server (Fedora)

Update the default package manager and it's dependencies.
```
dnf update
```
Install `zsh` in order to replace the current `bash` shell.
```
dnf install zsh
```
Switch the default shell from `bash` to `zsh`. Restart terminal and confirm that the shell has been updated.
```
chsh -s $(which zsh)
```
```
echo $SHELL
```
