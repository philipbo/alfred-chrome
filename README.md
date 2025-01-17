# Alfred Chrome Workflow

[![Release](https://img.shields.io/github/release/ShogunPanda/alfred-chrome.svg)](https://github.com/ShogunPanda/alfred-chrome/releases/latest)
[![Packal](https://img.shields.io/badge/packal-alfred--chrome-green)](http://www.packal.org/workflow/alfred-chrome)
[![Forum](https://img.shields.io/badge/forum-alfred--chrome-yellowgreen)](https://www.alfredforum.com/topic/9473-alfred-chrome-open-url-in-google-chrome-also-with-specific-profile)
[![License](https://img.shields.io/github/license/ShogunPanda/alfred-chrome.svg)](https://github.com/ShogunPanda/alfred-chrome/blob/master/LICENSE.md)

This workflow allows you to open a URL in [Google Chrome](https://www.google.com/chrome/) via [Alfred 4](https://www.alfredapp.com/).

https://sw.cowtech.it/alfred-chrome

## Description

To trigger the workflow, type `chrome` or `cr`. Optionally you can add a URL.

Between the results you will a list of profiles to use to open the URL (or simply to open a new window).

If you hold the `Alt` key while selecting the result item, the window will be open using incognito mode.

## Installation

Double click (or open in Alfred settings) the `Alfred Chrome.alfredworkflow` file.

This workflow is for Alfred 3 only therefore it works on macOS 10.9+ (Mavericks and following).

## Uninstallation

Remove the workflow via Alfred settings.

## Specifying a different flavor of Chrome

If you use Canary version of Chrome or similar applications, like Chromium, you can instruct the workflow to use it.

To do it:

- In the Workflows settings, select Alfred Chrome workflow
- Open the `Configure workflow and variables` by clicking on the second icon on right section of the workflow header.
- Under the `Workflow Environment Variables` section, create a variable called `ALFRED_CHROME_NAME` and enter the same name you see in your Applications folder.
- Click on `Save` and you're good to go! :)

## Copyright

Copyright (C) 2013 and above Shogun (shogun@cowtech.it).

Licensed under the MIT license, which can be found at https://choosealicense.com/licenses/mit.
