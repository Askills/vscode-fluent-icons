<div align="center">

<img src="https://raw.githubusercontent.com/misolori/vscode-fluent-icons/master/icon.png" width="140" />

# Fluent Icons for Visual Studio Code

</div>

[Product icons themes](https://code.visualstudio.com/api/extension-guides/product-icon-theme) allow theme authors to customize the icons used in VS Code's built-in views: all icons except file icons (covered by file icon themes) and icons contributed by extensions. This extension uses [Fluent Icons](https://www.figma.com/community/file/836835755999342788/Microsoft-Fluent-System-Icons).

# Install
Since this is using the proposed api for product icon themes, we're unable to publish this to the marketplace. Download the latest package from the [release](https://github.com/misolori/vscode-fluent-icons/releases) tab and manually install the vsix from the extensions list. Then you'll need to re-open code with the following flag:

`code --enable-proposed-api miguelsolorio.vscode-fluent-icons`

If you'd like for this to always be installed, you can open the `.vscode/argv.json` file in your home directory and add the following flag to always enable it:

```json
"enable-proposed-api": [
    "miguelsolorio.vscode-fluent-icons"
]
```
