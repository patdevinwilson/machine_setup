machine_setup
=============

Useful packages, frameworks, and applications for a new machine


1. Homebrew - ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

2. Install ZSH ~ $ brew install zsh

3. Install Oh-My-Zsh ~ $ https://github.com/robbyrussell/oh-my-zsh

4. Install PostGIS via Brew 

#4.1 Install PostgreSQL postgis and postgres
 
brew install postgis
initdb /usr/local/var/postgres
pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start
