# MyUW Pattern Lab

The MyUW Pattern Lab is based on [Pattern Lab Node - Gulp Edition](https://github.com/pattern-lab/edition-node-gulp) with the [Mustache Demo Starterkit](https://github.com/pattern-lab/starterkit-mustache-demo).



## Packaged Components

### Pattern Lab Gulp Edition
The Pattern Lab Gulp Edition comes with the following components:

* `patternlab-node`: [GitHub](https://github.com/pattern-lab/patternlab-node), [npm](https://www.npmjs.com/package/patternlab-node)
* `patternengine-node-mustache`: [GitHub](https://github.com/pattern-lab/patternengine-node-mustache), [npm](https://www.npmjs.com/package/patternengine-node-mustache)
* `pattern-lab/styleguidekit-assets-default`: [GitHub](https://github.com/pattern-lab/styleguidekit-assets-default)
* `pattern-lab/styleguidekit-mustache-default`: [GitHub](https://github.com/pattern-lab/styleguidekit-mustache-default)

### Other Libraries

* LESS CSS: [GitHub](https://github.com/less/less.js)
* Bootstrap: [GitHub](https://github.com/twbs/bootstrap)

### Fonts

* Font Awesome: [GitHub](https://github.com/FortAwesome/Font-Awesome)
* [Encode Sans Normal (Semibold and Bold)](https://www.fontsquirrel.com/fonts/encode-sans)


## Prerequisites

The Pattern Lab Node - Gulp Edition uses [Node](https://nodejs.org) for core processing, [npm](https://www.npmjs.com/) to manage project dependencies, and [gulp.js](http://gulpjs.com/) to run tasks and interface with the core library. Node version 4 or higher suffices. You can follow the directions for [installing Node](https://nodejs.org/en/download/) on the Node website if you haven't done so already. Installation of Node will include npm.

It's also highly recommended that you [install gulp](hhttps://github.com/gulpjs/gulp/blob/4.0/docs/getting-started.md) globally.

> Note: The Gulp Edition of Pattern Lab uses Gulp 4, which may require a new global install of the Gulp command line interface. Follow the [gulp upgrade instructions](https://github.com/pattern-lab/edition-node-gulp/wiki/Updating-to-Gulp-4) if you already have gulp installed and need to upgrade. Gulp 4 is in alpha, but brings many benefits to the table and is relatively stable. You can alternatively [run with local gulp instead of global gulp](https://github.com/pattern-lab/patternlab-node/wiki/Running-with-Local-Gulp-Instead-of-Global-Gulp), but commands are a bit more verbose. The rest of this documentation assumes a global install.

## Installing

1. Download or 'git clone' this repository to an install location
2. run the following

    ```
    cd install-location
    npm install
    ```

Running `npm install` from a directory containing a `package.json` file will download all dependencies defined within.

Note: `npm` is a dependency management and package system which can pull in all of the Gulp Edition's dependencies for you.



## Helpful Commands

These are some helpful commands you can use on the command line for working with Pattern Lab.

> Reminder: These commands assume a global installation of gulp 4.X, instead of a local installation. Depending on your preference, you may need to [upgrade your global version of gulp](https://github.com/pattern-lab/edition-node-gulp/wiki/Updating-to-Gulp-4) or [run with local gulp](https://github.com/pattern-lab/patternlab-node/wiki/Running-with-Local-Gulp-Instead-of-Global-Gulp).

### List all of the available commands

To list all available commands type:

    gulp patternlab:help

### Generate Pattern Lab

To generate the front-end for Pattern Lab type:

    gulp patternlab:build

### Watch for changes and re-generate Pattern Lab

To watch for changes, re-generate the front-end, and server it via a BrowserSync server,  type:

    gulp patternlab:serve

BrowserSync should open [http://localhost:3000](http://localhost:3000) in your browser.
