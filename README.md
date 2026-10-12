# boilr-dependabot

> **Retired:** boilr templates predate AI coding tools and no longer make sense. This repository is archived read-only and will receive no further updates.

## Purpose
Create a default dependabot config to be used in GitHub actions.

The following files are generated:

```
.
└── .github
    └── dependabot.yml

2 directories, 1 file
```

## Installation
Install [boilr](https://github.com/tmrts/boilr) first.

Then use

```
$ boilr download stefanwalther/boilr-dependabot <template-tag>
```

e.g.
```
$ boilr download stefanwalther/boilr-dependabot boilr-dependabot
```

## Usage
### Download the template

```
$ boilr template download stefanwalther/boilr-dependabot <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-dependabot
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g.
$ boilr template save $(PWD) dependabot
```

if you have to force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-dependabot .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```

## About

### Related projects

Other boilr templates (all retired and archived, like this one):

- [boilr](https://github.com/stefanwalther/boilr)
- [boilr-akita-entity](https://github.com/stefanwalther/boilr-akita-entity)
- [boilr-akita-filter](https://github.com/stefanwalther/boilr-akita-filter)
- [boilr-boilr](https://github.com/stefanwalther/boilr-boilr)
- [boilr-boilr-doc](https://github.com/stefanwalther/boilr-boilr-doc)
- [boilr-changelog](https://github.com/stefanwalther/boilr-changelog)
- [boilr-circleci](https://github.com/stefanwalther/boilr-circleci)
- [boilr-dockerfile-nodejs](https://github.com/stefanwalther/boilr-dockerfile-nodejs)
- [boilr-dockerignore](https://github.com/stefanwalther/boilr-dockerignore)
- [boilr-docs](https://github.com/stefanwalther/boilr-docs)
- [boilr-docs-author](https://github.com/stefanwalther/boilr-docs-author)
- [boilr-docs-contributing](https://github.com/stefanwalther/boilr-docs-contributing)
- [boilr-editorconfig](https://github.com/stefanwalther/boilr-editorconfig)
- [boilr-eslintrc](https://github.com/stefanwalther/boilr-eslintrc)
- [boilr-gitignore](https://github.com/stefanwalther/boilr-gitignore)
- [boilr-github-template-extensions](https://github.com/stefanwalther/boilr-github-template-extensions)
- [boilr-lic-mit](https://github.com/stefanwalther/boilr-lic-mit)
- [boilr-makefile](https://github.com/stefanwalther/boilr-makefile)
- [boilr-mocha-conf](https://github.com/stefanwalther/boilr-mocha-conf)
- [boilr-nodemon](https://github.com/stefanwalther/boilr-nodemon)
- [boilr-npmignore](https://github.com/stefanwalther/boilr-npmignore)
- [boilr-npmrc](https://github.com/stefanwalther/boilr-npmrc)
- [boilr-nvmrc](https://github.com/stefanwalther/boilr-nvmrc)
- [boilr-prettier](https://github.com/stefanwalther/boilr-prettier)
- [boilr-prettierrc](https://github.com/stefanwalther/boilr-prettierrc)
- [boilr-renovate](https://github.com/stefanwalther/boilr-renovate)
- [boilr-tsconfig](https://github.com/stefanwalther/boilr-tsconfig)

Full overview: [all boilr repositories](https://github.com/stefanwalther?tab=repositories&q=boilr&type=source)

### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)
* [github.com/stefanwalther](http://github.com/stefanwalther)

### License
MIT
