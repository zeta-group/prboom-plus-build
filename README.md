# PRBoom+ metabuild

This repository contains all the subrepositories, necessary
to cleanly (and easily) build PRBoom+ from scratch. It uses
the Meson build system, for its powerful and clean subprojects
paradigm.

## How to Build

Make sure Meson and Ninja are installed. And also Git, but
that's obvious.

If you haven't cloned or pulled this repository recursively,
please clone subrepositories with Git:

```sh
git submodule update --init --recursive
```

Then, use Meson to build PrBoom+:

```sh
meson build && ( cd build; ninja )
```