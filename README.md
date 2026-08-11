# MoonReplacer
## Dependencies
This mod will not work without MelonLoader.

## Installation steps:
1. Place MoonReplacer.dll inside your Steam/steamapps/common/Flyout/Mods folder.
2. In Steam/steamapps/common/Flyout/Flyout_Data/StreamingAssets/Mods, create a folder titled MoonReplacer. If you do not do this, the mod will not work.
## How to use:
1. In the MoonReplacer folder, place the six texture files you will use to replace the moon textures.
2. Each file name must take the following format: "moon_" followed by "neg_" or "pos_", followed by "x","y", or "z", and ending with the file extension. You should not need to manually add the file extension to the name. Example: moon_pos_x.png
3. If you want to replace the skybox, create a folder inside the MoonReplacer folder titled "Skybox". Place in this folder the six texture files you will use to replace the skybox.
4. Each skybox texture name should take the same format as those used by the moon, but with "sky_" instead of "moon_".
5. Open the config and make sure the image width of the skybox and moon textures matches the "moon image width" and "sky image width" fields. TEXTURES MUST BE SQUARE TO WORK CORRECTLY. IF DIMENSIONS DO NOT MATCH THOSE SET IN THE CONFIG, TEXTURES WILL APPEAR INCORRECTLY.
6. You may need to lower the brightness of the textures you use, as even moderately bright textures can have noticeable visual artifacts.
## Accepted texture formats:
This mod currently only supports .png, .jpg, and .exr file formats. TEXTURES MUST HAVE SQUARE DIMENSIONS.
## Additional notes:
- You can change the scale of the moon in the sky with the "scale" field in the config file. Exceeding a value of 2.0 will make plants become insanely reflective, so if you want a huge moon you will probably want to disable trees in your game settings.
- You can also change the color of the light emitted by the moon in the "lightcolor" arguments. The color format is RGBA with acceptable values ranging from 0.0 to 1.0 for each argument. You should only need to adjust the first three values, and the fourth can be left at 1.0.
