---
label: Command-line arguments
icon: code
order: 800
---

| **Argument**  | **Description**    |
| ------------- |:------------------:|
|-game <game>|  Specifies which game/mod to run. Default is "valve".
|-dev|  Enables developer mode.
|-w <width>| or -width <width>  Forces the engine to start with resolution set to <width>. Ex: -w 1024.
|-h <height>| or -height <height> Forces the engine to start with resolution set to <height>. Ex: -h 768.
|-nosound| Disables sound support.
|-nocdaudio|  Disables mp3 support. Also disallows cd console command to load mp3 tracks.
|-noip|  Disables network support.
|-nojoy|  Disables joystick support.
|-nomouse|  Disables in-game mouse support.
|-nobots|  Disables bots.
|-port <port>|  Specifies which port to use for client connections for a listen server. Default is 27015.
|-exec <file>|  Executes specific config file immediately after the engine is loaded.
|+<console variable> <arg> - |Sets the Cvar (or console variable) to the specified setting.
|-all_languages	|Loads all language files.|
|-allowdebug	|Fakes a debugger for phonehome, and is the same as -dev, unless -nodev is specified.|
|-buildcubemaps	|Builds cubemaps when fully loaded into a map, then quits the game.|
|-console|	Starts the game with the developer console enabled. Same as having con_enable enabled|.
|-defaultgamedir	|Fallback directory if "-game" is not set. Default is "hl2".|
|-demo|	Enters the game into demo mode. Only works for "hl2" and "portal"|
|-dev	|Enables developer mode. Also disables the automatic loading of menu background maps and stops the quit dialog from appearing on exit.|
|-edit|	According to comments, intended to replace -tools. Does nothing except disable all file logging for building reslists.|
|-exit	|Quits the game after fully loading into a map.|
|-forever	|When you get to the end of the maplist, start over from the top|
|-h <height>	|Forces the engine to start with resolution set to <height>. Ex: -h 768|
|-height <height>|	Same as -h|
|-hideconsole	|Forces the console hidden, whatever parameters are passed. This overrides -console, -dev, and all others.|
|-insecure|	Disable Valve Anti Cheat (VAC).|
|-ip|	Does the same as the ipname Cvar|
|-language %l	|Sets the game language to the one specified. (Examples: "english", "german").|
|-mat_vsync|	Enables Vertical Sync|
|-maxdxlevel|	Limits the maximum dxlevel to use. Default is 0.|
|-maxplayers|	Set the maximum players allowed to join the server. This does the same as the maxplayers convar, the maximum you can set it to is limited by the game/mod|
|-nocrashdialog|	Stop some windows crash message boxes from showing up.
|-nodev	|Disables -dev and -allowdebug during startup so sv_cheats and developer mode dosent get set.
|-nodttest|	Skips datatable testing.
|-noip|	Do not bind to an ip and disables all multiplayer support
|-nojoy|	Disables joystick support.
|-nomaster|	Hides server from master serverlist.
|-nomessagebox|	Stop various windows error message boxes from showing up
|-nominidumps|	Dont write minidumps
|-nomouse|	Disables in-game mouse support.
|-nosound|	Disables sound support
|-nosrgb|	Disables support for SRGB.
|-particles	|Sets the number of beam trails to allow (2048 by default, minimum is 512)
|-replay	|Increases maxplayers by 1 at startup and automatically executes replay.cfg for the server.
|-startmap	|Restarts devshot generation at the specified map if resuming from a crash.
|-sv_benchmark|	Enables benchmarking through sv_benchmark_force_start.
|-vguimessages|	Enables debug VGUI messages.
|-w <width>|	Forces the engine to start with resolution set to <width>. Ex: -w 1024
|-width| <width>	Same as -w

