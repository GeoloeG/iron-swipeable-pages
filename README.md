[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/GeoloeG/iron-swipeable-pages)

# `<iron-swipeable-pages>`

## Descripton

`<iron-swipeable-pages>` manages a set of pages and provides the ability to switch between them by swiping gesture.

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install iron-swipeable-pages --save
```

## Usage

Import Custom Element:

```html
<link rel="import" href="bower_components/iron-swipeable-pages/iron-swipeable-pages.html">
```

And then use it:

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="iron-swipeable-pages.html">
	  <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<iron-swipeable-pages selected="0">
  <div>One</div>
  <div>Two</div>
  <div>Three</div>
</iron-swipeable-pages>
```

See the [Documentation](https://geoloeg.github.io/iron-swipeable-pages/) for more options.

## More Demos

[https://geoloeg.github.io/iron-swipeable-pages/](https://geoloeg.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/)

## Discussing

If you have any questions, you can find me on the [Polymer Slack Channel](https://polymer.slack.com/), or just raise an Issue.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
