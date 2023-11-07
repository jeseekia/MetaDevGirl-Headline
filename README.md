# MetaDevGirl Headline

This is a theme based on Ghost CMS Headline. Although it is not a direct fork of the repository, it is maintained with the original repository as an upstream source for on-going changes.

The original README for Headline can be found as [Headline-README.md](/Headline-README.md)

# Setup

## Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/headline.zip`, which you can then upload to your site.

```bash
yarn zip
```



# Features

## Base features
- Primary Sections (Homepage)
- Secondary Sections (Homepage)

## Extended features
- [ ] Featured section (Homepage)
- [ ] Live stream section (Homepage)