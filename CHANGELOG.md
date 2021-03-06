# Changelog

## 2.0.1

- Allow for the case that selecting a menu item unmounts the menu (mostly by manager timers more intelligently).

## 2.0.0

- Ignore letter key presses if the letter is paired with `alt`, `ctrl`, or `meta` keys.
- Use [tap.js](https://github.com/alexgibson/tap.js) to improve click-outside-closes behavior: no overlay required anymore, meaning that a click outside can *both* close the menu *and* do something else — with both mouse and touch events.

## 1.1.0

- Allow objects as MenuItem `value`s.

## 1.0.0

- Nothing really: it was just time to start the real versioning.

## 0.8.0
- Overlay to enable close-when-clicking-outside for mobile.

## 0.7.0
- New, more flexible API: provided components are just wrappers around whatever elements they're given.

## 0.6.0
- Pass `event` to `handleSelection`.

## 0.5.2
- Add keywords to `package.json`.

## 0.5.1
- Update build.

## 0.5.0
- Make class names a little more explicit (change `menuWrapper--trans` to `menuWrapper--transition` and `li` to `menuItemWrapper`).
- Add `transition` option to factory and remove `transition` prop from component.

## 0.4.0
- Options to customize css classes' component name and namespace.
- Remove the need to pass in React by distinguishing `dist-modules/` with (transpiled) CommonJS modules and `dist/` with a UMD library that expects React to be global.
- Switch from browserify to webpack for JS module compilation.

## 0.3.0
- Remove `classnames` dependency.

## 0.2.0
- Add `dist-modules` for modular consumption.
- Upgrade dependencies.

## 0.1.0
- Initial release.
