

# GitHub Actions Analysis Template

This is how this repository was created:

1.  I started with the `AGENTS.md`, `.devcontainer`, and `README.qmd`
    files.
2.  I asked Codex 5.3 to create the baseline GitHub Action to render
    this README from the `README.qmd` file.

> Help me create a GitHub action that:
>
> 1.  Sets up R using `r-lib/actions`.
> 2.  Installs quarto for building reports (also using `r-lib/actions`.
> 3.  Is triggered when there are pushes to main or PRs.
> 4.  Takes the README.qmd document, renders it, and then makes a commit
>     (using the bot user) to the current branch (if the README.md file
>     changed).
>
> You should be using [AGENTS.md](AGENTS.md) as part of your context (if
> you are not using it already)
