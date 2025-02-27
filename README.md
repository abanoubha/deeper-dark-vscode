# deeper-dark color theme

## Install Deeper Dark color theme

Search for `deeper dark` in Visual Studio Code extensions sidebar, choose the extension that provided by `Abanoub Hanna`, and install it.

Or install it via commandline, using this command:

```sh
ext install abanoubha.deeper-dark
```

Or find the extension on VS Marketplace: <https://marketplace.visualstudio.com/items?itemName=abanoubha.deeper-dark>

## develop

```sh
# install Yeoman and the VS Code extension generator
npm install -g yo generator-code

## run the generator
yo code

# install vsce to package and publish exts
npm install -g vsce

# package the ext.
vsce package

# publish it on vs code marketplace
vsce publish

# install the color theme extension
code --install-extension deeper-dark-*.vsix
```
