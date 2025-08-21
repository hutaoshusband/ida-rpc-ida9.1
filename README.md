# ida-rpc for IDA 9.0

## About
ida-rpc was a quick test plugin to see what changed in the 7.0 sdk, ~~subsequently it only supports IDA 7.x as of now~~ ~~updated to IDA 9.0,~~, updated to IDA 9.1 
it allows for [discord rich presence](https://discordapp.com/rich-presence) to display information about the current IDA session

## Installation
To install ida-rpc simply copy **ida-rpc64.dll** from the [latest release](https://github.com/shikataganaii/ida-rpc-ida9/releases) to ```ida_install_location/plugins/``` ,
to change options within the plugin open the plugins menu and select IDA RPC ```Edit -> Plugins -> IDA RPC``` or use the default hotkey ```Ctrl-Alt-R```

## Building
To build this solution you'll need to get a copy of the [IDA 9.0 SDK](https://web.archive.org/web/20240810011401if_/https://out5.hex-rays.com/beta90_6ba923/idasdk90.zip), compile in 64bit Release64 and your done!


