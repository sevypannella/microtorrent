# microtorrent
Very simple and small database-less PHP torrent tracker.

## Note
"Public trackers" or "open trackers" are special type of software that assists in the communication between peers using the BitTorrent protocol. They can be used by anyone by adding the tracker address to an existing torrent, or they can be used by any newly created torrent, like <a href="//openbittorrent.com" target="_blank">OpenBitTorrent</a>.
<a href="//thepiratebay.org" target="_blank">The Pirate Bay</a> for instance operated one of the most popular public trackers until shutting it down in 2009 amid legal trouble even though the service was absolutely legal since the responsibility of distributing content is solely from the peers. Thereafter The Purate Bay offered only magnet links leading to the "distributed hash table" peering system.
Since the creation of the distributed hash table (DHT) method for "trackerless torrents", BitTorrent trackers have largely become redundant, however, they are still often included with torrents to improve the speed of peer discovery. That's where <a href="">MicroTorrent</a> comes useful:
* To track private torrent files (with DHT unflagged) distributed among few peers
* To track public torrent files (with DHT flagged) by improoving the peer discovery speed
* To track public torrent files by helping out the oversaturated big ones

Immagine an Internet where every seeder runs his own micro tracker and you'll understand my point of view. :)
