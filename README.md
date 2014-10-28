Live-IL: M3U Playlist for Israeli TV Channels and Radio Stations
---------------------------------------------------
**This updated unified tv & radio project still in its early days so more changes will come (including playlist addresses) and there might be few issues. The updated project publish in its current state in order to recieve responses and suggestions.**

###About
This playlist was constructed for Kodi's IPTVSimple PVR addon, but will might work in your favorite player.  
Playlists with channels/stations listing in Hebrew and Latin cases are provided.  
Logos for the stations available [logos-il](https://github.com/kodi-il/logos-il), feel free to contribute.    

####Disclaimer and disclosure
* All the links in the playlist are official streams from the official channels' sites or mobile apps.
* There are no un-official streams, streams that are not offered freely and violate copyrights or links that evading geo-restriction of official streams
* The playlist might include some foreign channels streams, the premise behind the inclusion of such streams is that if the stream isn't geo-restricted then it's allowed to play it outside its country of origin and also to link it in this playlist.

###Installation instructions

* Go to IPTVSimple configuration.
* Enter the m3u link, for example: http://live.xbmc-il.com
* Enter the logos base link: http://logos.xbmc-il.com
* Save the changes, enable the addon and enable XBMC's PVR function.

#####Instructions for other players than Kodi
* A player which supports m3u playlists is required.
* Most of the streams are HLS (m3u8), a player that supports this protocol is needed. It's recommened to choose a player which is based on MPlayer (which use FFmpeg to plays the HLS stream), **ATM stay away from VLC**.
* To always get the most updated revision of the playlist: Create a text file with .m3u suffix which content is one of the links to the playlists.

###Playlists links

These are live updating links to the playlists.
#####TV channels and radio stations combined playlist
* Hebrew listing: http://live.xbmc-il.com
* English listing: http://live.xbmc-il.com/en
#####TV channels only playlist
* Hebrew listing: http://tv.xbmc-il.com  
* English listing: http://tv.xbmc-il.com/en
#####Radio stations only playlist
* Hebrew listing: http://fm.xbmc-il.com  
* English listing: http://fm.xbmc-il.com/en

###Known issues and limitations

* When more than one pvr clients are enabled, Kodi might not show channels from a client that its initialization is cosiderably longer due to a [bug in Kodi](http://trac.xbmc.org/ticket/14498), for example when using both IPTVSimple and Tvheadend.
* Most of the streams are HLS (m3u8) which supported well only by player that use FFmpeg to play HLS streams, other might not work at all.
* Most of the Israeli TV channels are geo-restricted, meaning in order to play the streams one need to have an Israeli IP address.

###Contact
You are free to contact by opening an issue or if the nature of your query is private then you're welcome to mail xbmc.il.com@gmail.com

####Read this before trying to contact:
* **Do not ask for un-official streams, streams that are not offered freely and violate copyrights or links that are evading geo-restriction of official streams!**
* Do no report an issue with a stream if your IP address is recognized as an Israeli IP.
* If you're a TV service provider and you find one or more link to a channel stream as breaching your contract with a content provider / TV channel to broadcast the channel locally, then please contact the content provider / TV channel directly to geo-restrict the stream. The playlist contains only official streams without any manipulation to bypass geo-restricted streams.