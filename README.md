# James Hristu's private dotfiles #

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