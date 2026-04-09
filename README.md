# recycle-launcher-lutris-installer
This installer sets up the launcher through Wine and includes a custom URL Handler to allow browser-based logins to communicate with the launcher. It also installs the Windows version of Steam to ensure the launcher detects the necessary services.

After installation, you MUST manually set the Wine version to wine-11.6-amd64 in the Lutris game configuration.

You must use the Windows version of Steam installed inside this prefix. Please exit your native Linux Steam client before starting to prevent errors, as it will not bridge with the launcher.

You must be logged into the Windows Steam client before starting the game through the launcher. If you see "Error Code 5," it means the bridge failed or Steam wasn't ready. If this happens, exit the game and press start in the launcher again; that should fix it.

Visual & Steam Issues:
The launcher window may appear shifted or cut off at the bottom, and the mouse cursor often becomes invisible when hovering over it; however, it remains functional so you can still click "Start."
Please note that the Steam Overlay and the Steam friends list do not work in this environment, but you can use the game's built-in friend management system instead.
