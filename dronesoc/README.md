# DroneSoc Website

The DroneSoc website, built using [Hugo](https://gohugo.io). The site is statically generated, meaning that a bunch of markdown documents and templates are processed to generate a folder of static HTML/CSS, meaning it can be hosted on any static site hosting such as Github Pages.

## Setup
- Clone this repo
    - `git submodule update --init` to clone the theme
- Install [Hugo](https://gohugo.io) as per instructions on their site.
- `hugo watch -t hugo-lithium-theme` To run a server which rebuilds the site when changes are made to files

## Deployment
- Run `hugo`. This will do a production build of the site into the `public` folder.
- Copy this public folder to whatever hosting we are using. Currently this is github pages, so see the [appropriate repository](https://github.com/dronesoc/dronesoc.github.io).
