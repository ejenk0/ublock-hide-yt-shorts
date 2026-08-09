# Hide YouTube Shorts and Playables List

A [uBlock Origin](https://github.com/gorhill/uBlock) filter list to hide all traces of YouTube shorts videos and YouTube Playables.

This is a fork of [gijsdev/ublock-hide-yt-shorts](https://github.com/gijsdev/ublock-hide-yt-shorts), which covers shorts only. Everything above the `!!! PLAYABLES !!!` heading in `list.txt` comes from upstream and is kept in sync with it; the playables rules are additions.

This filter list might work with other content blockers, but that hasn't been looked into.

Copy the link below, go to uBlock Origin > Dashboard > Filter lists, scroll to the bottom, and paste the link underneath the 'Import...' heading:
- [https://raw.githubusercontent.com/ejenk0/ublock-hide-yt-shorts/master/list.txt](ubo:subscribe?location=https://raw.githubusercontent.com/ejenk0/ublock-hide-yt-shorts/master/list.txt)

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md). Note that the "Only include YouTube Shorts" rule applies to upstream; here, playables filters belong in the `!!! PLAYABLES !!!` sections at the bottom of the list so that upstream changes keep merging cleanly.

## License

See [LICENSE.md](LICENSE.md)
