# Laptop

> A script to setup/install/upgrade my preferred apps & configurations for web
development.

![Build Status](https://travis-ci.org/jasonpilz/laptop.svg?branch=master)

## Usage

From the terminal:
```sh
bash <(curl -s https://raw.githubusercontent.com/jasonpilz/laptop/master/laptop)
```

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
* Zsh
* Oh-my-Zsh
* Vundle (+ Install plugins)
* Powerline fonts

**Mac OS Apps**
* Slack
* Docker for Mac
* Flux
* Github Desktop
* Atom
* iTerm2

**Configuration**
* Split DNS via openconnect
* Personal dotfiles

## Overrides

`~/.laptop.local` is run at the end of the `mac` script.  Further customizations
can be added there.

## TODO

- Uninstall NVM
- Travis CI

- [ ] Oracle Instant Client (separate script)
    ```sh
    tap instantclienttap/instantclient
    brew instantclienttap/instantclient/instantclient-basic
    brew instantclienttap/instantclient/instantclient-sdk
    brew instantclienttap/instantclient/instantclient-sqlplus
    ```
- [ ] Keyboard - key repeat
- [ ] Customize iTerm2

## Credits

Inspired by [thoughbot's laptop](https://github.com/thoughtbot/laptop) script.
