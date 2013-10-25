# &lt;facebook-likebox&gt;

Web Component wrapper for Facebook's Likebox(https://developers.facebook.com/docs/plugins/like-box-for-pages/) using Polymer.

> Maintained by [Tiago Celestino](https://github.com/tcelestino).

## Demo

> [Check it live](http://customelements.github.io/boilerplate-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/facebook-likebox.html">
	```

3. Start using it!

	```html
	<facebook-likebox></facebook-likebox>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`appid`      | *string*                  | ``               | Your app id
`bar`      | `abc`, `def`, `ghi` 	   | `foo`               | Lorem ipsum
`height`   | *int*                     | `100`               | Lorem ipsum


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)