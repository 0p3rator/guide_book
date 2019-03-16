# Vim-go

## Environment requires

- vim 8
- vundle
- golang 1.8 or higher
- v2ray(vpn)
- cow(transfer from socks5 to https)

---

1. [vim8](vim8.md) 
2. [vundle](vundle.md)
3. [golang](golang.md)
4. [v2ray&cow](vpn.md)


## vim-go install

## About vim-go

This plugin adds Go language support for Vim, with following features:

- `:GoBuild` `:GoInstall` `:GoTest` `:GoTestFunc`
- `:GoRun`
- `:GoDebugStart` integrated with delve
- `gocode` support completion
- `gofmt` and `goimports` save undo history
- `:GoDef`
- `:GoMetaLinter` etc

## Install

1. `Plugin 'fatih/vim-go'` into `.vimrc`
2. `vim` then `:PluginInstall`
