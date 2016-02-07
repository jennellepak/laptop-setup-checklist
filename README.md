# Laptop Setup Checklist

## Software Downloads
 * Install homebrew:
 
 ```bash
 /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
 ```
 * Install and configure rbenv:
 
 ```bash
 brew install rbenv
 rbenv install 2.3.0
 rbenv global 2.3.0
 echo '# Initialize rbenv' >> ~/.bash_profile
 echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
 source ~/.bash_profile
 rbenv rehash
 ```
 
 * get rails set up
 
 ```bash
 gem install rails
 ```
 
 * install [Atom](https://atom.io/download/mac)
 * setup git
 
 ```bash
 brew install git
 git config --global user.name ...
 git config --global user.email ...
 ```
 * add SSH keys
 * install [postgresql](http://postgresapp.com/)


