# James Hristu's private dotfiles #

## Pre-reqs ##

1. Sign in to App Store
1. Sign in to iCloud
1. Install XCode Command Line Tools by running `xcode-select --install`

## Setup ##

Most of this is automated. Run the following:

```
pushd ~
mkdir -p workspace && cd workspace
git clone https://github.com/jhristu/dotfiles && cd dotfiles && ./bootstrap
popd
```

## Updating dotbot submodule ##

```git submodule update --remote dotbot```

## TODO:

1. Automate Battery -> Show Percentage
