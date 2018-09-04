﻿P&D Helper Language Localisation Preject
======
**This project is a public project that is localized for P&D Helper.**

NOTICE: "P&D Helper" by Babos Technology is NOT an official app for Puzzle & Dragons.

P&D Helper is a powerful and fully parameterizable app that will help you solve difficult boards in [Puzzle & Dragons](https://www.puzzleanddragons.us/)/[パズル＆ドラゴンズ](http://pad.gungho.jp)
/[龍族拼圖](https://pad.gungho.jp/hktw/pad/).  
<a href="https://play.google.com/store/apps/details?id=com.lt.padhelper"><img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="48"></a>

# TRANSLATE
## How to **Pull requests**
1. Click **Fork** In the page top right corner. Fork your own copy of this repository to your account.
1. Use Git to clone/pull repository locally for modification(How to modify please see below).
1. Use Git to commit and push changes to your repository on GitHub.
1. Go to the **[[Pull requests|pulls]]** page in the top middle of this repository, and click the **New pull request** button.
1. Click the **Compare Across Forks** button and select your fork, the page then displays the changes.
1. Click the **Create pull request** button and enter the details of the modification, create your pull request.
## Translate the main program
1. The original English strings is `android/values/strings.xml`.
1. Copy the `values` folder to `values-your_language_tag`, and add to Git repository.
1. Translate your `strings.xml`.
## Translate news and logs
1. The original English webpage is `web/news/news.html` and `web/changelog/changelog.html`.
1. Copy the two HTML files to themselves folder, change filename to `news-your_language_tag.html` and `changelog-your_language_tag.html`, and then add to Git repository.
1. Translate your HTML files.
1. Change the `i18n_suffix` node value in your `strings.xml` to your language tag.
# Languages that are now supported
| Language Tag | Language variant |
| --- | --- |
| en | English |
| zh-rCN | 简体中文（中国） |
| zh-rHK | 繁體中文（香港） |
| zh-rTW | 繁體中文（台灣） |