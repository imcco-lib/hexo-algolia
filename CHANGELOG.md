# hexo-algolia changelog

## v1.2.0, 2017-08-25

- remove chunk size from options — the default was decreased from `5000` to `50` items at a time
- index pages along with publishedPosts in the index ([#21](https://github.com/oncletom/hexo-algolia/pull/21), [#18](https://github.com/oncletom/hexo-algolia/issues/18))
- fix helper name in docs ([#16](https://github.com/oncletom/hexo-algolia/pull/16))

## v1.1.0, 2017-06-08

- add `algolia_search()`, `algolia_search_cdn()` and `algolia_search_config()` hexo helpers ([#13](https://github.com/oncletom/hexo-algolia/pull/13))

## v1.0.1, 2017-06-01

- node>=4.0.0 jshint compat

## v1.0.0, 2017-06-01

- rename flags, remove AdminAPIKey from config and document things a bit more