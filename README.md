# dotfiles

## とりあえずインストール (mac)

* [Homebrew](https://brew.sh/)
* [Docker for Mac](https://docs.docker.com/docker-for-mac/)
* [AppCleaner](https://freemacsoft.net/appcleaner/)
* [Rectangle](https://rectangleapp.com/)
* [KeepingYouAwake](https://github.com/newmarcel/KeepingYouAwake)
* [Quick View Calendar](https://apps.apple.com/jp/app/id1087080039)
* [Scroll Reverser](https://pilotmoon.com/scrollreverser/)
* [AltTab](https://alt-tab-macos.netlify.app/)
* [Alacritty](https://github.com/alacritty/alacritty)
* [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

```
$ brew install \
    ripgrep \
    tmux \
    prettier \
    black \
    jq \
    go \
    tig \
    ctop \
    bat
```

## Vimをビルド (mac)

```
$ mkdir -p ~/Workspaces/vim && cd $_
$ git clone https://github.com/vim/vim.git ~/Workspaces/Vim/vim
$ cd ~/Workspaces/Vim/vim
$ ./configure --prefix=$HOME/Workspaces/Vim/dest --enable-fail-if-missing --enable-terminal --enable-multibyte \
    && make \
    && make install
```
