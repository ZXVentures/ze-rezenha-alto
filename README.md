# ReZÉnha's Alto

A clean, minimalist theme featuring a light and dark mode with Zé Delivery style.

**Demo: https://rezenha.ze.delivery**

&nbsp;

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev

# Open your browser at http://localhost/ghost and create an account

# Activate the ze-resenha-alto theme at the Design section
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.
To update the locale files you need to update the locale at Ghost Admin -> General and will probably need to restart the docker container.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

# PostCSS Features Used

-   Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.

# Copyright & License

Copyright (c) 2013-2020 Ghost Foundation - Released under the [MIT license](LICENSE).
