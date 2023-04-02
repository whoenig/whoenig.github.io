# Personal Webpage of Wolfgang Hönig

The webpage uses the static site generator [Jekyll](https://jekyllrb.com/) with a custom theme based on the CSS framework [Bulma](https://bulma.io/).
For publication generation, we rely on the [Jekyll-Scholar](https://github.com/inukshuk/jekyll-scholar) plugin and the page is automatically deployed
on github using [jekyll-action](https://github.com/helaili/jekyll-action).

## Initial Set Up

Follow instruction on https://jekyllrb.com/docs/installation/ubuntu/, i.e., install ruby and then use

```
gem install jekyll bundler
```

## Building/Testing

```
jekyll serve
```

And go to `http://localhost:4000` in your browser. The page will automatically update, unless `_config.yml` is changed (in which case you have to restart jekyll).

## Deployment

Simply push to the main branch. The site will be deployed automatically.
