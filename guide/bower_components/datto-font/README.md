# The Datto "DIN" Font

Datto’s branding typeface is **DIN**. The modern feel and distinctive personality of this typeface provides Datto with strong visual recognition throughout all of our communications. The sharp yet organic and fluid design of this font works in concert with the simplicity of the Datto logo.

## Using

```
bower install --save git@github-server.datto.lan:UI-Components/datto-font.git
```

To use the font, a number of options are available:

### Precompiled CSS

The Bower package comes with a precompiled CSS file. Using a build tool (such as Gulp, Grunt, etc.), copy the contents of the `dist/` folder to your project's public folder.

### SASS

If your project is using SASS, include `@import 'bower_components/datto-font/src/sass/datto-font';` in your main SASS file. Additionally, update your build process to copy `dist/fonts` to your project's public folder.

### LESS

*TODO: add LESS support*

### (Deprecated) Using as a hosted font

```
<script src="//use.typekit.net/hrf0wzt.js"></script>
<script>try{Typekit.load();}catch(e){}</script>
```

This method is no longer recommended in favor of using a local copy.


## Changelog

* 0.0.3
  * Added SASS variables `$datto-font-family` and `$datto-font-family-bold-condensed` for use in other projects
* 0.0.2
  * Fixed CSS rules to ensure custom font is being used for bold and italics
* 0.0.1
  * Initial release. Woot!
