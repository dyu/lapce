## Installation With Package Manager

### Arch Linux

There is an community package that can be installed with `pacman`:

```bash
sudo pacman -Syu lapce
```

### Fedora
```bash
sudo dnf copr enable titaniumtown/lapce
sudo dnf install lapce
```

### Flatpak

Lapce is available as a flatpak [here](https://flathub.org/apps/details/dev.lapce.lapce)

```bash
flatpak install flathub dev.lapce.lapce
```

### Gentoo

Lapce is available in Gentoos user repository GURU. 
If the GURU is not activated, it can be with:

```bash
emerge --ask app-eselect/eselect-repository # install eselect repository
eselect repository enable guru 
emaint sync -r guru
```

After activating and syncing the GURU repository, lapce can be installed with

```bash
emerge app-editors/lapce
```

### Homebrew

```bash
brew install lapce
```

### Scoop

```bash
scoop install lapce
```

### winget

You can find the packages [here](https://github.com/microsoft/winget-pkgs/tree/master/manifests/l/Lapce/Lapce):

```bash
winget install lapce
```
