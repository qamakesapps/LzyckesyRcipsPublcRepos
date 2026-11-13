# Lazy Cook Easy recipes

Live recipe catalog for the Lazy Cook Easy iOS app, served by GitHub Pages at
`https://qamakesapps.github.io/LzyckesyRcipsPublcRepos/recipes.json`.

Don't hand-edit. Generate it with `tools/build_recipes.py` in the app repo, bump `version`,
and commit the new `recipes.json` here. Phones pick it up the next time the app opens.
The app ignores a file that fails to parse, has no recipes, or has a lower `version`.
