# Ridiculously Simple Vue (CLI) + App Engine

A ridiculously simple Vue (generated with the CLI) + App Engine boilerplate for when you just want to start making stuff.

No backend. Everything goes through the .yaml file. 

Okay, fine, this is not as ridiculously simple as it could be since it uses CLI. If you want something literally as simple as possible look [here](https://github.com/JudeOsborn/ridiculous_vue_gae).

The /dist folder is deployed to App Engine, which requires a build (see below).

## Setup

	npm install


### Compiles and hot-reloads for development

	npm run serve


### Compiles and minifies for production

	npm run build


### Lints and fixes files

	npm run lint

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Deploying

Replace [app id] with your very own App Engine id. 

Make sure to build first.

	gcloud app deploy dist/app.yaml --project cl-syd-general --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and start making stuff.

## Credits

Jude Osborn
