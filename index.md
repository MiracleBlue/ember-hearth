---
layout: default
---
# Ember Hearth
Ember Hearth is an application used to manage Ember projects.

**Warning: Ember Hearth is alpha software and may misbehave.**

## Features
* Installs all needed tools automatically ([node.js](http://nodejs.org), [NPM](http://npmjs.com), [Bower](http://bower.io), [PhantomJS](http://phantomjs.org) and [Ember-CLI](http://ember-cli.com))
* Create new Ember projects
* Manage existing Ember projects
* Run a local test server
* Create development and release builds

## Installing
Download [the latest release of Hearth][releaseurl]. Double click to extract and move `Ember Hearth.app` to your Applications folder.

## Goals
Ember Hearth aspires to allow new users to do all they need to do to run Ember projects without touching the command line.

[releaseurl]: {%for release in site.categories.release limit:1 %}{{release.package_url}}{% endfor %}