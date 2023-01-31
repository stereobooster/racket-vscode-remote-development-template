This is a [VS Code development container](https://github.com/microsoft/vscode-dev-containers) for the [racket](https://www.racket-lang.org/).

You can check that first link for the full details of how to get set up to use VS Code development containers, but the gist of it is:

1. Install [Docker](https://docs.docker.com/get-docker/).
2. Install the [Remote Development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack).
3. Clone this repo.
4. In VS Code, either:
    - "Open folder..." the cloned repo, then click the "Reopen in container" button that appears in the lower right.
    OR
    - F1 and "Remote-Containers: Open Folder in Container..." the cloned repo.
5. In VS Code, open a New Terminal from the Terminal menu.

## TODO

- [Built-in bracket colorization](https://code.visualstudio.com/blogs/2021/09/29/bracket-pair-colorization)
    - https://blog.scottlowe.org/2020/03/08/modifying-visual-studio-code-bracketing-behavior/
- paredit
    - [strict-paredit](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit)
    - [paredit](https://marketplace.visualstudio.com/items?itemName=clptn.code-paredit)

