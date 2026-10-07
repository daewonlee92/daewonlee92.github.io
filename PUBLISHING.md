# Editing this homepage

The editable Quarto files are in the repository root. The rendered website is in `docs/`.

To regenerate the site, install Quarto and run from the repository root:

```sh
quarto render
touch docs/.nojekyll
```

Commit both the edited source and regenerated `docs/` files. GitHub Pages publishes the `docs/` folder on the `main` branch. The `.nojekyll` file allows the rendered Quarto assets to be served directly.

The site can also be previewed by opening `docs/index.html` locally.
