## Slack Now Playing Thing ##

Here's how to hack together a now playing button for Slack (until I can get some more integrations and do it a better way.

### Do this
* Use Slack in a browser  
    *This stuff depends on the use of browser plugins so it'd take more work for this to work in the app*
* Install a Greasemonkey plugin
    * Chrome - [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
* Sign up for a Last.fm [API account](http://www.last.fm/api/account/create)
* Configure your music player (Spotify, probably) to "scrobble" to your Last.fm account
* Install the userscript.js from this repo
* Edit the userscript with your username and API key for last.fm

That should be it.. Now press the music button in Slack to paste your current / last scrobble song to the chat.  

I haven't tested this on anything but Chrome with Spotify so.. feel free to ask any questions or make changes to stuff.
![functional screenshot](https://i.imgur.com/cuqOh8Z.gif)
