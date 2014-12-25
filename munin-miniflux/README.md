# munin-miniflux

This is a munin wildcard plugin to draw graphs of your miniflux read and unread count.

## Dependencies
- Python 3
- [Requests](http://docs.python-requests.org/) (This could be removed if rewritten with `urllib`

## Configuration
Make sure to edit `munin-miniflux_` and customize your miniflux API credentials (username, token, endpoint)

## Installation
- Clone repository
- Create a link to:
	- `/etc/munin/plugins/munin-miniflux_read` 
	- `/etc/munin/plugins/munin-miniflux_unread`

## Screenshot

![Screenshot](https://img.notmyhostna.me/0ab8fddbfd49f170298c0177b0a38563cd4e7bc3.png)