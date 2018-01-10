# README

Sample project for rails with react.
Clone this and use as initial version of your project.

## IMPORTANT

React components should be put under `app/javascript/components` and added in slim html templates as  

```
== react_component 'Hello', name: 'Valiera'
```

CSS files should be put under `app/javascript/packs` and included in slim html templates as

```
= stylesheet_pack_tag 'hello'
```

* Installation

* `bundle install --path=./.bundle`
* `yarn install`

## Running the application

* `bundle exec rails s`
* Open page `http://localhost:3000/hello` in browser.
