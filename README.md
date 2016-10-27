# Sitegeist - Neos Guidelines

WIP

## Usage

`./flow guidelines:validate` - validates your neos/flow project against our guidelines

## Installation

Add this repository to your composer.json
```
    "repositories": [{
        "url": "ssh://git@git.sitegeist.de:40022/sitegeist/Sitegeist.NeosGuidelines.git",
        "type": "vcs"
    }],
```

and run `composer require --dev sitegeist/neosguidelines:dev-master`

This will give you a new flow-command `guidelines:validate`
--> `./flow guidelines:validate`

## Guidelines

Currently it is checked if a `README.md`, `composer.lock` and `.editorconfig` file exists and is versioned via git.
Also it is checked if the `README.md` contains the following sections(headlines(#)):
* Installation
* Deployment
* Versionskontrolle
