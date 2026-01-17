# **mpv-client**
Remote control script for MPV using the built in JSON IPC

## Usage
#### `./mpv-client -S <path>`
Start mpv at \<path>
<br>
Example: `./mpv-client -S ~/Music`

#### `./mpv-client -a <path>`
Appends \<path> to the end of playlist

#### `./mpv-client -c <path>`
Add \<path> next in the playlist and immediately play it

#### `./mpv-client -q <path>`
Add \<path> next in the playlist

<br>

#### `./mpv-client -s <amount>`
Seek by \<amount> seconds in the current playback

#### `./mpv-client -v <amount>`
Change Volume by \<amount>

<br>

#### `./mpv-client -l`
Toggle Playback Looping

#### `./mpv-client -r`
Restart Playback

#### `./mpv-client -p`
Play Previous

#### `./mpv-client -P`
Toggle Playback

#### `./mpv-client -n`
Play Next
