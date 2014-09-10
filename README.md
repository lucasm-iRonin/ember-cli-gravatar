# Gravatar Image Tag

_Currently under devlopment_.

An [ember-cli](http://ember-cli.com) addon for a gravatar image component.

## Installation

First, you must install moment with [bower](http://bower.io):

```
$ bower install --save JavaScript-MD5
```

Add the following import to your Brocfile.js:

```js
app.import('vendor/JavaScript-MD5/js/md5.js');
```

Then, install ember-cli-gravatar:

```
$ npm install --save ember-cli-gravatar
```

## Usage

```hbs
{{gravatar-image email='johnotander@gmail.com' alt='John Otander gravatar'}}
```

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by [John Otander](http://johnotander.com).