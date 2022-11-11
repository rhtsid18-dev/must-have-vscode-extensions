# Must have VSCode Extensions

## A list of vscode extensions that I have found to be essentials in my workflow: -

* [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
    * It's great for avoiding silliy code formatting mistakes in markdown.
    * It's great for keeping a standardized set of linting rules for every contributor in the codebase to follow.
* [GitLens](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
    * It's great for code blame where you can view the person who made the last code change on each line of code.
    * It has great command pallet commands which make running git commands a breeze.
* [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
    * It's great for checking the history of changes made to a single file with graphs and other details.
    * We can compare the file in the current workspace with an older version of the file and see all the changes that are there which is amazing.
* [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
    * Great tool for looking at a graphical representation of your active branch or all your branchs in one go if that is what you want.
* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
    * Adds gitignore language support to the file.
    * Provides commands link add .gitignore throught the command pallet using which you can generate a .gitignore file in your repo based on some pre-existing templates.
* [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
    * This is the official VSCode theme from GitHub.
    * I like the Github Dark Dimmed variant of this theme the most.
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme-icons)
    * Adds descriptive icons to all file types in the VSCode explorer sidebar.
* [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
    * A great extension that addes color fills to all indentations that help us visually better identify the indentations.
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
    * The name pretty much sums it up.
* [CSS Peek](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
    * The name pretty much sums it up.
* [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
    * Adds auto-complete suggestion support when adding classes to HTML elements.
* [AutoComplate shell](https://marketplace.visualstudio.com/items?itemName=truman.autocomplate-shell)
    * Adds rich language support for shell scripts
* [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
    * Adds complete support for all things docker. Main things that I am interested in is that it provides intelliSense for `Dockerfile` and `docker-compose.yml` files.ß

## Other must have setup related things: -

* Configure the following settings in your VSCode user.settings as this will enable selected bracket highlighting: -

```json
{
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs":"active"
}
```

* Configure the following settings in your VSCode user.settings as this will enable sticky scrolling: -

```json
{
    "editor.stickyScroll.enabled": true
}
```

## Good to have visual settings: -

```json
{
    "editor.cursorBlinking": "phase",
    "editor.cursorSmoothCaretAnimation": true
}
```

## References: -

* [This](https://www.youtube.com/watch?v=Guva-oab1pg) is a great video on youtube from where I referenced most of the git extensions in the list below.
* [This](https://www.youtube.com/watch?v=c5GAS_PMXDs) is another great video on youtube from where I got the reference for the rest of the extensions in the list above.
