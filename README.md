# spa
a CLI controller for spotify on MacOS

- no premium subscription required
- can search for songs/albums/playlists/artists & control spotify
- uses native macos applescript apis

## install
1. go to https://developer.spotify.com/dashboard/applications and create an app
2. put the client ID in the SPA_ID variable
3. and the client secret in SPA_SECRET
4. put those variables in ~/.config/spa/keys, so that spa can use them.
5. put `spa` in your path!

**don't export them!** any program would be able to access them that way. 

Inspired by sp for linux
https://gist.github.com/wandernauta/6800547

Licensed under the MIT license (included in script)
