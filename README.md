# dokk

dokk aims to be a turnkey environment for building simple software documentation sites.

## In the mix

- [devcontainers](https://containers.dev): Help contributors use the same tools with the same configuration.
- [markdownlint](https://github.com/DavidAnson/markdownlint): Help contributors write consistent Markdown.
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material): Probably the worlds most complete and polished MkDocs theme.
- [GitHub Pages](https://pages.github.com/): Host documentation directly from a GitHub repository.
- [Mermaid](https://mermaid.js.org): Create diagrams and visualizations using Markdown-like syntax.

## Get started

Prerequisites:

- Docker
- Visual Studio Code

Run locally:

1. Clone and open the repo in Visual Studio Code.
1. Open the Command Palette (F1) and select `Remote-Containers: Reopen in Container`.
1. Run the following command in a terminal:

   ```console
   mkdocs serve
   ```

1. Open your browser and navigate to `http://localhost:8000` to see the documentation site.

Use `dokk` as template for your own project:

- Fork the repository.
- Replace the content in the `docs` folder with your own documentation.
- Update the configuration in `mkdocs.yml` to match your project.
- Enable GitHub Pages in the repository settings to host your documentation.

# Contribute

Contributions are welcome! Both Issues and Pull Requests are appreciated to make dokk more helpful and easy to use.

Code and style:

- Aim for consise language in an active voice.
- use the tools in the devcontainer, or improve the devcontainer.
- follow the rules in markdownlint.json
