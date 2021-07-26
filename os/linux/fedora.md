# Linux Fedora

## Install GUI

It is recommended to run dnf upgrade before proceeding, to make sure you have the latest version of all packages.

```
dnf upgrade
```

Simply install Xfce and its dependencies:

```
dnf install @xfce-desktop-environment
```

Edit ~/.xinitrc to end with ‘exec startxfce4’

```
echo "exec startxfce4" >> ~/.xinitrc
```