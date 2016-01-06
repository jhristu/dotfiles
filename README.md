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

- [Pixelmator](http://www.pixelmator.com/mac/)
- [Flexiglass](http://www.nulana.com/flexiglass/)

## Updating dotbot submodule ##

```git submodule update --remote dotbot```