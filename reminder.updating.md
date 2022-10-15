# Personal notes on updating

## what not to forget:

1. update screenshots (themeDB/images/BananaAcid/...). + config screenshot in theme
2. update commit value, since tags are not used by themeDB. (themeDB/themes/BananaAcid-*.json::repo-commit)
3. *optional* update readme.md with new screenshot ref
4. update 3rd party repo (themes/rep.json)
    1. add a zip version of the subfolder to be referenced as content download in the rep.json
5. pull `https://github.com/suchmememanyskill/CssLoader-ThemeDb`
    1. copy `themeDB/*` to repo's root
    2. send pull-request

## remember

### debugging

accessing the steameck in inspector:

[Ref/docu is here](https://github.com/suchmememanyskill/CssLoader-ThemeDb)

1. decky -> settings -> enable remote CEF
2. chrome://inspect/#devices
    1. add ip:8081
    2. inpect ... `SP` is the main area

### adding 3rd party repo for testing

1. on steamdeck: /user/dock/homebrew/themes/repos.txt
    1. add: https://raw.githubusercontent.com/BananaAcid/SteamDeck-CSS-Themes/main/themes/rep.json