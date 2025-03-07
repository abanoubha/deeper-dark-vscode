# deeper-dark color theme

A color theme for visual studio code to make background absolute dark and text more contrasty and clear to read.

> [!NOTE]  
> This vscode color theme is mainly created for myself with my preferences in mind as you can read in [this post](https://abanoubhanna.com/posts/deeper-dark-color-theme-vscode/). And if you are wondering why I prefer opinionated software, read my post about [opinionated software vs heavily customized/customizable software](https://abanoubhanna.com/posts/heavily-customizable-software-vs-opinionated-software/). TL;DR; If I did not find an opinionated software that matches my opinions and preferences, I create an opinionated one.

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
