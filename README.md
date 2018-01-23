# mac-dev-setup
Setting up dev environments 
### homebrew
* [homebrew](https://brew.sh)
* `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
### iterm
* `brew cask install iterm2`
### git
* `brew install git`
### vim
* `brew install vim`
### tmux
* `brew install tmux`
* if tmux user-namespace error run this
* `brew install reattach-to-user-namespace`
### generate new SSH key
* [github help](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#adding-your-ssh-key-to-the-ssh-agent)
* `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
### add to ssh-agent
* `eval "$(ssh-agent -s)"`
* `ssh-add -K ~/.ssh/id_rsa`
### copy ssh key to clipboard
* `pbcopy < ~/.ssh/id_rsa.pub`
### dotfiles
* [thoughbot-dotfiles](https://github.com/thoughtbot/dotfiles)
* clone down dotfiles-local from personal repo
* `git clone git@github.com:natevenn/dotfiles-local.git`
### zsh-syntax-highligting
* `brew install zsh-syntax-highlighting`
* add this line to dotfiles-local/.zshrc.local if it doesnt exist
* `source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh`
### powerline fonts
* [instructions](https://gist.github.com/kevin-smets/8568070)
### postgresql
* [postgresql app instructions](http://postgresapp.com/documentation/gui-tools.html)
### rvm
* `curl -sSL https://get.rvm.io | bash -s stable`
### Ag aka the_silver_searcher
* `brew install the_silver_searcher`
### node and npm
* `brew install node`
### redis 
* `brew install redis`
* then run `redis-server`





