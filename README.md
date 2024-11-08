# Godot 4 Color Correction and Screen Effects Visual Shaders

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Godot_4_Color_Correction_and_Screen_Effects_Visual_Shader_Overview.jpg)

## Description

Color correcting shader graph (visual shader) for Godot 4.3 (may work with other versions too), will probably work with Redot Engine as well.

There are two branches: ColorCorrection Mini and Screen Effects Ultimate. Mini only has basic tools, but is very lightweight and can be used without any noticeable performance costs on any platform. Color correction works similar to video editing software and is fully compatible with basic environment and camera features of Godot Engine.

## Installation
1. Download Relese or use ColorCorrection_Mini and ScreenEffects_Ultimate files from source
2. Download Textures folder as well
3. Place them in your project
4. Make a camera in your 2D or 3D scene
5. Add CanvasLayer node as a child of the camera
6. Add ColorRect node as the child of the CanvasLayer
7. Make ColorRect full-screen in node settings: Layout, Anchors Preset, Full Rect.
8. Add shader (MINI or ULTIMATE) to ColorRect Material slot
9. Change values to setup (only visible in runtime, not within the editor) 

### ColorCorrection Mini
Tune color temperature, brightness, saturation, and green tint of the whole image. With this simple and fast shader you can easily make the game feel colder, warmer, or more dangerous (like on icy mountains, hot volcano, or poisoned swamps respectively).

### Screen Effects Ultimate
A heavy but reliable shader with tons of effects and features. It should run well on any modern system: effects are optimized, sampling is very limited, and all heavy features have on/off toggles.

**Global:**

• Blur and Sharpening

• Pixelation (scalable)

• Chromatic Aberrations

• Bloom booster

• Halation

• Vignette 

• Saturation

• Color Filter


**MAIN + Shadows, Midtones, Highlights:**

• Color Temperature

• Green Tint

• Brightness

• Contrast

**WIP:**

• Lense Flares (Anamorphic)

• Film Grain (Physically Correct)

• Screen Warp Effects

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Day_to_Night.jpg)

## License

Unique files are provided under Creative Commons Attribution license. You need to clearly mention Arseniy Mirniy as the author and provide the link to this repository.

[![CC BY 4.0][cc-by-shield]][cc-by]

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Extra credits

The HDRi is [Klippad Sunrise 1](https://polyhaven.com/a/klippad_sunrise_1) by Greg Zaal from Poly Heaven, the license is CC0 for the image.
You can learn visual shaders (in Unreal and Unity) from [Ben Cloward YouTube channel](https://www.youtube.com/watch?v=ipKQt0BxQSA&list=PL78XDi0TS4lGORvoEKCyw_6dO9tzlu6Ox).
