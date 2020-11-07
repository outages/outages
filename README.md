# The Outages Project

The Outages Project tracks outages and status via a technique known as "git-scraping", which means that we scrape or pull the original data, and store the historical data as Git history.

This is possible because of the kind availability of Github Actions for open source projects such as these.

## How to contribute

1. Improve existing repositories by making data easier to re-use. Date and times can be particularly challenging to work with as each repository will have its own format really.
2. Add new resources to the project. To do so, you can use the [`outages-scaffold`](https://github.com/outages/scaffold) package.

## Credits

The [Outages Project](https://github.com/outages) ~~inspired by~~ copied from [Simon Willison's project tracking
Californian Fires](https://simonwillison.net/2020/Oct/9/git-scraping/). Simon has a good writeup on how he built
that project on [his blog](https://simonwillison.net/2020/Oct/9/git-scraping/) and there is a broader discussion of
the topic on [Hacker News](https://news.ycombinator.com/item?id=24732943) if you want more background.
