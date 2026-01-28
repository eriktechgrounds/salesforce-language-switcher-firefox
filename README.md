# <img src="public/icons/icon_48.png" width="45" align="left"> Salesforce User Language Switcher for Firefox

This is a port of the [Salesforce User Language Switcher](https://github.com/derroman/salesforce-user-language-switcher) Chrome extension by [@derroman](https://github.com/derroman) to Firefox. Most code and even this README.md are simply copied from said original project.

## Features

- Queries all available languages of a Salesforce environment
- Provides a list of languages which can be switch with a single click
- Page will reload automatically after language switch

![The extension in action](ExtensionInAction.png)

## Remarks

- Switching to some languages might take a moment to refresh the Page, e.g. "Chinese (Traditional)"
- This extension only works in Salesforce Lightning (who uses Classic these days, anyway...)

## Install

This extension is not (yet) available on the Firefox Add-on store. You can install it manually by following these steps:
1. Download the latest `sf-language-switcher-firefox.zip` file from the [releases page](https://github.com/eriktechgrounds/salesforce-language-switcher-firefox/releases).
2. Open Firefox and navigate to `about:debugging`.
3. Click on 'This Firefox'.
4. Click on 'Load Temporary Add-on...'.
5. Select the `sf-language-switcher-firefox.zip` file.

## Contribution

Suggestions and pull requests are highly welcome.

---

The source project (Chrome extension) was bootstrapped with [Chrome Extension CLI](https://github.com/dutiyesh/chrome-extension-cli)

Icon source: <a href="https://www.flaticon.com/free-icons/translate" title="translate icons">Translate icons created by Freepik - Flaticon</a>