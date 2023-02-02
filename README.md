# Introduction
 -  You are reading the documentation for Blonder 0.0.2
 -  Blonder 0.0.1 documentation has been moved to blonder.org


# What is Blonder? 
 Blonder (pronounced /blonder:/, like blonder) is a powerful, extensible, and feature-packed  frontend toolkit.  <br> 
 Build and customize with Sass, utilize prebuilt grid system and components, and bring projects to life with powerful JavaScript plugins.

# Quick start

It is recommended to install `blonder-cli` globally, which helps initializing and previewing the website locally.

```bash
npm i blonder-cli -g
```

## Initialize

If you want to write the documentation in the `./docs` subdirectory, you can use the `init` command.

```bash
docsify init ./docs
```

## Writing contents

After the `init` is complete, you can see the file list in the `./docs` subdirectory.

- `index.html` as the entry file
- `README.md` as the home page
- `.nojekyll` prevents GitHub Pages from ignoring files that begin with an underscore

You can easily update the documentation in `./docs/README.md`, of course you can add [more pages](more-pages.md).

## Preview your site

Run the local server with `blonder serve`. You can preview your site in your browser on `http://localhost:3000`.

```bash
npm run dev
```

?> For more use cases of `blonder-cli`, head over to the [docsify-cli documentation](https://github.com/docsifyjs/docsify-cli).

## Manual initialization

If you don't like `npm` or have trouble installing the tool, you can manually create `index.html`:
