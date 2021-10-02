# gruvbox-gitea
![Color Palette: Gruvbox](readme_assets/color-palette-gruvbox.svg)
![For: Gitea](readme_assets/for-gitea.svg)
![Made With: CSS](readme_assets/made-with-css.svg)
![Open: Source](readme_assets/open-source.svg)

Gitea CSS theme for visual similarity to the [Gruvbox Vim theme](https://github.com/morhetz/gruvbox).

Code-block syntax highlighting was adapted from [daveyarwood/gruvbox-pygments](https://github.com/daveyarwood/gruvbox-pygments).

See Usage for installation and configuration instructions and [dreamerslegacy.xyz's Gitea instance](https://dreamerslegacy.xyz/git/) for a demo.

## Usage
Clone repository with `git`.
```bash
git clone https://github.com/perpetualCreations/gruvbox-gitea.git
```
Alternatively, use the PROVIDENCE Git remote.
```bash
git clone https://dreamerslegacy.xyz/git/perpetualCreations/gruvbox-gitea.git
```
Copy CSS files into Gitea's customizations directory, see [Gitea's documentation](https://docs.gitea.io/en-us/customizing-gitea) for more information.
```bash
cp theme-gitea-gruvbox.css $GITEA_CUSTOM/public/css/
```
Modify your Gitea configuration to use the theme.
```bash
nano $GITEA_CUSTOM/conf/app.ini
```
Specifically add gitea-gruvbox.css to the `THEMES` field under section `ui`.
Refer to [Gitea's documentation](https://docs.gitea.io/en-us/config-cheat-sheet/#ui-ui) for other relevant parameters you may wish to change, such as the default UI theme.
