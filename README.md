<h1 align="center">
  <br>
  <a href="https://github.com/entcloudcom/StarVault/"><img src="https://raw.githubusercontent.com/entcloudcom/StarVault/master/assets/img/logo.png" alt="StarVault" width="200"></a>
  <br>
    StarVault
  <br>
</h1>

<h4 align="center">A lightweight, privacy-focused Github stars manager with power filtering. All data stored locally. Filter function can work in offline mode after data synced locally.</h4>

<p align="center">
  <a href="https://github.com/entcloudcom/StarVault/">
    <img src="https://img.shields.io/badge/release-1.0.1-blue"
         alt="StarVault">
  </a>

  <a href="https://www.paypal.me/leopku">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How to Use</a> •
  <a href="#download">Download</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://raw.githubusercontent.com/entcloudcom/StarVault/master/assets/screenshot.png)

## Key Features

* Free to use. (Sources NOT opened currently)
* About 50MB only
* Privacy focused
* All data stored locally
* Work in offline mode except syncing stars from github
* Power filtering with lean filter syntax
* Wildcard filtering
* Filtering by name of repository, name of repo owner, language, topics, stars count, forks count etc
* Pre-configurated filter by commonly used languages
* Dark/Light mode
* Cross platform
  - Windows, macOS ready. Linux coming soon.

## How to use

### Syncing starred repositories
1. Generate a new Github <a href="https://github.com/settings/personal-access-tokens/new" target="_blank">personal access token</a>
2. Fill personal access token in StarVault.(`Peference` -> `Settings` -> `Account`)
3. Go to `General` -> `All`
4. Click `Sync Stars` button in top-right corner.
5. Click sync button multi times until all starred repositories synced due to limits of Github API

### Filtering
After syncing starred respositories from github, repositories can be found easily by change filters. Here are some examples of filtering syntax.

* `shadcn`  # wildcard filtering
* `owner:wailsapp` # filter by owner
* `topics:react` # filter by topics
* `stars_count:>100` # filter by stars count more than 100
* `forks_count:>100` # filter by forks count more than 100
* `open_issues_count:<10` # filter by open issues count less than 10
* `shadcn topics:react topics:nextjs stars_count:>100 open_issues_count:<10` # composed filter

## Download

You can [download](https://github.com/entcloudcom/StarVault/releases) the latest binary file of StarVault for Windows, macOS and Linux.

## Support

If you like this project and think it has helped in any way, consider buying me a coffee!

<a href="https://www.paypal.me/leopku" target="_blank"><img src="app/img/bmc-button.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>


## License

Copyright 2025 &copy;entcloud.com
