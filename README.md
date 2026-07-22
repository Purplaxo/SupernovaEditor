⚠️ **SEGA has banned the usage of unofficial apps in favor of the in-game Editor. Posting any content on the internet is taken at your own risk.** (I am not affiliated with SEGA, Colorful Palette or Crypton Future Media)

# Supernova Editor
A VSRG chart editor built on the LOVE2D framework.

<img width="800" height="493" alt="Gif showcasing the editor and the preview." src="https://github.com/user-attachments/assets/a59c5b6c-0156-4ec7-a5cd-44c66106291a" />


Supported/Planned features:
- [x] Windows, macOS, Linux support
- [x] Editor Themes
- [x] MMWS, SUS, USC, LevelData supported Importing/Exporting
- [x] Compatibilty Warning mode
- [x] Reimagined SV's (timescale)
- [x] Preview
- [x] Layers
- [x] Combo Text
- [x] Extended features
- [x] Downwards Flicks
- [x] Skill/Fever events
- [x] Chart Cyanvas guides (specifically Fade-In/Fade-Out/No Fade)
- [x] Dynamic Stages
- [x] Dynamic Stages (for preview)
- [x] SV Skip (for preview)
- [x] Layer/Stage Grid/List
- [x] Changing Note SFX
- [x] Mobile support
- [x] Live Co-op charting
- [x] Directly export to UntitledCharts within the editor
- [ ] .pjsk support
- [ ] Custom Slide mids
- [ ] Cycling tool note types.
- [ ] Better particles (3D)
- [ ] Better user particle editing
- [ ] More customization
- [ ] Support for unchmmws & ccmmws
- [ ] (Possible script macros?)


<img width="1258" height="841" alt="image" src="https://github.com/user-attachments/assets/7b95b3ae-cf17-421e-b9da-d9bbc5cbde79" />



### SV Keyframes
These function like timescale markers, although they have a few major differences. You can place multiple keyframes on the span of 6 lanes. Another difference is the fact that you can click and drag upwards to create a "long" keyframe, which will interpolate\* the sv value (by whatever easing you choose). How it works is whatever value you input into the long keyframe will be the *end* value. The *start* value is the value that was before, or the value that was set as the "Start Value". This SV system might change in the future so beware of that.

<img width="322" height="297" alt="image" src="https://github.com/user-attachments/assets/846f6986-d7a8-4da9-95f8-1bf546ff74da" />

The image above has a SV change to 0.5x, which will be instant (exactly like a normal timescale marker). Then from the starting point of the long keyframe, it will interpolate from 0.5x to 1.0x. Since no filetypes support long keyframes, the editor automatically can convert keyframes to markers (you can select the division too)

<img width="325" height="230" alt="image" src="https://github.com/user-attachments/assets/d3b0cf62-db4b-43ce-8014-7f49236ebb51" />

The image above does the same thing as before. It interpolates from the start value (0.5x) to the end value (1x).

\***Interpolation** - inserting values between one value and the other, creating a smooth transition.

### Compatibility Warning Mode (beta)
~~Warns the user if there are any objects in the chart that are unsupported by the filetype the user wants to export.~~
This feature is currently disabled, mainly because you can't export and save as .USC, .SUS, .MMWS in the most recent version

<img width="1278" height="856" alt="image" src="https://github.com/user-attachments/assets/e5e13065-4c92-4445-8b75-1b20e5103551" />

### Keybinds

Full list of keybinds are found in the editor settings. A few actions are keybind-only, such as changing division, song speed or adjusting note size.

You can hold shift while scrolling to scroll in a fancier way, and press alt to zoom in 1920div.

# Mobile

The mobile version of the chart editor is available in [Releases](https://github.com/Purplaxo/SupernovaEditor/releases). It features almost every feature from the PC version. 
<img width="292" height="633" alt="IMG_9211" src="https://github.com/user-attachments/assets/7682fcbb-3da4-4f03-a01d-5f4d820eea13" />
<img width="633" height="292" alt="IMG_9212" src="https://github.com/user-attachments/assets/aeb0f137-629f-4b4a-bc69-f4e5f2507e91" />

If you see an issue with the lower toolbar being too low, you can configure it in the editor settings.


### Gestures

- Scrolling: Two finger up/down
- Zooming: Two finger pinch (might not work 100% of the time)
- Undo: Two finger tap
- Redo: Three finger tap
- Note properties: Double tap on the note
- Preview: Rotate your device to landscape


# Downloads

⚠️ **Warning**: This tool is in its early stages of development. If you experience any bugs, please report them [here](https://github.com/Purplaxo/SupernovaEditor/issues).
> This tool was partially assisted by AI for very obscure and time consuming tasks. If you don't like it, don't use it. Nobody is forcing you to.

You can find download files in [Releases](https://github.com/Purplaxo/SupernovaEditor/releases)

Linux needs to do some terminal shenanigans:
- `chmod +x /path/to/appimage`
- if opening the file doesnt work, run the appimage through the terminal
- if THAT doesn't work, install love2d systemwide and run `love /path/to/appimage` (Love is bundled in the appimage though)
I'm not sure about these steps since i haven't tested this on my own (i don't have linux). If you find an easier way of opening this editor, let me know.

### iOS

You need to sideload the `.ipa` file. Find out how to sideload apps with tools like AltStore [here](https://www.reddit.com/r/sideloaded/comments/1ak3x9t/how_to_sideload_application_on_ios_ipados/). (Use these sideloading services at your own risk, I'm not affiliated with them.)

Once you wanna use the editor filesystem, open up the app "Files" on your iPhone, and go to "On My iPhone" > "Supernova". You can find Autosaves, Exports, Audio and Charts there.

### Android

Open the `.apk` file found in releases. 

Once you wanna use the editor filesystem, open up your file explorer, and go to "Internal storage" > "Android" > "media" > "com.nova". You can find Autosaves, Exports, Audio and Charts there.

### Modding

> I'm not allowing any Lua code in this repository to be copied, modified, distributed, datamined, or used to create derivative works by anyone, unless i say otherwise. This will probably change in the future.
> Although i grant permission to modify/replace assets (only files ending in: .png .txt .scp .ttf .otf .mp3).

I'm open to adding suggestions. Create them [here](https://github.com/Purplaxo/SupernovaEditor/issues) with the suggestions tag.

### Other

Join the discord server: https://discord.gg/P6RHTAQvAw

> If i haven't credited someone - sorry, please inform me.

> I have not copied any code from any other tools, only used tools as reference for a few things.
