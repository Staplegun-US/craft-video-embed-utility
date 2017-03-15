craft-video-embed-utility
=========================

A Craft CMS plugin providing a Twig filter for converting YouTube, Vimeo and Facebook URLs into an embedded video <iframe> with the necessary settings applied.

## Usage:

Once installed, a `videoEmbed` filter will be available to your templates allowing you to embed a video in your page with just the URL:

    {{https://www.youtube.com/watch?v=6-HUgzYPm9g|videoEmbed}}

The filter also allows you to provide querystring based embed options as the first argument in the filter:

    {{url|videoEmbed({ byline: 0, autoplay: 1 })}

* [Vimeo embed options](https://developer.vimeo.com/player/embedding).
* [YouTube embed options](https://developers.google.com/youtube/player_parameters).
