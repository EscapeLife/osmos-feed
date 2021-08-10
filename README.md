# Osmos Feed

> **This is repository hosts the UI and content of an RSS feed reader.**

- `https://www.escapelife.site/osmos-feed`

## configure subscription

- edit osmosfeed.yaml file add feed link addr
- remove # to uncommend the cacheUrl property, replace <github_username> with your GitHub username
- update the items to the sources you want to follow

```yaml
cacheUrl: https://<github_username>.github.io/<repo>/cache.json
sources:
  - href: https://my-rss-source-1/feed/
  - href: https://my-rss-source-2/rss/
  - href: https://my-rss-source-3/feed
  - href: https://my-rss-source-4/news/rss
  - href: https://my-rss-source-5/rss/
```

- click "Commit changes" button
- your feed will be available at https://<github_username>.github.io/<repo>

## links and references

- [How does it work?](https://github.com/osmoscraft/osmosfeed#osmosfeed)
- [File an issue about the template](https://github.com/osmoscraft/osmosfeed-template)
- [File an issue about the tool](https://github.com/osmoscraft/osmosfeed)
- [Lastest documentation](https://github.com/osmoscraft/osmosfeed)
