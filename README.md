# &lt;twbs-grid&gt;

The Bootstrap Grid System Web Component.

## Demo
> [Check it live](http://ifly9.com.br/webcomponents/twbs-grid/).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install twbs-grid --save
```

Or [download as ZIP](https://github.com/mvaldetaro/twbs-grid/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="bower_components/platform/platform.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="bower_components/twbs-grid/src/twbs-grid.html">
  ```

3. Start using it!

  ```html
<bs-row>
    <bs-col md="8">.bs-col-md-8</bs-col>
    <bs-col md="4">.bs-col-md-4</bs-col>
</bs-row>
  ```

## Options

Attribute                                      | Options | Default   | Description
---                                            | ---     | ---       | ---
`xs`                                           |         | `12`      | Extra small devices Phones (<768px)
`sm`                                           |         | `12`      | Small devices Tablets (≥768px)
`md`                                           |         | `12`      | Medium devices Desktops (≥992px)
`lg`                                           |         | `12`      | Large devices Desktops (≥1200px)
`xspull`, `smpull`, `mdpull` , `lgpull`        |         | `0`       | Change the order of our built-in grid columns
`xspush`, `smpush`, `mdpush` , `lgpush`        |         | `0`       | Change the order of our built-in grid columns
`xsoffset`, `smoffset`, `mdoffset`, `lgoffset` |         | `0`       | Move columns to the right

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

Check [Release](https://github.com/mvaldetaro/twbs-grid/releases) list.

## License

[MIT License](http://mvaldetaro.mit-license.org/) © Magno Valdetaro
