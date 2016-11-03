## What is this?

This repository contains the slides for a talk given at a [Dayton Web Developers meetup](https://www.meetup.com/dayton-web-developers/events/226548666/).

## Build

The slides are built using [assemble](https://github.com/assemble/assemble). Run the following command to build the slides into the `_gh_pages` folder:

```bash
$ assemble
```

## Dev

To create a [browser-sync](http://www.browsersync.io/) server and watch the files for changes during development, run the following command:

```bash
$ assemble dev
```

## Deploy

To publish the slides to Github Pages, run the following command:

```bash
$ assemble deploy
```