# README

Sample project for rails with react, using [rails webpacker](https://github.com/rails/webpacker) and [react-rails](https://github.com/reactjs/react-rails).

Clone this and use as initial version of your project.

## IMPORTANT

React components should be put under `app/javascript/components` and added in slim html templates as  

```
== react_component 'Hello', name: 'Valiera'
```

CSS files should be imported from `app/javascript/packs/application.js` as:

```
import '../stylesheets/main.sass'
import '../stylesheets/hello.css'
```

and included in slim html templates as

```
= stylesheet_pack_tag 'application'
```

because imported styles will be compiled into `application.css` by webpacker.

## Installation

* `bundle install --path=./.bundle`
* `yarn install`

## Running the application

* `bundle exec rails s`
* Open page [http://localhost:3000/hello](http://localhost:3000/hello) in browser.
