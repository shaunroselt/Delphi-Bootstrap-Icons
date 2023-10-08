# Delphi Bootstrap Icons (.SVG)

The [Bootstrap Icons library](https://icons.getbootstrap.com/) to use within Delphi.

<p align="center">
  <a href="https://v5.getbootstrap.com/">
    <img src="https://v5.getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo-shadow.png" alt="Bootstrap logo" width="200" height="165">
  </a>
</p>
<p align="center">
  Open source SVG icon library with over 2,000 icons.
</p>

[![Bootstrap Icons preview](https://github.com/twbs/icons/blob/main/.github/preview.png)](https://icons.getbootstrap.com)


## Usage

### SVG Code

```pascal
uses uBootstrapIcons

...

// Returns SVG Code:
var HouseIconSVG := GetBootstrapIcon('house');
var ValveSteamIconSVG := GetBootstrapIcon('steam');
var BrushIconSVG := GetBootstrapIcon('brush');

// Returns SVG Code with Width/Height set to 24:
var HouseIconSVG := GetBootstrapIcon('house', 24); 
var ValveSteamIconSVG := GetBootstrapIcon('steam', 24);
var BrushIconSVG := GetBootstrapIcon('brush', 24);

// Returns SVG Code with Width/Height set to 24 and color set to purple (#800080):
var HouseIconSVG := GetBootstrapIcon('house', 24, 'purple'); 
var ValveSteamIconSVG := GetBootstrapIcon('steam', 24, '#800080');
var BrushIconSVG := GetBootstrapIcon('brush', 24, 'purple');
```

### SVG Path Data

```pascal
uses uBootstrapIcons

...

// Returns SVG Path Data Text:
var HouseIconSVGPathData := GetBootstrapIconPathData('house'); 
var ValveSteamIconSVGPathData := GetBootstrapIconPathData('steam');
var BrushIconSVGPathData := GetBootstrapIconPathData('brush');

// Returns SVG Path Data Text with Width/Height set to 24:
var HouseIconSVGPathData := GetBootstrapIconPathData('house', 24); 
var ValveSteamIconSVGPathData := GetBootstrapIconPathData('steam', 24);
var BrushIconSVGPathData := GetBootstrapIconPathData('brush', 24);

// Returns SVG Path Data Text with Width/Height set to 24 and color set to purple (#800080):
var HouseIconSVGPathData := GetBootstrapIconPathData('house', 24, 'purple'); 
var ValveSteamIconSVGPathData := GetBootstrapIconPathData('steam', 24, '#800080'); 
var BrushIconSVGPathData := GetBootstrapIconPathData('brush', 24, 'purple'); 
```

Other ways to use Bootstrap Icons: [https://icons.getbootstrap.com/#usage](https://icons.getbootstrap.com/#usage)

## License

- Bootstrap Icons are free and open source ([MIT](https://github.com/twbs/icons/blob/main/LICENSE.md)).

---

## Other Delphi Icon Libraries
- [Font Awesome Icons](https://github.com/shaunroselt/Delphi-Font-Awesome-Icons)
