# Környezet beállítása macOS-en (macOS Mojave 10.14 (18A391))

## LaTeX telepítése
1. [MacTeX](http://www.tug.org/mactex/mactex-download.html) letöltése és telepítése

1. [TeXstudio](https://texstudio.org) letöltése és telepítése

1. TeX Live Utility - csomagok frissítése
Update All Packages

## Syntax highlighting beállítása
1. Python telepítése
Nem ajánlom `brew`-val felrakni, nekem az a változat összeakad a Reveal view debuggerrel. A gyári, beépített `/usr/bin/python` a célra tökéletesen megfelel.

1. pip telepítése
`sudo easy_install pip`

1. [Pygments](http://pygments.org) telepítése
`sudo pip install pygments`

## TeXstudio beállításai

### Commands
XeLaTeX: **`/Library/TeX/texbin/xelatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex`**

### Build
Default Compiler: **`txs:///xelatex`**

### Editor
Font Family: **Menlo**

### Language Checking
Default Language: **hu_HU**
