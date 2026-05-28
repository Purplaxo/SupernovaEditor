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
- [x] Dynamic Stages
- [ ] Dynamic Stages (for preview)
- [ ] SV Skip (for preview)
- [ ] Changing Note SFX
- [ ] Custom Hold mids
- [ ] Cycling tool note types.
- [ ] Mobile support
- [ ] Performance improvements
- [ ] Better particles (3D)
- [ ] Better user particle editing
- [ ] More customization
- [ ] Exporting long SV's with easings instead of keyframe spam
- [ ] Support for unchmmws & ccmmws
- [ ] Chart Cyanvas guides (specifically Fade-In/Fade-Out/No Fade)
- [ ] (Possible script macros?)
- [ ] Open source (with an open modding license)


<img width="1280" height="858" alt="Image showcasing the editor and the preview." src="https://github.com/user-attachments/assets/b05e3c98-49c2-4ea6-85e7-1f70219dd7c1" />

### SV Keyframes
These function like timescale markers, although they have a few major differences. You can place multiple keyframes on the span of 6 lanes. Another difference is the fact that you can click and drag upwards to create a "long" keyframe, which will interpolate the sv value (by whatever easing you choose). How it works is whatever value you input into the long keyframe will be the *end* value. The *start* value is the value that was before.

<img width="427" height="304" alt="image" src="https://github.com/user-attachments/assets/0827b1c0-6c4d-4106-8bec-738838388d40" />

The image above has a SV change to 0.5x, which will be instant (exactly like normal timescale marker). Then from the starting point of the long keyframe, it will interpolate from 0.5x to 1.0x. Since no filetypes support long keyframes, the editor automatically can convert keyframes to markers (you can select the division too)

### Compatibility Warning Mode (beta)
Warns the user if there are any objects in the chart that are unsupported by the filetype the user wants to export.

<img width="1278" height="856" alt="image" src="https://github.com/user-attachments/assets/e5e13065-4c92-4445-8b75-1b20e5103551" />

### Keybinds

Full list of keybinds are found in the editor settings. A few actions are keybind-only, such as changing division, song speed or adjusting note size.

# Downloads

⚠️ **Warning**: This tool is in its early stages of development. If you experience any bugs, please report them [here](https://github.com/Purplaxo/SupernovaEditor/issues).
> This tool was __partially__ assisted by AI for very obscure and time consuming tasks. If you don't like it, don't use it. Nobody is forcing you to. (its not like i can even do anything with free tiers lmao)

You can find download files in [Releases](https://github.com/Purplaxo/SupernovaEditor/releases)

### Modding

> I'm not allowing any Lua code in this repository to be copied, modified, distributed, or used to create derivative works by anyone, unless i say otherwise. This will probably change in the future.
> Although i grant permission to modify/replace assets (files ending in: .png .txt .scp .ttf .otf .mp3).

I'm open to adding suggestions. Create them [here](https://github.com/Purplaxo/SupernovaEditor/issues) with the suggestions tag.

### Other

> If i haven't credited someone - sorry, please inform me.

> I have not copied any code from any other tools, only used mmw as reference for a few things (with Crash5b's permission).
