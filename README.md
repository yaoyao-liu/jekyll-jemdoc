## Jekyll + jemdoc

[![LICENSE](https://img.shields.io/github/license/yaoyao-liu/jekyll-jemdoc?style=flat-square&logo=creative-commons&color=EF9421)](https://github.com/yaoyao-liu/jekyll-jemdoc/blob/main/LICENSE)

### Change basic information
Edit this file: [_config.yml](_config.yml)

### Update the index page
Edit this file: [index.md](index.md)

### Update the publication page
Edit this file: [publications.md](publications.md)

### How to add a new page
- Create a new file named 'abc.md'
- Copy the following lines to the new file:
```
---
layout: normal
title: ABC
---
```
- Add your content using Markdown

The link of this page is `abc.html`

### How to change the navigation bar
Edit this file: [_includes/navbar.html](_includes/navbar.html), then the navigation bar on all pages will change
- Add a new item in the navigation bar:
```
<div class="menu-item"><a href="abc.html">ABC</a></div>
```
- Add a new category in the navigation bar:
```
<div class="menu-category">Category ABC</div>
```

### How to add a text block
Add the following lines in the Markdown file:
```
<div class="infoblock">
    <div class="blockcontent">
    <p>Your content</p>
    </div>
</div>
```

### Using Locally with Jekyll

*You need to install [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/) fisrt.*

Install and run:

```bash
bundle install
bundle exec jekyll server
```
View the live page using `localhost`:
<http://localhost:4000>. You can get the html files in `_site` folder.

## Acknowledgements
- [jemdoc](https://github.com/jem/jemdoc)
