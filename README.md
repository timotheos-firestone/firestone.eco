# firestone.eco

## Timotheos Firestone's personal website

This is a static website generated from [Markdown](https://en.wikipedia.org/wiki/Markdown) files using the [Zola](https://www.getzola.org) static website generator.

This repository contains the Markdown content files and the HTML template files required by Zola to generate the website at [firestone.eco](http://firestone.eco). As the files are plain-text, they can be edited in any plain text editor. [Visual Studio Code](https://code.visualstudio.com/) is recommended, and a workspace is provided. This should work on any operating system, but was mainly developed on Linux.

This project assumes that the `zola` binary is placed in the same directory as this `README.md` file. This website was tested with Zola 0.9.0 but newer versions should also work.

Another possibility is installing Zola via `snap`:

    snap install --edge zola

To build the static website, enter the following command into a terminal or command prompt (with this directory as the working directory):

    ./zola build

To serve the website locally, so that it can be viewed locally:

    ./zola serve

Further instructions can be found on [the Zola website](https://www.getzola.org).
