<p align="center">
  <img src="https://raw.githubusercontent.com/lz42/pile/master/static/icons/pile.png" width="200px" alt="">
</p>

<p align="center">
  <a href="https://travis-ci.org/lz42/pile">
    <img src="https://travis-ci.org/lz42/pile.svg?branch=master" alt="">
  </a>
  <a href="https://github.com/lz42/pile/releases">
    <img src="https://img.shields.io/github/release/lz42/pile.svg" alt="">
  </a>
  <a href="http://perso.crans.org/besson/LICENSE.html">
    <img src="https://img.shields.io/badge/License-GPLv3-green.svg" alt="">
  </a>
</p>

# Pile

> Organize your piled work at one place.

[README](https://github.com/mtobeiyf/pile/blob/master/README.md) | [中文说明](https://github.com/mtobeiyf/pile/blob/master/docs/README_zh.md)

<p align="center">
  <img src="https://user-images.githubusercontent.com/5097752/37512418-14efa934-293d-11e8-89d8-4038e1235ba0.png" width="600px" alt="">
</p>

## Why Pile?

The way we get things done is often project-oriented. However, the files, applications, tasklists, etc. are **scattered everywhere**. Pile is a place for you to **put them all together**.

## Usage

Before we get started, let me help you get it more clear how to use Pile.

### Board

A board (or tab) is a place to hold all the resources of your **project** or **workspace**. You can organize your things related to the project/workspace using *hubs*.

### Hub

A hub (or card) is an area for specific stuff. There are currently three kinds of hubs:

#### App/File

You can add apps or files you may use in this area so that you can quickly access them and open them.

<p align="center">
  <img src="https://user-images.githubusercontent.com/5097752/37556606-908ce60a-2a33-11e8-8e3e-7e96fadc1b13.gif" width="700px" alt="">
</p>

#### Notes

Online resources (often appeared as links) or your thoughts can be taken down here. **Markdown** is supported! :tada:

<p align="center">
  <img src="https://user-images.githubusercontent.com/5097752/37556612-995ba5f0-2a33-11e8-8904-9da862f47c07.jpg" width="700px" alt="">
</p>

#### Todo

A simple todolist related to the project.

<p align="center">
  <img src="https://user-images.githubusercontent.com/5097752/37556613-9b643f2e-2a33-11e8-9c7c-9fdd9080aa6a.jpg" width="700px" alt="">
</p>

## Features

- Drag and drop, easy and convenient.
- Various application scenarios.
- Endless possibilities. Developer, designer, writer...
- Pin your workspace/project to your desktop.
- Markdown support, emoji included.

## Installation

:tada: Support Windows/Linux/macOS

### Windows
- Go to the [release page](https://github.com/mtobeiyf/pile/releases)
- Download and run the setup **.exe** file and Pile will be insalled automatically
- Or download the portable **.zip** file, unzip it and run `Pile.exe`

### Linux / macOS
- Go to the [release page](https://github.com/mtobeiyf/pile/releases)
- Linux user: Download **.AppImage** and run it
- Mac user: Download portable **.zip** file or **.dmg** installation file
- You can build by yourself, see [Build Steps](https://github.com/mtobeiyf/pile#user-content-build-setup)

## Technical

### Stack

- [Electron](https://electronjs.org/) : Framework
- [electron-vue](https://github.com/SimulatedGREG/electron-vue) : Skeleton
- [iView](https://www.iviewui.com/) : UI toolkit

### Build Setup

``` bash
# install dependencies
yarn # or npm install

# serve with hot reload at localhost:9080
yarn run dev # or npm run dev

# build electron application for production
yarn run build:dir # or npm run build:dir

```

---

## Changelog

Detailed changes for each release are documented in the [CHANGELOG.md](https://github.com/mtobeiyf/pile/blob/master/docs/CHANGELOG.md)

## Acknowledgment

- [Vue.js](https://vuejs.org/)
- [vue-markdown](https://github.com/miaolz123/vue-markdown)
- [lowdb](https://github.com/typicode/lowdb)
- [Backlog](https://github.com/czytelny/backlog)

## License

Licensed under the [GPL v3.0](https://opensource.org/licenses/GPL-3.0) License.

Copyright (c) 2018 [Fing](http://imfing.com). 
All rights reserved.
