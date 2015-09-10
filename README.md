# Design Flow

1. Markup content
2. Setup typography
3. Sketch layouts for various breakpoints
4. Use breakpoint plugin to name the primay breakpoints
5. Style mobile
6. Style tablet
7. Style desktop

## Content

### Viewport

1. Set the [viewport meta tag](https://developers.google.com/web/fundamentals/layouts/rwd-fundamentals/set-the-viewport?hl=en) so the content is maximized on mobile screens

## Typography

### Typeface

1. Typeface for headings: DIN Condensed Web
2. Typeface for body: Minion Pro

### Scale

1. Modular Scale plugin
2. Golden Ratio

### Baseline

1. Install [baseliner](http://keyes.ie/things/baseliner/) 

### Reset

1. Install [marx](https://github.com/mblode/marx)

## Logo
1. Export SVG
2. Optimize SVG
	- [Tips](https://svgontheweb.com)
	- `$ npm install -g svgo`
	- `$ svgo logo.svg logo.min.svg`