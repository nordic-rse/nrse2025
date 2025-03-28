# 2025 Nordic-RSE conference

Website for the 2025 Nordic-RSE conference. Based on the [zeppelin template](https://github.com/gdg-x/zeppelin).


## Local preview

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).

```bash
    gem install bundler
```

and run next command from root folder:

```bash
  bundle install
```

To start Jekyll run:

```bash
    jekyll serve -w
```

Site will be available at http://127.0.0.1:4000/zeppelin/ or http://localhost:4000/zeppelin/ (on Windows)

**NOTE:** in this mode all changes to html and data files will be automatically regenerated, but after changing `_config.yml` you have to restart server.


## Sass(Compass) support

**Note:** You need to install [Node.js](http://nodejs.org/download/)

To watch changes of `.sass` files and compile it to the `.css` on a fly change property `safe: true` to `safe: false` in `_config.yml`.
**Note: It works only on local machine, because GitHub runs Jekyll in `--save` [mode](https://help.github.com/articles/using-jekyll-with-pages/#configuration-overrides)**

Learn more about Sass development from [documentation](https://github.com/gdg-x/zeppelin/wiki/Sass-development).


## Documentation

Quick-start guide is not enough? Checkout [full documentation](https://github.com/gdg-x/zeppelin/wiki).


## Used libraries

- [Bootstrap](https://github.com/twbs/bootstrap)
- [Animate.css](https://github.com/daneden/animate.css)
- [Waves](https://github.com/publicis-indonesia/Waves)
- [jquery.appear](https://github.com/bas2k/jquery.appear)
- [jQuery countTo Plugin](https://github.com/mhuggins/jquery-countTo)
- [Typed.js](https://github.com/mattboldt/typed.js)
- [Sticky-kit](https://github.com/leafo/sticky-kit)


## License

Project is published under the [MIT license](https://github.com/gdg-x/zeppelin/blob/master/LICENSE.txt). Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)
