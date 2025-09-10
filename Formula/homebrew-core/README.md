# homebrew-core

This folder is for formula that is extracted from older versions of [homebrew-core](https://github.com/homebrew/homebrew-core). All code falls under their [license](./LICENSE.txt), is their work and has not been modified by ONSDigital.

## gpg@2.2

To install

```sh
    # Install the tap if you haven't already
    brew tap ONSDigital/homebrew-retired git@github.com:ONSdigital/homebrew-retired
    # Install the formula
    brew install ONSDigital/retired/gnupg@2.2
    # Add to path
    echo 'export PATH="/usr/local/opt/gnupg@2.2/bin:$PATH"' >> ~/.zshrc
```
