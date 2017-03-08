# Enber OAuth Workshop

This repo is the seed project for a workshop on using [ember-simple-auth](https://github.com/simplabs/ember-simple-auth)
(ESA) and [torii](https://github.com/Vestorly/torii) to authenticate against GitHub
using [OAuth2 authentication code grant flow](https://tools.ietf.org/html/rfc6749#section-4.1). The workshop is first
being presented at Boston Ember.js on March 9, 2017. Based on the knowledge hopefully gained from the preceding talk,
the goal will be to add full authentication against GitHub into this app.

The app has a simple index page and a login page. You will make it so that if you start the app unauthenticated you go
to the login page. If authenticated, you go to your chosen page and it displays some information from GitHub.

I recommend you try it unassisted first, but if you want "guidance" or to follow a tutorial, see the
[related ESA guide](https://github.com/simplabs/ember-simple-auth/blob/master/guides/auth-torii-with-github.md) and
the [corresponding demo app](https://github.com/srvance/simple-auth-torii-github-demo).

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Bower](https://bower.io/)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository (fork it if you want to push)
* `cd ember-oauth-workshop`
* `npm install`
* `bower install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
