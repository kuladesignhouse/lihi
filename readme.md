# Life in the Hawaiian Islands



## ZURB WebApp with NetlifyCMS

[![devDependency Status](https://david-dm.org/zurb/foundation-zurb-template/dev-status.svg)](https://david-dm.org/zurb/foundation-zurb-template#info=devDependencies)

Gulp-powered build system:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with Webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript module bundling with webpack
  - Image compression

### Installation

To use this, your computer needs:

- [NodeJS](https://nodejs.org/en/) (Version 6 or greater recommended, tested with 6.11.4 and 8.12.0)
- [Git](https://git-scm.com/)
- Install the Foundation CLI globally

#### Using the CLI

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Now `cd` to your project and to start your project run

```bash
foundation watch
```

To create compressed, production-ready assets, run `gulp build`. Though repository is connected to Netlify so **any push to master branch triggers this command.**
