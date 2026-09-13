ZynyRing

I made this custom radial menu script myself to make launching apps, handling shortcuts, controlling system volume, and managing media playback much easier while using my PC. It is designed to work seamlessly with extra side buttons on gaming mice (such as Attack Shark X3, X11, R11, and similar multi-button mice).

Features

- Radial Navigation: Pops up right at your cursor position when triggered.
- Context-Aware Actions: You can configure shortcuts to only show up when a specific application is active (like SolidWorks).
- Media Integration: Built-in Spotify and media controls with real-time track info and album art rotation.
- Volume Control: Adjust your system volume quickly by scrolling your mouse wheel while the menu is open.
- Mouse Compatibility: Optimized for extra side buttons (X1/X2) on popular gaming mice like Attack Shark models.

How to Set It Up

1. Make sure you have Python installed along with the required libraries (PyQt6, pynput, pycaw, comtypes, and winsdk).
2. Clone or download this repository to your computer.
3. Place your icon image files (like SolidWorks or Spotify icons) in the same directory as the script.
4. Run the script using Python:
   python script.py

How to Customize

If you want to change the buttons, shortcuts, or applications in the menu, open up the script and look at the ACTIONS list right at the top. You can adjust the following parameters for each item:

- 'label': The text or symbol shown for the action.
- 'icon': The file path to the icon image you want to display.
- 'type': Set to 'app' if you want to launch a program, or 'key' if you want to trigger a keyboard shortcut.
- 'cmd': The path to your file or shortcut link, or the specific key combination you want to use (such as 'ctrl+c' or 'f21').
- 'target_app': The executable name of the app where this button should be active (use 'Altijd' if you want it to show up everywhere).
- 'is_spotify': Set to True if you want to enable the sub-menu controls for media playback.

STILL IN BETA BTW
