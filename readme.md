### Installation guide:

1. Copy paste settings from `settings.json` to your local `settings.json`.
2. `js.js` and `css.css` files paths should be adjusted in `settings.json`, look for section: `"vscode_custom_css.imports"`
3. `roslyn-lsp` is a c# language server file. Its path should be adjusted in `settings.json`, look for section: `"dotnet.server.path"`
4. The extensions installation should be followed by terminal command: `cat extensions.txt | xargs -L 1 code --install-extension`
5. Copy paste settings from `keybindings.json` to your local `keybindings.json` settings
