![](http://puu.sh/94QI3.png)

**UPDATE:** This project has been discontinued - you can still use it and recommend it to friends, but there may not be any further support.  However, development on a successor, [cashmere](https://github.com/pixeldesu/cashmere/), has begun.

A CSS modification for the popular Twitter client 'TweetDeck'

**WARNING:** This modification cannot be applied directly *without* a plugin for your browser that allows userstyles on certain webpages. I would recommend [Stylish/userstyles.org](http://userstyles.org/).

## Requirements

* Any browser that is not Internet Explorer, *I highly doubt it will work there.*
* A plugin that provides support for userstyles

## Installation

These instructions are for Stylish on [Chromium-based browsers (like Chrome)](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) and [Mozilla-based browsers (like Firefox)](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome). Steps will vary based on browser and plugin.

### How to add a new style

* Click on the Stylish icon.
* Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
* Click on "Write New Style"

### How to install this style

* Name the Style anything you want, but something easy to recognise like *Modernized TweetDeck* would be good.
* (Chrome only) Create a rule pointing to `URLs starting with` `https://tweetdeck.twitter.com`.
* (Firefox only) Add the following into the textbox, on a single line: 
* `@-moz-document url-prefix("https://tweetdeck.twitter.com") {`.
* Paste the text from `style.css` into the textbox, below the `@moz-document...` line if you have one.
* (Firefox only) Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
* Click on **Save** and look at TweetDeck!

### How to use a custom loading image

Follow the above steps, but open the theme in Stylish afterwards and do the following:

* Upload your image to a host where it will stay up permanently
* Copy the URL and paste it into the line starting `background-image: url(` where the default URL is.
* Click on save.
* Notice the changes on refresh!

## Roadmap

### General Style

* [x] Flat style
* [x] Removed paddings, *more content displayed*
* [x] New font and Unicode support
* [x] Header for 'New Tweet'
* [x] Circled images
* [x] Resized column headers

### Tweet Status (Favorite/Retweet/Both)

* [x] Dogears displaying tweet status changed to a bar on the right-hand side (yellow = favorite, green = retweet, blue = both)
* [x] Links are now colored in the corresponding status color

### Icon Replaces

* [x] New Tweets sprite replaced with CSS-line/border

### Special

* [x] Support for custom loading background!

### Planned

* [ ] Profile redesign
