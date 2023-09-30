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

## usage
```
A CLI to control spotify on MacOS

spa <song> - alias for 'spa search -t $*'
             so 'spa many words in song name' will work

spa play   - resumes playback of track
spa pause  - pauses track
spa toggle - toggles play/pause on a track
spa skip   - skip track
spa prev   - goes to previous track

spa info   - prints title and artist of track
spa art    - gets the url for the track art
spa name   - gets the name of the track
spa artist - gets the name of the artist of the track

spa search - searches for tracks/albums/artists/playlists
           - use -t/-l/-a/-p flag before the search
```
