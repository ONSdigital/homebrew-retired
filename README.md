# homebrew-retired

A homebrew tap for ONS to maintain formulae retired by homebrew.

It currently houses:

- gnupg@2.2

## How do I install these formulae?

```sh
    brew tap ONSDigital/homebrew-retired git@github.com:ONSdigital/homebrew-retired
    brew install ONSDigital/retired/$FORMULA@$VERSION
```

## How to extract an expired formula from homebrew-core

```sh
# Install the homebrew-core tap
brew tap homebrew/core --force
# Extract a specific version from the git tree and add to our tap
brew extract --version=$VERSION $FORMULA ONSDigital/homebrew-retired
# Install from our tap
brew install ONSDigital/retired/$FORMULA@$VERSION
```

To add to this repo for sharing with other developers you will need to extract the formula from the tap directory. On MacOS it's the below:

```txt
/usr/local/Homebrew/Library/Taps/ONSdigital/homebrew-retired
```
