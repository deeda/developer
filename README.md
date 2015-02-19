***Please use develop branch for in progress changes and when ready merge them to gh-pages branch***

Read the docs: http://bruth.github.io/jekyll-docs-template


### Get Started

Start by [creating a new post](http://jekyllrb.com/docs/posts/) one of the categories listed in `_config.yml`. It will appear in the navigation on the left once recompiled. Or use the supplied script to make creating pages easier:

```bash
ruby bin/jekyll-page "Some Page Title" ref
```

To run it locally - simple run jekyll locally
```bash
jekyll serve
```

#### Don't Forget

- Add your own content to this page (i.e. `index.md`) and change the `title`
- Change `title` and `subtitle` defined in `config.yml` for your site
- Set the `baseurl` in `_config.yml` for your repo if deploying to GitHub pages

#### Modifying css/js/html templates

Don't change anything in `_includes/`, `_layouts/`, `_css/`, or `_js/` -- they are all generated from source files inside `_build/`.

```
cd _build
npm install
npm start
```
