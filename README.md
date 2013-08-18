## Overview

This repo is aiming to mirror Valve's 2013 SDK source with bug fixes and beneficial features included. 

Pull requests for bug fixes are welcome, features which would be beneficial for all 2013 SDK users are also welcome.

## Changes from 2013 SDK

- [John McBroom](https://github.com/jimbomcb)
 - [Fixed client/server gamerules becoming out-of-sync if multiple gamerules are used](https://github.com/jimbomcb/source-sdk-2013/commit/befa1786ce7ed755f331c8897ff9962d082879f9)
 - [Fixed incorrect/non-existent download path, fixes custom sprays & jingles not loading on servers](https://github.com/jimbomcb/source-sdk-2013/commit/64f7ede00ec56583f35a933796423c69b82c50b8)
 - [Reverting Valve changes to cbase.cpp for now, fixes entity I/O on dedicated servers.](https://github.com/jimbomcb/source-sdk-2013/commit/b1d1b3138a566f1f081e272d945bcf4f8ea0ddcb)


- [FlaminSarge](https://github.com/FlaminSarge)
 - [Fixed player jingle functionality](https://github.com/jimbomcb/source-sdk-2013/pull/1)


- [Alan Edwardes](https://github.com/alanedwardes)
 - [Custom URL handlers for the vgui::HTML panel now pass the URL and protocol.](https://github.com/jimbomcb/source-sdk-2013/pull/2)
 - [Changed VBSP to check both the EXECUTABLE_PATH and the MOD path for FDG files.](https://github.com/jimbomcb/source-sdk-2013/pull/3)
