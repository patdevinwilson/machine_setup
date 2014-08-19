machine_setup
=============

Useful packages, frameworks, and applications for a new machine


##1. Install Homebrew 
$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

##2. Install ZSH 
$ brew install zsh

##3. Install Oh-My-Zsh 
$ curl -L http://install.ohmyz.sh | sh

##4. Install PostgreSQL postgis and postgres
 
brew install postgis

initdb /usr/local/var/postgres

pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start
