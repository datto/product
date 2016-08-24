# Contributing

Install dependencies (this assumes you have [nodejs installed](https://nodejs.org/en/download/package-manager/))
```
npm install
bower install

// To build the project:
npm run build

// To launch a web browser (displays examples/index.html)
// and rebuild the project when source files change:
npm run start
```

Pro-tip! If you are working on a project that uses bootstrap3-datto and you want changes immediately available in your project for testing, use `bower link`:

*Note, if you are using NPM, replace `bower link` with `npm link`.*

  1. If you haven't cloned bootstrap3-datto, do it now
  2. Navigate to the folder where bootstrap3-datto exists and run `bower link` (you only have to do this once)
  3. Navigate to your project and run `bower link bootstrap3-datto`

This replaces `bower_components/bootstrap3-datto` with a symlink to your cloned bootstrap3-datto. You may want to adjust your project's build process to listen for changes to `bower_components/bootstrap3-datto/dist/bootstrap3-datto.min.css` and rebuild your project's CSS automatically.
