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

mkdir ~/.venv
python3 -m venv ~/.venv
source ~/.venv/bin/activate

python3 -m pip install docopt
python3 -m pip install ruamel_yaml
python3 -m pip install jinja2
python3 -m pip install distro
python3 -m pip install tomli_w
python3 -m pip install requests
python3 -m pip install packaging
```


Step 3:  Run the setup script:

```
./dotdrop.sh install -p home
```

