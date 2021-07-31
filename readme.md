# gruvbox-gitea
![Color Palette: Gruvbox](readme_assets/color-palette-gruvbox.svg)
![For: Gitea](readme_assets/for-gitea.svg)
![Made With: CSS](readme_assets/made-with-css.svg)
![Open: Source](readme_assets/open-source.svg)

Gitea CSS theme for visual similarity to the [Gruvbox Vim theme](https://github.com/morhetz/gruvbox).

See Usage for installation and configuration instructions and ~~Sample for a preview screenshot~~ (screenshots pending).

## Usage
Clone repository with `git`.
```bash
git clone <remote here>
```
Copy CSS files into Gitea's customizations directory, see [Gitea's documentation](https://docs.gitea.io/en-us/customizing-gitea) for more information.
```bash
cp gitea-gruvbox.css $GITEA_CUSTOM/public/css/
```
Modify your Gitea configuration to use the theme.
```bash
nano $GITEA_CUSTOM/conf/app.ini
```
Specifically add gitea-gruvbox.css to the `THEMES` field under section `ui`.
Refer to [Gitea's documentation](https://docs.gitea.io/en-us/config-cheat-sheet/#ui-ui) for other relevant parameters you may wish to change, such as the default UI theme.
