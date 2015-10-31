WP Twitch
=========

Simple embedding of your Twitch stream, which will only show when you're online.

Sample Screenshot
=================

![WP Twitch example](http://wordpresscontent.azurewebsites.net/bertjohnson_com/wp-content/uploads/sites/2/2015/10/wp-twitch.png)

Configuration
=============

To add your Twitch stream, use the following code:

	[twitch channel="twitchchannelname" height="640" height="480"]

The following shortode parameters are supported:

1. **channel**: Name of the Twich user / channel
2. **height**: Height of the stream (e.g., `400px`, `100%`, `2em`)
2. **width**: Width of the stream (e.g., `600px`, `100%`, `2em`)
3. **https**: `yes` or `no`.  By default, content is served over HTTP via Twitch's HTML5 player.  If `yes` is specified, content is delivered via a legacy Flash player seved via Justin.TV's CDN (https://www-cdn.jtvnw.net/swflibs/TwitchPlayer.rfc07d37fc4eed1d17243b452dd3441665496e1e0.swf?channel={$channel}).

License
=======

Copyright © 2015 [Bert Johnson](https://bertjohnson.com)

Licensed according to GPLv2 or later (https://www.gnu.org/licenses/gpl-2.0.html).
