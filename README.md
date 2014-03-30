# &lt;github-button&gt;

Web Component wrapper for [@mdo's GitHub button](https://github.com/mdo/github-buttons) using Polymer.

## Demo

![GitHub Element](http://zno.io/QtpO/github-element.png)

> [Check it live](http://zenorocha.github.io/github-button).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/github-button.html">
	```

3. Start using it!

	```xml
	<github-button></github-button>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`user`     | *string*                  | `customelements`    | GitHub username that owns the repo
`repo`     | *string*                  | `github-button`     | GitHub repository to pull the watchers/forks counts
`type`     | `follow`, `fork`, `watch` | `watch`             | Type of button to show
`count`    | `true`, `false`           | `true`              | Show the number of watchers/forks
`height`   | *int*                     | `25`                | The height of the button
`width`    | *int*                     | `100`               | The width of the button
`size`     | `large`, `regular`        | `regular`           | Flag for using a larger button or a regular one

> See GitHub Buttons' [official documentation](https://github.com/mdo/github-buttons).

## Browser Support

![IE](https://raw.github.com/paulirish/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/paulirish/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/paulirish/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/paulirish/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/paulirish/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/zenorocha/github-button/releases) list.

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha
