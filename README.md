# Platno, a starting boilerplate.

This is my starting boilerplate for all projects. Based on my personal development
practices it includes enough styling and markup to start proper modern development.

It is based on [Normalize](http://necolas.github.com/normalize.css/) with some
highly opinionated additions and extensions to make it more robust.

Other sources of code and inspiration include traditional
[Meyer Reset](http://meyerweb.com/eric/tools/css/reset/),
[HTML5 Boilerplate](http://html5boilerplate.com/) and
[Inuit](https://github.com/csswizardry/inuit.css).

## Installation

Well, you clone the project :). Since boilerplate uses Normalize as submodule,
you will have to use `--recursive` argument and pull changes from proper branch.

```bash
$ git clone --recursive git@github.com:niksy/platno.git
$ cd normalize
$ git pull origin v1
```

After that, include it in your project structure however you want it.

## Usage

Normalize (normalize.css) should be starting point for everything. After that,
you can add additions and extensions for it via Normalize+ (normalize+.css) and
traditional, although greatly modified, Reset styling (reset.css), which will
basically carpet bomb all those nasty spacing on elements :)

Print styling (print.css) is used for—you guessed it—print media. To keep usability
and display problems at minimum, it’s best to use Print styling only with
Normalize and Normalize+ but without Reset.

### Additional modules

Helpers contain some battle-hardened, useful helper classes, such as
clearfix and image replacement.

Diagnostics will point you errors and warnings with your markup such as empty
elements or images without alternate text so you can resolve those problems
in timely manner.

Some sensible project starting point is achieved with Starter, which contains
baseline styling and opt-in typography.

---

Platno is roughly translated to "blank canvas" in Croatian :)
