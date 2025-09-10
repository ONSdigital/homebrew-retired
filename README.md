# homebrew-retired

A homebrew tap for ONS to maintain formulae retired by homebrew.

It currently houses:

- gnupg@2.2

## How do I install these formulae?

`brew install onsdigital/retired/<original_tap>/<formula>`

Or `brew tap onsdigital/retired` and then `brew install <original_tap>/<formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "onsdigital/retired"
brew "<formula>"
```

## How to extract an expired formula from homebrew-core

```sh
# Install the homebrew-core tap
brew tap homebrew/core --force
# Extract a specific version from the git tree and add to our tap
brew extract --version=$VERSION $PACKAGE onsdigital/homebrew-retired
# Install from our tap
brew install onsdigital/retired/$PACKAGE@$VERSION
```

To add to this repo for sharing with other developers you will need to extract the formula from the tap directory. On MacOS it's the below:

```txt
/usr/local/Homebrew/Library/Taps/onsdigital/homebrew-retired
```
