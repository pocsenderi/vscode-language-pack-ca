# Traducció de VSCode al català

Aquesta és la traducció no oficial de VSCode al català. Moltes parts estan fetes amb el traductor Softcatalà, sona estrany i hi ha errors. Toca, entre tots, arreglar-ho :)

Tota la documentació i commits seran, preferiblement, en català.

## Com clonar

```
git clone https://github.com/katuak/vscode-language-pack-ca.git
cd vscode-language-pack-ca
```

Si vols mantenir un fork actiu i fer Releases, hi ha un workflow de [GitHub Actions](https://github.com/features/actions) que permet publicar l'extensió automàticament a VSCode Marketplace i OpenVSIX.

Crea un compte als serveis i crea un Personal Access Token (PAT):
- [Crear un compte a Microsoft VSCode Marketplace.](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
- [Crear un compte a OpenVSIX.](https://github.com/eclipse/openvsx/wiki/Publishing-Extensions)

Una vegada tenguis el PAT, hauràs d'emplenar uns secrets al repositori GitHub. `Settings` -> `Secrets` -> `Actions` -> `New repository secret`

![GitHub Secrets screenshot](github-secrets-screenshot.jpeg)

- `MS_MARKETLPLACE_PUBLISHER_ID` Azure marketplace publisher id
- `MS_MARKETLPLACE_TOKEN` Azure marketplace Personal Access Token
- `OPEN_VSIX_PUBLISHER_ID` Open VSIX marketplace publisher id
- `OPEN_VSIX_TOKEN` Open VSIX marketplace Personal Access Token

## To-Do List

- [x] main.i18n.json
- [ ] ms-vscode.js-debug.i18n.json
- [ ] vscode.bat.i18n.json
- [ ] vscode.builtin-notebook-renderers.i18n.json
- [ ] vscode.clojure.i18n.json
- [ ] vscode.coffeescript.i18n.json
- [ ] vscode.configuration-editing.i18n.json
- [x] vscode.cpp.i18n.json
- [ ] vscode.csharp.i18n.json
- [ ] vscode.css-language-features.i18n.json
- [ ] vscode.css.i18n.json
- [ ] vscode.dart.i18n.json
- [ ] vscode.debug-auto-launch.i18n.json
- [ ] vscode.debug-server-ready.i18n.json
- [ ] vscode.diff.i18n-json
- [ ] vscode.docker.i18n.json
- [ ] vscode.emet.i18n.json
- [ ] vscode.extension-editing.i18n.json
- [ ] vscode.fsharp.i18n.json
- [ ] vscode.git-base.i18n.json
- [x] vscode.git.i18n.json
- [ ] vscode.github-authentication.i18n.json
- [ ] vscode.github.i18n.json
- [ ] vscode.go.i18n.json
- [ ] vscode.groovy.i18n.json
- [ ] vscode.grunt.i18n.json
- [ ] vscode.handlebars.i18n.json
- [ ] vscode.hlsl.i18n.json
- [ ] vscode.html-language-features.i18n.json
- [ ] vscode.html.i18n.json
- [ ] vscode.ini.i18n.json
- [x] vscode.ipynb.i18n.json
- [ ] vscode.jake.i18n.json
- [ ] vscode.java.i18n.json
- [ ] vscode.javascript.i18n.json
- [ ] vscode.json-language-features.i18n.json
- [ ] vscode.json.i18n.json
- [ ] vscode.julia.i18n.json
- [ ] vscode.latex.i18n.json
- [ ] vscode.less.i18n.json
- [ ] vscode.log.i18n.json
- [ ] vscode.lua.i18n.json
- [ ] vscode.make.i18n.json
- [ ] vscode.markdown-language-features.i18n.json
- [ ] vscode.markdown-math.i18n.json
- [ ] vscode.markdown.i18n.json
- [ ] vscode.media-preview.i18n.json
- [ ] vscode.merge-conflict.i18n.json
- [ ] vscode.microsoft-authentication.i18n.json
- [ ] vscode.npm.i18n.json
- [ ] vscode.objective-c.i18n.json
- [ ] vscode.perl.i18n.json
- [ ] vscode.php-language-features.i18n.json
- [ ] vscode.php.i18n.json
- [ ] vscode.powershell.i18n.json
- [ ] vscode.pug.i18n.json
- [ ] vscode.python.i18n.json
- [ ] vscode.r.i18n.json
- [ ] vscode.razor.i18n.json
- [ ] vscode.references-view.i18n.json
- [ ] vscode.restructuredtext.i18n.json
- [ ] vscode.ruby.i18n.json
- [ ] vscode.rust.i18n.json
- [ ] vscode.scss.i18n.json
- [ ] vscode.search-result.i18n.json
- [ ] vscode.shaderlab.i18n.json
- [ ] vscode.shellscript.i18n.json
- [ ] vscode.simple-browser.i18n.json
- [ ] vscode.sql.i18n.json
- [ ] vscode.swift.i18n.json
- [ ] vscode.theme-abyss.i18n.json
- [ ] vscode.theme-defaults.i18n.json
- [ ] vscode.theme-kimbie-dark.i18n.json
- [ ] vscode.theme-monokai-dimmed.i18n.json
- [ ] vscode.theme-monokai.i18n.json
- [ ] vscode.quitelight.i18n.json
- [ ] vscode.theme-red.i18n.json
- [ ] vscode.theme-solarized-dark.i18n.json
- [ ] vscode.theme-solarized-light.i18n.json
- [ ] vscode.theme-tomorrow-night-blue.i18n.json
- [ ] vscode.typescript-language-features.i18n.json
- [ ] vscode.vb.i18n.json
- [ ] vscode.vscode-theme-seti.i18n.json
- [ ] vscode.xml.i18n.json
- [ ] vscode.yaml.i18n.json
