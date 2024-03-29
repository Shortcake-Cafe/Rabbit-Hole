![thumbnail](https://github.com/Shortcake-Cafe/Rabbit-Hole/assets/165345800/c2f58e0e-b41f-40c7-8574-f5723cca1115)

# Rabbit Hole Source Code (V. 1.03)
This is the Rabbit Hole source code!

## Links to the game
- [Newgrounds](https://www.newgrounds.com/portal/view/920158)
- [Itch.io](https://shortcake-cafe.itch.io/rabbit-hole)
- [Steam](https://store.steampowered.com/app/2831340/Rabbit_Hole/)

## Community
- [Join the fan Discord!](https://discord.gg/2Kwpd3Mtg6)
## Installing
1. Compress /Rabbit Hole into a zip file.
2. Rename zip file to Rabbit Hole.sb3

## Where to begin?

### 1. Opening the file
Rabbit Hole is an **.sb3** file, which means it is a scratch game, here's the steps you need to take to open it. 
(Skip to **step 4** if you've already done this once)

1. Go to https://turbowarp.org/editor.

2. Go to **Addons > Import** settings and upload **turbowarp-addon-settings.json**

3. Return to the editor and refresh the page.

4. Load **Rabbit Hole.sb3** in Turbowarp, **File > Load from computer**.

### 2. Modding the game
Rabbit Hole has no documentation at the moment. Eventually i'll write up some sort of documentation, I just lack the time at the moment.

This means you are on your own for now. However here's a few tips on where to get started:

- **/Hitboxes/HB_MAIN**
   - Handles all player movement
- **/Player**
   - Handles sprites and visuals for player. This is where you'll add sprites for skins and modded characters.
- **/CharaSelect/CharaEngine**
   - Handles character selection and characters in general.
- **/CharaSelect/Cards**
   - This is where the character selection art is stored.

### 3. Modding the game
1. Go to https://packager.turbowarp.org/.

2. **Select File** and **load Rabbit Hole.sb3*

3. Scroll down, press **Import Settings** and upload **turbowarp-packager-settings.json**

4. Pick your **environment** and press **package**!

   - The browser version of Rabbit Hole just uses Plain HTML

   - The steam version uses Electron Windows application (64-bit only)

## Author
- All code was written by @ShortCake_Cafe
