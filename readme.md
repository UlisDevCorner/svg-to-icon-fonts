![Collapse & Expand HTML Block Elements CSS & JS](./readme/images/svg-to-icon-fonts-835x346.jpg)

## Intro
To run this project first you have to install the npm packages with

```
npm i
```

Then you can run it either in the package.json file, the last script createIconFonts, or you run this command in the terminal.

```
npm run createIconFonts
```
## YouTube
You can find the video to this repo at this link.  
[**YouTube**: SVG to Icon Fonts](https://www.youtube.com/watch?v=ooCLkjZcCiA)

### Icon Font Example

[Fontawesome](https://fontawesome.com/icons)

### Install and Set Up
[**NPM**: fantasticon](https://www.npmjs.com/package/fantasticon)
```
npm init -y
npm i -D @pluslab/fantasticon
md icon-dist
```

#### SVG Resource
[SVG Repo](https://www.svgrepo.com/)

#### Quick Usage
`fantasticon my-icons -o icon-dist`

### Command-line
[Command-line](https://github.com/agencia-e-plus/fantasticon#command-line)
```
Usage: fantasticon [options] [input-dir]

Options:
  -V, --version                output the version number
  -c, --config <value>         custom config path (default: .fantasticonrc | fantasticonrc | .fantasticonrc.json | fantasticonrc.json | .fantasticonrc.js | fantasticonrc.js)
  -o, --output <value>         specify output directory
  -n, --name <value>           base name of the font set used both as default asset name (default: icons)
  -t, --font-types <value...>  specify font formats to generate (default: eot, woff2, woff, available: eot, woff2, woff, ttf, svg)
  -g --asset-types <value...>  specify other asset types to generate (default: css, html, json, ts, available: css, scss, sass, html, json, ts)
  -h, --font-height <value>    the output font height (icons will be scaled so the highest has this height) (default: 300)
  --descent <value>            the font descent
  --normalize [bool]           normalize icons by scaling them to the height of the highest icon
  -r, --round [bool]           setup the SVG path rounding [10e12]
  --selector <value>           use a CSS selector instead of 'tag + prefix' (default: null)
  -p, --prefix <value>         CSS class prefix (default: icon)
  --tag <value>                CSS base tag for icons (default: i)
  -u, --fonts-url <value>      public URL to the fonts directory (used in the generated CSS)
  --debug                      display errors stack trace (default: false)
  --silent                     run with no logs (default: false)
  --help                       display help for command
```

### Asset Types
#### Example
`fantasticon my-icons -o icon-dist -g css html`

**default**: css, html, json, ts  
**available**: css, scss, sass, html, json, ts

### Font Types
#### Example
`fantasticon my-icons -o icon-dist -t ttf`

**default**: eot, woff2, woff  
**available**: eot, woff2, woff, ttf, svg

#### Embedded OpenType
Embedded OpenType (EOT) fonts are a compact form of OpenType fonts designed by Microsoft for use as embedded fonts on web pages. These files use the extension .eot. They are supported only by Microsoft Internet Explorer, as opposed to competing WOFF files.

[**Wikipedia**: Embedded OpenType](https://en.wikipedia.org/wiki/Embedded_OpenType)

#### Web Open Font Format
The Web Open Font Format (WOFF) is a font format for use in web pages. WOFF files are OpenType or TrueType fonts, with format-specific compression applied and additional XML metadata added. The two primary goals are first to distinguish font files intended for use as web fonts from fonts files intended for use in desktop applications via local installation, and second to reduce web font latency when fonts are transferred from a server to a client over a network connection.

[**Wikipedia**: Web Open Font Format](https://en.wikipedia.org/wiki/Web_Open_Font_Format)

#### TrueType

TrueType is an outline font standard developed by Apple in the late 1980s as a competitor to Adobe's Type 1 fonts used in PostScript. It has become the most common format for fonts on the classic MacOS and Microsoft Windows operating systems.

[**Wikipedia**: TrueType](https://en.wikipedia.org/wiki/TrueType)

#### Scalable Vector Graphics

Scalable Vector Graphics (SVG) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation. The SVG specification is an open standard developed by the World Wide Web Consortium (W3C) since 1999.

[**Wikipedia**: Scalable Vector Graphics](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics)

## Install Helper Packages

### del-cli

[**NPM**: del-cli](https://www.npmjs.com/package/del-cli)

### mkdirp

[**NPM**: mkdirp](https://www.npmjs.com/package/mkdirp)

`npm i -D del-cli mkdirp`
