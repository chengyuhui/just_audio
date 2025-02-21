# just_audio_windows

The windows implementation of [`just_audio`](https://pub.dev/packages/just_audio)

## Features

| Feature                        |   Windows    | Description                                                                       |
| ------------------------------ | :----------: | --------------------------------------------------------------------------------- |
| read from URL                  |      ✅      |                                                                                   |
| read from file                 | (not tested) |                                                                                   |
| read from asset                | (not tested) |                                                                                   |
| read from byte stream          | (not tested) |                                                                                   |
| request headers                |              |                                                                                   |
| DASH                           |      ✅      | [Dash profile support](https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/dash-profile-support) |
| HLS                            |      ✅      | [Hsl tag support](https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/hls-tag-support) |
| ICY metadata                   |              | |
| buffer status/position         |      ✅      | |
| play/pause/seek                |      ✅      | |
| set volume/speed               |      ✅      | |
| clip audio                     |              | |
| playlists                      |              | |
| looping/shuffling              |              | |
| compose audio                  |              | |
| gapless playback               |      ✅      | |
| report player errors           |      ✅      | | 
| handle phonecall interruptions |              ||
| buffering/loading options      |              | |
| set pitch                      |      ✅      | |
| skip silence                   |              | |
| equalizer                      |              | |
| volume boost                   |              || 

## Player error codes

- `unknown`
- `abort`
- `networkError`
- `decodingError`
- `sourceNotSupported`