# Delphi Bootstrap Icons (.SVG)

The [Bootstrap Icons library](https://icons.getbootstrap.com/) to use within Delphi.

<p align="center">
  <a href="https://v5.getbootstrap.com/">
    <img src="https://v5.getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo-shadow.png" alt="Bootstrap logo" width="200" height="165">
  </a>
</p>
<p align="center">
  Open source SVG icon library with over 1,900 icons.
</p>

[![Bootstrap Icons preview](https://github.com/twbs/icons/blob/main/.github/preview.png)](https://icons.getbootstrap.com)


## Usage

```pascal
uses uBootstrapIcons

...


var HouseIconSVG := GetBootstrapIcon('house'); // Returns SVG Code
var ValveSteamIconSVG := GetBootstrapIcon('steam'); // Returns SVG Code
var BrushIconSVG := GetBootstrapIcon('brush'); // Returns SVG Code

var HouseIconSVGPathData := GetBootstrapIconPathData('house'); // Returns SVG Path Data Text
var ValveSteamIconSVGPathData := GetBootstrapIconPathData('steam'); // Returns SVG Path Data Text
var BrushIconSVGPathData := GetBootstrapIconPathData('brush'); // Returns SVG Path Data Text
```

Other ways to use Boostrap Icons: [https://icons.getbootstrap.com/#usage](https://icons.getbootstrap.com/#usage)

## License

- Bootstrap Icons are free and open source ([MIT](https://github.com/twbs/icons/blob/main/LICENSE.md)).
