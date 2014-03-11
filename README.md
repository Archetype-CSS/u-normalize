# u-normalize [![Build Status](https://secure.travis-ci.org/Archetype-CSS/u-normalize.png?branch=master)](http://travis-ci.org/Archetype-CSS/u-normalize) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

Archetype utility for normalize.css

## Installation
  * [Bower](http://bower.io): {{coming soon}}
  * Git: `git clone https://github.com/Archetype-CSS/u-normalize.git`

  Then,
  * Import the partial in your main project Sass file `@import
    bower_components/Archetype/u-normalize`

## Use

  * `@include normalize-display;` - normalize HTML5 display definitions
  * `@include normalize-page;` - normalize <code>html</code> and <code>body</code>
    element styles
  * `@include normalize-links;` - normalize hyperlinks
  * `@include normalize-typography;` - normalize typography
  * `@include normalize-embeds;` - normalize embeded content
  * `@include normalize-figures;` - normailze figures
  * `@include normalize-forms;` - normalize forms
  * `@include normalize-tables;` - normalize tables

## Run the Test Locally

```bash
git clone https://github.com/Archetype-CSS/u-normalize.git
cd u-normalize
npm install
grunt
```

### Browser Suport
  * Chrome (latest)
  * Firefox (4+)
  * Opera (latest)
  * Safari (5+)
  * Internet Explorer (8+)

#### License
[MIT](/LICENSE.md)

