# Contributing

Install dependencies (this assumes you have [nodejs installed](https://nodejs.org/en/download/package-manager/))
```
npm install

// To build the project:
npm run build

// To rebuild the project when source files change:
npm run start
```

Pro-tip! If you are working on a project that uses css-utility-classes and you want changes immediately available in your project for testing, use `bower link`:

*Note, if you are using NPM, replace `bower link` with `npm link`.*

  1. If you haven't cloned css-utility-classes, do it now
  2. Navigate to the folder where css-utility-classes exists and run `bower link` (you only have to do this once)
  3. Navigate to your project and run `bower link css-utility-classes`

This replaces `bower_components/css-utility-classes` with a symlink to your cloned css-utility-classes. You may want to adjust your project's build process to listen for changes to `bower_components/css-utility-classes/dist/css-utility-classes.min.css` and rebuild your project's CSS automatically.
