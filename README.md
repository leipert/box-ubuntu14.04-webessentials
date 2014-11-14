# ubuntu14.04-webessentials box

Base box with most popular libraries for the web installed.

# What's new

- Make sure $HOME/tmp exists and is owned by `ubuntu`.

# License

The MIT License (MIT)

# Changelog

## 2.0.1
- npm updated to 2.1.8
- added imagemin 3.0.0
- fixed versions bower@1.3.12 gulp@3.8.10 grunt-cli@0.1.13
- Removed optipng, use imagemin instead

## 2.0.0
- phantomjs updated to 1.9.8
- nodejs updated to 0.10.33
- upgraded to ubuntu 14.04 (trusty)
- upgraded cookbooks for apt and added chef-sugar dependency
- added gulp, grunt and bower

## 1.0.4
- phantomjs 1.9.7 fixed

## 1.0.3
- updated node version (0.10.28)

## 1.0.2
- use newer node version (0.10.26)
- optipng updated to 0.7.5
- postgres-client updated to 9.3
- box no longer inherits from wercker/box-ubuntu12.04-chef10.18.2 but installs
chef 11.12.4

## 1.0.1

- use version bumped chef box (for inheritence)

## 1.0.0

- Make sure $HOME/tmp exists and is owned by `ubuntu`.

## 0.0.13

- adds libjpeg-dev
- adds libpng-dev
- adds optipng

## 0.0.12

- update to pgdg-keyring for postgres

## 0.0.11

- Update postgres-client to 9.2

## 0.0.10

- GitHub and Bitbucket public keys added to known_hosts

## 0.0.5

- Update wercker-essential-cookbook to 0.0.4
  - Update phantomjs to 1.9.1

## 0.0.4

- Lock apt cookbook to 1.8.2
- Update readme

## 0.0.3

- Initial release
