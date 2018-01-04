# Laptop

> A script to setup/install/upgrade my preferred apps & configurations for web
development.

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

- Uninstall NVM

- [ ] Keyboard - key repeat
- [ ] Personal dotfiles (clone, symlink, ect)
- [ ] Powerline fonts
- [ ] Oracle Instant Client
    ```sh
    tap instantclienttap/instantclient
    brew instantclienttap/instantclient/instantclient-basic
    brew instantclienttap/instantclient/instantclient-sdk
    brew instantclienttap/instantclient/instantclient-sqlplus
    ```

## Credits

Inspired by [thoughbot's laptop](https://github.com/thoughtbot/laptop) script.
