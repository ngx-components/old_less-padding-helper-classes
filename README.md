[![AngularJS Express](http://i.imgur.com/nTj9QgN.png)](https://github.com/angular-express/angular-express)

## LESS padding helper classes

Set of LESS padding helper classes that allow you to quickly assign various levels of padding to elements using plain CSS classes.

## Installation

To install the component:

```bash
$ ngx install less-padding-helper-classes
```

No clue what the `ngx` command line tool is? Learn more about [AngularJS Express](https://github.com/angular-express/angular-express).

## How to use

The components exposes the following CSS classes:

```less
@padding-xxs: .1rem;
@padding-xs: .3rem;
@padding-s: .5rem;
@padding-m: 1rem;
@padding-l: 1.5rem;
@padding-xl: 3rem;
@padding-xxl: 6rem;

.padding-xxs{ padding: @padding-xxs; }
.padding-top-xxs{ padding-top: @padding-xxs; }
.padding-right-xxs{ padding-right: @padding-xxs; }
.padding-bottom-xxs{ padding-bottom: @padding-xxs; }
.padding-left-xxs{ padding-left: @padding-xxs; }

.padding-xs{ padding: @padding-xs; }
.padding-top-xs{ padding-top: @padding-xs; }
.padding-right-xs{ padding-right: @padding-xs; }
.padding-bottom-xs{ padding-bottom: @padding-xs; }
.padding-left-xs{ padding-left: @padding-xs; }

.padding-s{ padding: @padding-s; }
.padding-top-s{ padding-top: @padding-s; }
.padding-right-s{ padding-right: @padding-s; }
.padding-bottom-s{ padding-bottom: @padding-s; }
.padding-left-s{ padding-left: @padding-s; }

.padding-m{ padding: @padding-m; }
.padding-top-m{ padding-top: @padding-m; }
.padding-right-m{ padding-right: @padding-m; }
.padding-bottom-m{ padding-bottom: @padding-m; }
.padding-left-m{ padding-left: @padding-m; }

.padding-l{ padding: @padding-l; }
.padding-top-l{ padding-top: @padding-l; }
.padding-right-l{ padding-right: @padding-l; }
.padding-bottom-l{ padding-bottom: @padding-l; }
.padding-left-l{ padding-left: @padding-l; }

.padding-xl{ padding: @padding-xl; }
.padding-top-xl{ padding-top: @padding-xl; }
.padding-right-xl{ padding-right: @padding-xl; }
.padding-bottom-xl{ padding-bottom: @padding-xl; }
.padding-left-xl{ padding-left: @padding-xl; }

.padding-xxl{ padding: @padding-xxl; }
.padding-top-xxl{ padding-top: @padding-xxl; }
.padding-right-xxl{ padding-right: @padding-xxl; }
.padding-bottom-xxl{ padding-bottom: @padding-xxl; }
.padding-left-xxl{ padding-left: @padding-xxl; }
```

The variables can be adjusted to tweak the different sizes.

## License

MIT.
