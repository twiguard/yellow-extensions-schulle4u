<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a></p>

# Twitter 0.8.7

Embed Twitter messages.

<p align="center"><img src="twitter-screenshot.png?raw=true" alt="Screenshot"></p>

## How to install an extension

[Download ZIP file](https://github.com/datenstrom/yellow-extensions/raw/main/downloads/twitter.zip) and copy it into your `system/extensions` folder. [Learn more about extensions](https://github.com/annaesvensson/yellow-update).

## How to embed a message

Create a `[twitter]` shortcut. 

The following arguments are available, all but the first argument are optional:
 
`Id` = last part of a [Twitter](https://www.twitter.com) link, e.g. `https://twitter.com/dog_feelings/status/1169078881963261953`  
`Theme` = message theme, e.g. `light`, `dark`  
`Style` = message style, e.g. `left`, `center`, `right`  
`Width` = message width, pixel or percent  
`Height` = message height, pixel or percent  

You should know that the service provider collects personal data and uses cookies.

## Examples

Embedding a tweet:

    [twitter 1169078881963261953]

Embedding a tweet, different theme and style:

    [twitter 1169078881963261953 dark]
    [twitter 1169078881963261953 light right]

Embedding a timeline:

    [twitter dog_feelings]

Embedding a timeline, different theme and dimensions:

    [twitter dog_feelings/likes]
    [twitter dog_feelings/likes light - 250 250]

Embedding a follow button:

    [twitterfollow dog_feelings]

## Settings

The following settings can be configured in file `system/extensions/yellow-system.ini`:

`TwitterTheme` = message theme, e.g. `light`, `dark`  

## Acknowledgements

Thanks to Datenstrom for intermediately developing and maintaining this extension!

This extension uses [Twitter](https://www.twitter.com). Thanks for the free service.

## Developer

Steffen Schultz. [Get help](https://datenstrom.se/yellow/help/).
