## ToDo: Port to MAC, work with spotify specifically
 - https://code.likeagirl.io/how-i-wrote-my-first-google-chrome-extension-using-spotifys-api-90de4ffc6ef3
 - https://blog.xamarin.com/building-your-first-macos-app/
 - https://stackoverflow.com/questions/41649874/how-to-detect-if-a-chrome-tab-is-playing-audio
 - https://developer.chrome.com/extensions/tabs (audible boolean on Tabs API for chrome)

# AwkwardSilence

### Background 
I made this program for some people over at [/r/nfl](https://www.reddit.com/r/nfl) who wanted music to play when the there was a break in the game they were watching.

The program basically starts the audio from a given sound source when all other sound sources are quiet and stops the given sound source when other sound sources are playing. There is user customizable tolerance levels and delays.

### Build
Requires the [cscore audio lib.](https://cscore.codeplex.com/)
