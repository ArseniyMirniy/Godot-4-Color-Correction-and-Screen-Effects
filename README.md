# Godot 4 Color Correction and Screen Effects Visual Shaders

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Godot_4_Color_Correction_and_Screen_Effects_Visual_Shader_Overview.jpg)

## Description

Color correcting shader graph (visual shader) for Godot 4.3 (may work with other versions too), will probably work with Redot Engine as well.

There are three branches: ColorCorrection Extra, ColorCorrection Mini, and Screen Effects Ultimate. The main shader for now is Extra. It can tweak saturation and brightness, tune color temperature for the overall image, tune it for bright and dark areas (in smaller scale), etc. It works similar to video editing software and is fully compatible with basic environment and camera features of Godot Engine. 

### ColorCorrection Mini
Tune color temperature, brightness, saturation, and green tint of the whole image. With this simple and fast shader you can easily make the game feel colder, warmer, or more dangerous (like on icy mountains, hot volcano, or poisoned swamps respectively).

### ColorCorrection Extra
Same as Mini, but also able to tweak Bright and Dark areas separately, so the results are almost unlimited: you can turn day into night in a few clicks.

### Screen Effects Ultimate
Same as Extra, but with additional effects, like Sharpening and Blur, Vignette, and Chromatic Aberrations. More features will be included over time. Current tools are fine-tuned to avoid visual glitches (like clipping over bright spots sharpening). Blur is intentionally overscaling to avoid mix with empty space and visual borders on sides, it makes both blur and sharpening to be more significant on the sides of the image.

Please, be very careful with Chromatic Aberrations — it's the easiest way to get motion sickness.

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Day_to_Night.jpg)

## License

Files are provided under Creative Commons Attribution license. You need to clearly mention Arseniy Mirniy as the author and provide the link to this repository.

[![CC BY 4.0][cc-by-shield]][cc-by]

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Extra credits

The HDRi is [Klippad Sunrise 1](https://polyhaven.com/a/klippad_sunrise_1) by Greg Zaal from Poly Heaven, the license is CC0 for the image.
You can learn visual shaders (in Unreal and Unity) from [Ben Cloward YouTube channel](https://www.youtube.com/watch?v=ipKQt0BxQSA&list=PL78XDi0TS4lGORvoEKCyw_6dO9tzlu6Ox).
