# Bootstrap 3... now in Datto-blue!

Bootstrap is heavily used by most projects at Datto and a good first step towards consistent UIs is to provide a custom Bootstrap build/theme.

The most common way to customize Bootstrap3 is to provide a "theme", which is a separate stylesheet used in combination with the default stylesheet. The problems with this approach is that the resulting CSS is larger and overriding some Bootstrap components can be really difficult.

Alternatively, a custom build of Bootstrap3 can be created by overriding the provided LESS (or SASS variables). This approach yields CSS that is easier to maintain and the final CSS is smaller because you are only importing a single stylesheet. This is the approach `bootstrap3-datto` takes. It is not a "theme" that is imported on top of the default Bootstrap3 stylesheet. **It is meant to replace your project's version of Bootstrap.**

Final note, this project is built using the [official SASS port](https://github.com/twbs/bootstrap-sass), which is maintained by Bootstrap and is always kept up to date with the official version of Bootstrap3. If a new version is released, this project simply needs to update its `bootstrap-sass` dependency, QA and release a new version.

So, what does it look like? Check out the [example page](http://github-server.datto.lan/pages/UI-Components/bootstrap3-datto/).

## Using

```
bower install --save git@github-server.datto.lan:UI-Components/bootstrap3-datto.git
```

Compiled source files can be found in the `dist/` folder.

## Documentation

For now, please refer to the [official Boostrap documentation](http://getbootstrap.com). Also, check out the [example page](http://github-server.datto.lan/pages/UI-Components/bootstrap3-datto/).

## Changelog

See [Changelog](CHANGELOG.md).

## Contributing

See [Contributing](CONTRIBUTING.md).
