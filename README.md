# boilr-dependabot

---

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

if you have for force the local updates, use

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
Some related projects:

 

### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)  
* [github.com/stefanwalther](http://github.com/stefanwalther)

### License
MIT

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.8.0, on December 15, 2024._

