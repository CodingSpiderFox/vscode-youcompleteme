# vscode-youcompleteme

[![Build Status](https://travis-ci.org/richard1122/vscode-youcompleteme.svg?branch=master)](https://travis-ci.org/richard1122/vscode-youcompleteme)

[YouCompleteMe](https://github.com/Valloric/YouCompleteMe) for vscode.

[Source](https://github.com/richard1122/vscode-youcompleteme)

[Issues](https://github.com/richard1122/vscode-youcompleteme/issues)

[VSCode extension market](https://marketplace.visualstudio.com/items?itemName=RichardHe.you-complete-me)

## Previews

completion

![completion](arts/completion.gif)

lint

![completion](arts/lint.gif)

fixit

![fixit](args/fixit.gif)

getType

![hover](arts/hover.gif)

## Features

* Semantic code completion with Ycmd backend
* Diagonostic display
* GetType with hover
* GoToDefinition with ctrl+click
* QuickFix

## Keymaps

* <kbd>alt</kbd>+<kbd>l</kbd> diagonostic

## Usage

* Install from vscode extension marketplace
* Install Ycmd, see [Ycmd's Readme](https://github.com/Valloric/ycmd#building)
* Config extension in your user or workspace settings.json

## Configuration

* `ycmd.path`: The directory you installed ycmd, like: `C:/Users/YOURNAME/.vim/bundle/YouCompleteMe/third_party/ycmd`
* `ycmd.global_extra_config`: Optional, see [ycm's Readme](https://github.com/Valloric/YouCompleteMe/blob/master/README.md#the-gycm_global_ycm_extra_conf-option)
* `ycmd.python`: Optional, python execuable path.
* `ycmd.confirm_extra_conf`: Optional, see [ycm's Readme](https://github.com/Valloric/YouCompleteMe/blob/master/README.md#the-gycm_confirm_extra_conf-option)
* `ycmd.enabled_languages`: Optional, default is `["c", "cpp"]`


## More languages

golang

![golang](arts/golang.gif)