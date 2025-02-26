# deeper-dark color theme

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
