# cv

My Curriculum Vitae

## Compile

```bash
bin/print
bin/web
```

## Setup

You need to install `ʟᴬᴛᴱx` for printable documents and `ʜᴱᴠᴱᴀ` for HTML site.

### macOS

```bash
brew cask install mactex
echo 'export PATH="$PATH:/Library/TeX/texbin"' >> ~/.bash_profile
brew install hevea
brew install wget
wget http://hevea.inria.fr/distri/hevea.sty
```

### Ubuntu

```bash
sudo apt-get install texlive-full
sudo apt-get install hevea
```
