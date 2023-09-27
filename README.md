# Roblox Spotify Rich Presence
Displays what you're listening to on Spotify in your Roblox profile

# How to use
- Create an app at: https://developer.spotify.com/dashboard/applications
- Redirect URI should be `http://localhost:5000/callback` and you can use whatever name/description you want, save when you're done
- Choose the app you made and click settings
- You will find Client ID and Client Secret under Basic Information, copy them to your `config.json` file
- To get your Roblox cookie install a [Cookie Editor extension](https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) from your browser's web store, log in to your Roblox account if you haven't already, click on the extension and you should see ".ROBLOSECURITY". Copy and paste its value to your `config.json` file
- Once you're done, make sure your PIN code is disabled from Roblox settings then run rospotify.exe and visit the prompted URL to connect Spotify
- Play a song and your Roblox bio should change automatically to whatever you're listening to in real time.
