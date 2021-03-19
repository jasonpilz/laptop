<img src="_images/osx_laptop.png" align="right" />

# Laptop

> A script to setup/install/upgrade my preferred apps & configurations for web
development.

[![Build Status](https://travis-ci.org/jasonpilz/laptop.svg)](https://travis-ci.org/jasonpilz/laptop)

## Usage

From the terminal:
```sh
bash <(curl -s https://raw.githubusercontent.com/jasonpilz/laptop/master/laptop.setup)
```

**Alternatively, if you have `svn` and want to run installers manually:**

(Downloads the `.laptop` directory recursively in pwd)
```sh
svn export https://github.com/jasonpilz/laptop/trunk/.laptop
```

### Additional

There are additional stand-alone installers for various purposes in the
[.laptop/](https://github.com/jasonpilz/laptop/tree/master/.laptop) directory.

## What it sets up

[Xcode]: https://developer.apple.com/xcode/features/
[Homebrew]: https://brew.sh/
[Git]: https://git-scm.com/
[Heroku]: https://www.heroku.com/
[Heroku CLI]: https://devcenter.heroku.com/articles/heroku-cli
[Amazon Web Services]: https://aws.amazon.com/
[AWS CLI]: https://aws.amazon.com/cli/
[Tmux]: https://github.com/tmux/tmux
[The Silver Searcher]: https://github.com/ggreer/the_silver_searcher
[Exuberant Ctags]: http://ctags.sourceforge.net/
[ASDF]: https://github.com/asdf-vm/asdf
[Zsh]: http://zsh.sourceforge.net/
[Vundle]: https://github.com/VundleVim/Vundle.vim
[Powerline fonts]: https://github.com/powerline/fonts
[Split DNS]: https://github.com/batmanppc/vpnc-scripts/blob/master/vpnc-script
[Dotfiles]: https://github.com/jasonpilz/dotfiles
[Bundler]: https://bundler.io/
[Oh-my-Zsh]: https://github.com/robbyrussell/oh-my-zsh
[PostgreSQL]: https://www.postgresql.org/
[MySQL]: https://www.mysql.com/
[RabbitMQ]: https://www.rabbitmq.com/
[Node.js]: https://nodejs.org/en/
[Ruby]: https://www.ruby-lang.org/en/
[Elixir]: https://elixir-lang.org/
[Erlang]: https://www.erlang.org/
[Python]: https://www.python.org/
[Golang]: https://golang.org/
[Slack]: https://slack.com/
[Docker for Mac]: https://www.docker.com/docker-mac
[Postman]: https://www.getpostman.com/
[Karabiner-Elements]: https://github.com/tekezo/Karabiner-Elements
[Karabiner]: https://pqrs.org/osx/karabiner/complex_modifications/
[Authy]: https://authy.com/
[Github Desktop]: https://desktop.github.com/
[Atom]: https://atom.io/
[iTerm2]: https://www.iterm2.com/
[SSH key]: https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/
[Gotham theme]: https://github.com/whatyouhide/gotham-contrib
[Zsh autosuggestions]: https://github.com/zsh-users/zsh-autosuggestions

**Mac OS Tools**
* [Xcode] - Command Line Tools
* [Homebrew] - Mac OS package manager

**Unix Tools**
* [Git] - Version control
* [Tmux] - Terminal multiplexer
* [The Silver Searcher] - project/file search
* [Exuberant Ctags] - Index files for Vim
* [Zsh] - Shell
* [Heroku CLI] - Command Line interface to [Heroku]
* [AWS CLI] - Command Line interface to [Amazon Web Services]

**Version/Package Managers**
* [ASDF] - Version manager for languages
* [Bundler] - Package manager for Ruby
* [Oh-my-Zsh] - Zsh plugin manager
* [Vundle] - Vim plugin manager + Install plugins

**Programming Languages**
* [Ruby] - A dynamic, OS language built for developer happiness
* [Elixir] - a dynamic, functional language designed for building
scalable and maintainable applications
* [Erlang] - functional language which Elixir is built upon
* [Golang] - a compiled, statically typed language
* [Python] - an interpreted high-level programming language for
general-purpose programming
* [Node.js] - JavaScript runtime for server-side programming

**Custom Configuration**
* [Powerline fonts] - Patched fonts for Powerline users
* [Split DNS] - Replace `vpnc-script` that openconnect ships with to support split DNS configuration
* [Dotfiles] - Install my personal dotfiles/configurations
* [Karabiner] - Configure caps lock with split personality (esc on press, ctrl on hold)
* [SSH key] - Generate an SSH key and add to `ssh-agent` for easy Github authentication
* [Gotham theme] - Download and load iterm2 gotham theme
* [Zsh autosuggestions] - Fish-like autosuggestions for zsh

**Databases / Brokers**
* [PostgreSQL] - Relational DBMS
* [MySQL] - Relation DBMS
* [RabbitMQ] - Message broker

**Mac OS Apps**
* [Slack] - Team communication
* [Docker for Mac] - Application containerization
* [Postman] - API testing
* [Karabiner-Elements] - Keyboard customization tool
* [Authy] - 2FA
* [Github Desktop] - Desktop git client
* [Atom] - Code editor
* [iTerm2] - Terminal replacement

## Overrides

`~/.laptop.local` is run at the end of the `mac` script.  Further customizations
can be added there.

## TODO

- export DOFTILES env var + ask for it at start of script with my default
- install Gotham-custom.itermcolors from dotfiles
- script for cloning all repos
- script for global install of useful rubygems
- script for global install of useful npm packages

- [ ] npm install -g (Be sure to `asdf reshim nodejs` after)
    ```sh
    fast-cli
    json
    ```

- [ ] pip install (Be sure to `asdf reshim python` after)
    ```sh
    pygments
    ```

- [ ] Oracle Instant Client (separate script)
    ```sh
    tap instantclienttap/instantclient
    brew instantclienttap/instantclient/instantclient-basic
    brew instantclienttap/instantclient/instantclient-sdk
    brew instantclienttap/instantclient/instantclient-sqlplus
    ```

- [ ] Customize Atom
  ```sh
  Packages
    vim-mode-plus
    autosave

  Editor
    Font size: 12
    check show invisibles
    check Auto Indent
  ```

## Supported

Tested on Mac OS X 10.13.2 (High Sierra)

## Credits

Inspired by [thoughbot's laptop](https://github.com/thoughtbot/laptop) script.
