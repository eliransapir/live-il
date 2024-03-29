Live-IL: M3U Playlist for Israeli TV Channels and Radio Stations
---------------------------------------------------
**This updated unified tv & radio project still in its early days so more changes will come (including playlist addresses) and there might be few issues. The updated project publish in its current state in order to recieve responses and suggestions.**

###About
This playlist was constructed for Kodi's IPTVSimple PVR addon, but will might work in your favorite player.  
Playlists with channels/stations listing in Hebrew and Latin cases are provided.  
Logos are available [logos-il](https://github.com/kodi-il/logos-il), feel free to contribute.    

####Disclaimer and disclosure
* All the links in the playlist are official streams from the official channels' sites or mobile apps.
* There are no un-official streams, streams that are not offered freely and violate copyrights or links that evading geo-restriction of official streams
* The playlist might include some foreign channels streams, the premise behind the inclusion of such streams is that if the stream isn't geo-restricted then it's allowed to play it outside its country of origin and also to link it in this playlist.

###Installation instructions

* Go to IPTVSimple configuration.
* Enter the m3u link, for example: http://live.kodi-il.tv
* Enter the logos base link: http://logos.kodi-il.tv
* Save the changes, enable the addon and enable Kodi's PVR function.

#####Instructions for other players than Kodi
* A player which supports m3u playlists is required.
* Most of the streams are HLS (m3u8), a player that supports this protocol is needed. It's recommened to choose a player which is based on MPlayer (which use FFmpeg to plays the HLS stream), **ATM stay away from VLC**.
* To always get the most updated revision of the playlist: Create a text file with .m3u suffix which content is a link to a playlist.

###Playlists links

Use one of these links to get the most updated revision of a playlist.

#####TV channels and radio stations combined
* Hebrew listing: http://live.kodi-il.tv
* English listing: http://live.kodi-il.tv/en

#####TV channels only
* Hebrew listing: http://tv.kodi-il.tv
* English listing: http://tv.kodi-il.tv/en

#####Radio stations only
* Hebrew listing: http://fm.kodi-il.tv
* English listing: http://fm.kodi-il.tv/en

###Known issues and limitations

* When more than one pvr clients are enabled, Kodi might not show channels from a client that its initialization is cosiderably longer due to a [bug in Kodi](http://trac.xbmc.org/ticket/14498), for example when using both IPTVSimple and Tvheadend.
* Most of the streams are HLS (m3u8) which supported well only by player that use FFmpeg to play HLS streams, others might not work at all.
* Most of the Israeli TV channels are geo-restricted, meaning in order to play the streams one must have an Israeli IP address.

###Contact
You are welcome to contact by opening an issue or if the nature of your inquiry is private then by mailing to kodi.il.tv@gmail.com.

####Read this before trying to contact:
* **Do not ask for un-official streams, streams that are not offered freely and violate copyrights or links that are evading geo-restriction of official streams!**
* Do no report an issue with a stream if your IP address is not recognized as an Israeli IP.
* If you're a representative of a TV service provider and you find one or more link to a channel stream as breaching your contract with a content provider / TV channel to broadcast the channel locally, then please contact the content provider / TV channel directly to geo-restrict the stream. The playlist contains only official streams without any manipulation to bypass geo-restricted streams.