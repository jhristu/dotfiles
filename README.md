# James Hristu's private dotfiles #

## Pre-reqs ##

1. Sign in to App Store
1. Sign in to iCloud
1. Install XCode Command Line Tools by running `xcode-select --instal`

## Setup ##

Most of this is automated. Run the following:

```
pushd ~
mkdir -p workspace && cd workspace
git clone https://github.com/jhristu/dotfiles && cd dotfiles && ./bootstrap
popd
```

# App Store ##

Software I install via the App Store:

- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12)
- [Pixelmator](https://apps.apple.com/us/app/pixelmator/id407963104?mt=12)
- [Flexiglass](https://apps.apple.com/am/app/flexiglass/id426410278?mt=12)

## Updating dotbot submodule ##

```git submodule update --remote dotbot```

## TODO:

1. Flexiglass is no longer in App Store
1. Automate Touchpad -> Tap to click
1. Turn off Game Centre from Internet Accounts
1. Automate Battery -> Show Percentage
1. Deal with `Error: caskroom/versions was moved. Tap homebrew/cask-versions instead. Tapping caskroom/versions has failed!`
