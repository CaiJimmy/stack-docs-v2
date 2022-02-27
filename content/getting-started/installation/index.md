---
title: Installation
---

## Requirements

Hugo Extended ≥ 0.87.0.

## Installation

The last release of this theme can be found on this page: [Releases](https://github.com/CaiJimmy/hugo-theme-stack/releases)

If you want to try out the latest feature, you can download the theme executing the next Git clone command on your Hugo site folder.

You can also download this theme **using Git** \(recommended\), execute the following command under your Hugo site folder:

```bash
git clone https://github.com/CaiJimmy/hugo-theme-stack/ themes/hugo-theme-stack
```

If you are using **Git to manage your Hugo site**, add this theme as a submodule.

```sh
git submodule add https://github.com/CaiJimmy/hugo-theme-stack/ themes/hugo-theme-stack
```

## Configuration and site startup

If it's your first time using this theme, take a look at `exampleSite` folder, which includes an example `config.yaml` with all available parameters.

> Remove `config.toml` from your site folder.

In case this is your first time using Hugo, I recommend you copy the content of `exampleSite` to your Hugo site folder. (It includes a set of example posts.)

The demo site is built using content included in `exampleSite`: [https://demo.stack.jimmycai.com/](https://demo.stack.jimmycai.com/)

Once you've done that, execute `hugo server` in your terminal. You should be able to visualize the theme on `http://localhost:1313`.

> For more information about Hugo's functionality, check [official documentation of Hugo](https://gohugo.io/documentation/).
