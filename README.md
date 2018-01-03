# Laptop

> A script to setup/install/upgrade my preferred apps & configurations for web
development.

## Usage

## What it sets up

**Tools & Packages**
* Xcode commandline tools
* Homebrew
* Git
* Heroku CLI
* Tmux
* Rabbitmq
* MySQL
* PostgreSQL
* Authy
* Postman
* The Silver Searcher
* Karabiner-elements
* Zsh
* Exuberant Ctags
* AWS CLI
* Bundler
* ASDF Version manager
* Node.js
* Ruby
* Elixir
* Erlang
* Python
* Golang

**Mac OS Apps**
* Slack
* Docker for Mac
* Flux
* Github Desktop
* Atom
* iTerm2

**Configuration**
* Split DNS via openconnect

## Overrides

`~/.laptop.local` is run at the end of the `mac` script.
Further customizations can be added there. If you want to install additional
tools or Mac apps with Homebrew, add them to your `~/Brewfile.local`.

Write your customizations such that they can be run safely more than once.

Laptop functions such as `fancy_echo`, and `gem_install_or_update` can be used
in your `~/.laptop.local`.

## TODO

- [ ] Keyboard - key repeat
- [ ] Personal dotfiles (clone, symlink, ect)
- [ ] Oh-my-Zsh
- [ ] Powerline fonts
- [ ] Vundle (+ Install plugins)
- [ ] Oracle Instant Client
    ```sh
    tap instantclienttap/instantclient
    brew instantclienttap/instantclient/instantclient-basic
    brew instantclienttap/instantclient/instantclient-sdk
    brew instantclienttap/instantclient/instantclient-sqlplus
    ```

## Credits

Inspired by [thoughbot's laptop](https://github.com/thoughtbot/laptop) script.
