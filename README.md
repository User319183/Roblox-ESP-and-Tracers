# ESP and Tracers Script for Roblox

This is a script for Roblox that provides ESP (Extra Sensory Perception) and Tracers functionality. ESP allows you to see other players' names and distances from you through walls and other obstacles. Tracers draw a line from your character to other players, making it easier to locate them.

## Features

- ESP: See other players' names and distances from you.
- Tracers: Draw a line from your character to other players.
- Toggle ESP and Tracers on or off.

## Usage

To use this script, you need to have a Roblox game where you have permissions to run scripts. 

1. Copy the script from the codeblock below
2. Open your Roblox executor. I recommend using Krampus/Ro-exec
3. Paste the script into a Script executor.
3. Run the script. You should see ESP and Tracers in the game and a GUI to toggle them on or off.

## Loading the Script from a URL

You can also load and run the script directly from a URL using the `loadAndRunScript` function:

```lua
function loadAndRunScript(url)
    local HttpService = game:GetService("HttpService")
    local scriptContent = HttpService:HttpGet(url)
    local func = loadstring(scriptContent)
    func()
end

loadAndRunScript("https://raw.githubusercontent.com/User319183/Roblox-ESP-and-Tracers/main/obfuscated.lua")
```

## License

MIT
