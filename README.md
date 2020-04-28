# Casper for Micro Acquisitions

The default theme for [Ghost](http://github.com/tryghost/ghost/), Casper. Modified for the Micro Acquisitions blog.

If you want the latest release of Casper, [go here](https://github.com/TryGhost/Casper/releases).

# Development

Casper styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# install dependencies
yarn install

# run development server
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

# Development for Micro Acquisitions blog
To bump the Micro Acquisitions blog with the latest styles in this repo:

1. make changes
2. yarn dev (to build new CSS)
3. git commit/push
4. copy latest git hash (git log)
5. paste into forkequity/ma-blog repo > package.json casper following `.git#`

# Copyright & License

Copyright (c) 2013-2020 Ghost Foundation - Released under the [MIT license](LICENSE).
