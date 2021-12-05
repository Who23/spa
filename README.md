# spa
a CLI controller for spotify on MacOS

- no premium subscription required
- can search for songs/albums/playlists/artists & control spotify
- uses native macos applescript apis

## install
1. go to https://developer.spotify.com/dashboard/applications and create an app
2. put the client ID in the `SPA_ID` variable
3. and the client secret in `SPA_SECRET`
4. put `spa` in your path!

Consider putting your `SPA_SECERT` behind something like keychain,
since it's otherwise accessible as plain text in `spa`

Inspired by sp for linux
https://gist.github.com/wandernauta/6800547

Licensed under the MIT license (included in script)
