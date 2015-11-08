# Platno, a starting boilerplate.

This is my starting boilerplate for all projects. Based on my personal development practices it includes enough styling and markup to start proper modern development.

It is based on [Normalize](http://necolas.github.com/normalize.css/) with some highly opinionated additions and extensions to make it more robust.

Other sources of code and inspiration include [traditional Meyer Reset](http://meyerweb.com/eric/tools/css/reset/), [HTML5 Boilerplate](http://html5boilerplate.com/) and [Inuit](http://inuitcss.com/).

Browser support includes Internet Explorer 7+ and for other browsers their modern versions (basically, versions from the last 6 months).

## Installation

Clone the projects or install via [Bower](http://bower.io/).

```bash
bower install niksy/platno
```

## Usage

Platno’s assets are SASS partials so it’s best to include them as such in your SASS preprocessing workflow. With that you have option to change environment variables such as support for Internet Explorer &#8804; 7.

[**Normalize**](http://necolas.github.com/normalize.css/) should be starting point for everything. You can download it with your preferred method (e.g. manual installation or package manager like [Bower](http://bower.io)).

After that, you can add additions and extensions for it via [**Rationalize**](https://github.com/niksy/rationalize.css) and traditional, although greatly modified, [**Reset**](https://github.com/niksy/restart.css), which will basically carpet bomb all those nasty spacing on elements :)

### Additional modules

**Helpers** (`helpers`) contain some battle-hardened, useful helper classes, such as clearfix and image replacement.

Some sensible project starting point is achieved with **Starter** (`starter`), which contains baseline styling, and **UGC** (`ugc`) with opt-in typography.

## Notes

* To use HTML5 elements in IE &#8804; 8, it’s best to [download Modernizr](http://modernizr.com/download/) with included printshiv support.
* Various server configuration files can be found in [H5BP server-configs repository](https://github.com/h5bp/server-configs).

---

Platno is roughly translated to "blank canvas" in Croatian :)
