## Synchronizacja dotfiles przy pomocy NextCloud

Najważniejsza rzecz! 

Folder z Cloudem musi znajdować się pod adresem `~/Nextcloud/Dotfiles/files`

## Style GTK

Aby szablon gtk działał musimy mieć zainstalowane pare rzeczy

* osx-arc-white [AUR] lub (KDE STORE)[https://store.kde.org/p/1167049]
* papirus-icon-theme-git [AUR]

**Nie są instalowane pakiety przy pomocy ansible!**

W razie problemów z robieniem linków

```
mv ~/.config/gtk-3.0 ~/.config/gtk-3.0.old
mv ~/.config/gtk-2.0 ~/.config/gtk-2.0.old
```

## Style QT 

Zainstalować pakiet

* arc-kde-git [AUR]

W razie problemów z robieniem linków

```
mv ~/.config/qtcurve ~/.config/qtcurve.old
```
