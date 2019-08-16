# Hangman

## Support

<p><style>.bmc-button img{width: 27px !important;margin-bottom: 1px !important;box-shadow: none !important;border: none !important;vertical-align: middle !important;}.bmc-button{line-height: 36px !important;height:37px !important;text-decoration: none !important;display:inline-flex !important;color:#000000 !important;background-color:#FFDD00 !important;border-radius: 3px !important;border: 1px solid transparent !important;padding: 1px 9px !important;font-size: 22px !important;letter-spacing:0.6px !important;box-shadow: 0px 1px 2px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;margin: 0 auto !important;font-family:'Cookie', cursive !important;-webkit-box-sizing: border-box !important;box-sizing: border-box !important;-o-transition: 0.3s all linear !important;-webkit-transition: 0.3s all linear !important;-moz-transition: 0.3s all linear !important;-ms-transition: 0.3s all linear !important;transition: 0.3s all linear !important;}.bmc-button:hover, .bmc-button:active, .bmc-button:focus {-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;text-decoration: none !important;box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;opacity: 0.85 !important;color:#000000 !important;}</style><link href="https://fonts.googleapis.com/css?family=Cookie" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/HEazcCDFS"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/BMC-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:5px">Buy me a coffee</span></a></p>

## Description

A simple hangman application built with [vue-cli-plugin-electron-builder](https://nklayman.github.io/vue-cli-plugin-electron-builder/), [electron-store](https://github.com/sindresorhus/electron-store), [vue-i18n](https://kazupon.github.io/vue-i18n/) and [chota CSS framework](https://jenil.github.io/chota/)

## Quickstart

### Install

```shell
$ npm install
```

### Run in dev

```shell
$ npm run electron:serve
```

### Build Linux (AppImage)

```shell
$ npm run electron:build
```

### Build Windows (exe) on Linux platform

/!\ you need to install [Docker](https://docs.docker.com/install/) first

```shell
$ chmod +x run_wine.sh
$ ./run_wine.sh
$ npm install
$ npm run electron:build-win
```

If you are on another platform than Linux, check the [docs](https://github.com/electron-userland/electron-builder)