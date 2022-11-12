# Explainer

The issue in this repo is that the Rome linter/formatter does not auto fix the error regarding if block scopes. 

As the `.vscode/settings.json` file has the correct `editor.codeActionsOnSave` rule and the `rome.rome` formatter as the option it should auto apply this fix. 

If you manually click on the quick fix it works. 