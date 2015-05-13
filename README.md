This is a demonstration repository showing that component-scoped CSS thanks to [`ember-component-css`](https://github.com/ebryn/ember-component-css) is not working on Heroku when deployed with [`heroku-buildpack-ember-cli`](https://github.com/tonycoco/heroku-buildpack-ember-cli).

You can visit a Heroku deployment at [http://ember-component-css-heroku.herokuapp.com](http://ember-component-css-heroku.herokuapp.com). The names [should be bold](app/components/name-badge/styles.css) but are not.
