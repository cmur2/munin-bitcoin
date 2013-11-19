munin-bitcoin
=============

Creates Munin graphs from the data at [bitcoinaverage.com tickers](https://bitcoinaverage.com/) which are extracted
via their [JSON API](https://api.bitcoinaverage.com/ticker/) providing the last price data.

Install
-------

Clone this repository or download the bitcoin_ file and create a
symlink as *root* in /etc/munin/plugins by using e.g.:

	cd /etc/munin/plugins; ln -s /path/to/bitcoin_ bitcoin_<currency>

where <currency> is a currency known to https://api.bitcoinaverage.com/ticker/ like "EUR" or "USD".

**Don't forget to restart your munin-node deamon.**
