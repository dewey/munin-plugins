# munin-miniflux

This is a munin wildcard plugin to draw graphs of your miniflux read and unread count.

## Dependencies
- Python 3
- [Requests](http://docs.python-requests.org/) (This could be removed if rewritten with `urllib`

## Configuration
Make sure to edit `munin-miniflux_` and customize your miniflux API credentials (username, token, endpoint)

## Installation
- Clone repository
- Create a link to `/etc/munin/plugins/munin_miniflux_read` and/or `/etc/munin/plugins/munin_miniflux_unread`