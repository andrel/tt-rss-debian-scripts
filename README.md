tt-rss-debian-scripts
=====================

Used for running update background job on Debian.

Based on scripts from http://510x.se/notes/posts/Install_Tiny_Tiny_RSS_on_Debian/, with only minor additions.

Consists of:
  - `/etc/init.d/tt-rss`
  - `/etc/default/tt-rss`

Copy the files to their corresponding place under /etc/.

Edit `/etc/default/tt-rss` to suit your needs.

`sudo chmod 755 /etc/init.d/tt-rss`

`sudo service tt-rss start` starts the daemon.

`sudo service tt-rss stop` stops the daemon.

`sudo update-rc.d tt-rss defaults` run at startup.
