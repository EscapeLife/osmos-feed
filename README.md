# Osmos Feed

> **This is repository hosts the UI and content of an RSS feed reader.**

- `https://www.escapelife.site/osmos-feed`

## Configure Subscription

> **project configuration and usage instructions**

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

## Find/Add New Feeds

> **reference the [RSS Aggregator for Web3](https://github.com/chainfeeds/RSSAggregatorforWeb3)**

Medium, Github, Substack, Mirror, Ghost are natively support RSS, For example:

- GitHub: Appending ".atom" to most link
  - e.g. `https://github.com/bitcoin/bitcoin/releases.atom`
- Substack: Appending "/feed" to link
  - e.g. `https://0xsoros.substack.com/feed`
- Mirror: Appending "/feed/atom" to link
  - e.g. `https://ens.mirror.xyz/feed/atom`
- Ghost: Appending "/rss" to link
  - e.g. `https://fuel-labs.ghost.io/rss/`
- Medium: Adding "/feed" after medium.com
  - e.g. `https://medium.com/feed/anomanetwork`

For other sites or sources, you can find many great tutorials from [ALL About RSS](https://github.com/AboutRSS/ALL-about-RSS) or [RSSHub](https://github.com/DIYgod/RSSHub).

## Links and References

> **roses, hands have lingering fragrance**

- [How does it work?](https://github.com/osmoscraft/osmosfeed#osmosfeed)
- [File an issue about the template](https://github.com/osmoscraft/osmosfeed-template)
- [File an issue about the tool](https://github.com/osmoscraft/osmosfeed)
- [Latest documentation](https://github.com/osmoscraft/osmosfeed)
