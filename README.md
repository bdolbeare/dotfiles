# env-setup

<img src="https://cdn.pixabay.com/photo/2012/05/04/10/57/gear-47203_960_720.png" width="128px"/>

This project provides a set of dotfiles that I use to create a consistent development environment acrross the many devices I use at work and home.

It was largely inspired by the following project(s): 

* <https://github.com/donnemartin/dev-setup>
* <https://github.com/nicolashery/mac-dev-setup>
* <https://github.com/mathiasbynens/dotfiles>

## Steps

Step 1: Clone the git repo:

```
git clone git@github.com:bdolbeare/dotfiles.git
```

Step 2:  Install the pre-requisites
```
pip3 install -r dotdrop/requirements.txt --user
```

or
```
pip3 install docopt
pip3 install ruamel_yaml
pip3 install jinja2
```


Step 3:  Run the setup script:

```
./dotdrop.sh install -p home
```

## Script Summary

**setup-osx.sh** run this command to update the OS, install XCode, and to write system defaults which control OS and applications settings/preferences. [view source](https://github.com/bdolbeare/env-setup/tree/master/mac/setup-osx.sh)

**setup-brew.sh** run this command to install brew, upgrade any existing brew formulae, and install some common tools and applications. [view source](https://github.com/bdolbeare/env-setup/tree/master/mac/setup-brew.sh)

**setup-tmux.sh** run this command to configure tmux with some preferred plugins. [view source](https://github.com/bdolbeare/env-setup/tree/master/mac/setup-tmux.sh)

**setup-powerline.sh** run this command to install the Powerline fonts which I like to use in tmux [view source](https://github.com/bdolbeare/env-setup/tree/master/mac/setup-powerline.sh)
