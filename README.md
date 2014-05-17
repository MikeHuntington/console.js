console.js
==========

A game console for web. Check the [live demo](http://amio.github.io/console.js).

## Usage

Include CSS & JS in your page:

```
	<link href="http://amio.github.io/console.js/lib/console.css" rel="stylesheet" />
	<script src="http://amio.github.io/console.js/lib/console.js"></script>
```

then:
```
new Console({
    "addbots": function (num) {
        // add some bots,
        // then tell player:
        return num + ' bots added.'
    }
});
```

## Advance Usage

#### Init Console with options

```
new Console({
    "addbots": function (num) {
        // add some bots,
        // then tell player:
        return num + ' bots added.'
    }
}, {
    welcome: 'Need some help? Try "help":'
});
```
