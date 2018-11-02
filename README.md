# My GitHub Pages [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action) [![HitCount](http://hits.dwyl.io/anselhong1445/anselhong1445.github.io.svg)](http://hits.dwyl.io/anselhong1445/anselhong1445.github.io) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

This (https://anselhong1445.github.io/) is my GitHub Pages to manage portfolios, which is powered by **[Jekyll](https://jekyllrb.com)** and **[Leonids](http://renyuanz.github.io/leonids)** (Jekyll theme).

## Quick Overview
### Get Started

```bash
git clone https://github.com/anselhong1445/anselhong1445.github.io
cd anselhong1445.github.io
bundle exec jekyll server
```

(installing Ruby development environment and Jekyll is required in advance, see **[instructions for installation.](https://jekyllrb.com/docs/)**)

Then open http://localhost:4000/ to see the app.

### Editing the App
(while `Jekyll server` is running, it will **automatically build and reload** the files upon any changes you have made to those files.)

#### `_config.yml` file
You could set your own configurations by editing this file as the followings: Site wide configuration, Jekyll configuration, Site Owner configuration...

#### `_site` directory
Do not lay a hand on files in `_site` directory. The files in `_side` directory will be updated by running `Jekyll server` as you have update files in elsewhere. 

**For example**, if you add new image files in `img` directory in `root` directory, `Jekyll server` will duplicate the image files and place it to `img` directory in `_site` directory. Likewise, updates on `resume.html` file in `root` directory will be reflected on `resume.html` in `_site` directory. 

## Lincense

This app is open source software **[licensed as MIT](https://github.com/anselhong1445/anselhong1445.github.io/blob/master/LICENSE.txt)** with the copyright &copy; 2018 **[Sangsik Hong](https://github.com/anselhong1445)** and &copy; 2015 **[Renyuan Zou](https://github.com/renyuanz)**.
