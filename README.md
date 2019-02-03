# C[urriculum][ ]V[itae]

## Compile

```bash
bin/print
bin/web
```

## Setup

You need to install `LaTeX` for printable documents and `HeVeA` for HTML site.

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
