This is a clone of SinanMtl's much-appreciated webpack-simple-starter. I was using the vue-cli webpack template, but was growing tired of Vuejs's more "interesting" features. There are only 3 changes to the master:

1. "npm start" script aliased to "npm run dev".
2. Disabled autoOpenBrowser for dev env.
3. Added the FormidableLabs webpack-dashboard plugin.

Thanks for SinanMtl for making this useful starter.

# Webpack Simple Starter
A simple webpack starter without framework (Like Vue, React, Angular, etc.). This project is inspired from [**vue-cli webpack project**](https://github.com/vuejs/vue-cli#vue-build)

## Getting Started
First, install the modules that the project needs.
```bash
$ npm install
```

Now, let's start developing.
```bash
$ npm run dev
```

Finally development process done. Let's export for production.
```bash
$ npm run build
```

That's it!. Files are ready to under the `dist/` directory for production.

## What's in this project?

### Directories
There are four main directories in project. This directories like below:
```
build/		# Webpack configurations
config/		# Dev and prod configurations
src/ 		# Project development files
|_ scripts/	# Javascript files
|_ styles/	# Style files (scss)
|_ views/	# HTML templates (pug)
static/		# Static files (Like fonts, images)
```

### Used Frameworks
- Bootstrap and depended javascript frameworks like jquery. (Client)
- Babel.js for ES6 compile
- Sass for CSS
- Pug for HTML template

Also, this project is supporting hot reload and include **eslint**

## License
This project is under the MIT license.
