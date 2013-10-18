# Brunch with Chaplin
![](https://a248.e.akamai.net/camo.github.com/b7ebb8bbcec7938940cf8e9c441124c3bddafd3a/687474703a2f2f662e636c2e6c792f6974656d732f34373039326b30423141334a317a3166306b34362f6277632e706e67)

This is HTML5 application, built with
[Brunch](http://brunch.io) and [Chaplin](http://chaplinjs.org).

## Installation
Clone this repo manually with git or use `brunch new gh:paulmillr/brunch-with-chaplin`.

## Getting started
* Install:
    * [node.js](http://nodejs.org) if you don't have it (`brew install node` on OS X).
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * [Bower](http://bower.io): `npm install -g bower`
    * Brunch plugins and Bower dependencies: `npm install & bower install`.
* Run:
    * `brunch watch --server` — will watch the project with continuous rebuild. This will also launch HTTP server.
    * `brunch build --production` — will build minified project for production
* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.You should write your code in `app` dir.
    * Place static stuff you want to be copied to `public` in `app/assets`.
    * [Brunch site](http://brunch.io), [Chaplin site](http://chaplinjs.org)

---------------

# For newcomers

Brunch with Chaplin is a skeleton (boilerplate) for [Brunch](http://brunch.io)
based on [Chaplin](http://chaplinjs.org) architecture. Requires Brunch 1.7+.

Example application built with the skeleton:
[Ost.io](https://github.com/paulmillr/ostio).

This branch does not contain ready-to-use test environment.
If you want take a look how tests can be used, see `with-tests` git branch.

## Difference from Chaplin Boilerplate
[Chaplin Boilerplate](https://github.com/chaplinjs/chaplin-boilerplate)
is a official boilerplate all for chaplin. This skeleton is almost the same,
except a few changes:

* Added Header.
* CommonJS is used instead of AMD, because it's easier to use & debug.

## Features
* HTML5Boilerplate html & css are included.
* CoffeeScript + Stylus + Handlebars as app languages
(you can change this to anything you want)
* Backbone as main MVC/MVP library, Chaplin as meta-framework.
* Support of IE8 and up.
* Cross-module communication using the Mediator and Publish/Subscribe patterns
* Controllers for managing individual UI views
* Rails-style routes which map URLs to controller actions
* An application view as dispatcher and view manager
* Extended model, view and collection classes to avoid repetition and
enforce conventions
* Strict memory management and object disposal
* A collection with additional manipulation methods for smarter change events
* A collection view for easy and intelligent list rendering

## Authentication
If you build an application with authentication, there are some useful abstractions for it out there: https://github.com/chaplinjs/chaplin-auth.

## License
The MIT license.

Copyright (c) 2012 Paul Miller (http://paulmillr.com/)

Copyright (c) 2012 Moviepilot GmbH, 9elements GmbH et al.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
