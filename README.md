# Godot 4 Color Correction and Screen Effects Visual Shaders

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Godot_4_Color_Correction_and_Screen_Effects_Visual_Shader_Overview.jpg)

## Description

Color correcting shader graph (visual shader) for Godot 4.3 (may work with other versions too), will probably work with Redot Engine as well.

There are two branches: ColorCorrection Mini and Screen Effects Ultimate. Mini only has basic tools, but is very lightweight and can be used without any noticeable performance costs on any platform. Color correction works similar to video editing software and is fully compatible with basic environment and camera features of Godot Engine. All values have sliders (shader parameters) that can be animated and controlled from your code. It allows to use and combine all these features for the whole game and change them in runtime.

## Installation
1. Download the most recent Release folder and place it to your project
2. From source use ColorCorrection_Mini, ScreenEffects_Ultimate + Gradient Texture
4. Make a camera in your 2D or 3D scene
5. Add CanvasLayer node as a child of the camera
6. Add ColorRect node as the child of the CanvasLayer
7. Make ColorRect full-screen in node settings: Layout, Anchors Preset, Full Rect.
8. Add shader (MINI or ULTIMATE) to ColorRect Material slot
9. Change values to setup (only visible in runtime, not within the editor) 

### ColorCorrection Mini
Tune color temperature, brightness, contrast, saturation, and green tint of the whole image. Apply vignette, if needed. With this simple and fast shader you can easily make the game feel colder, warmer, or more dangerous (like on icy mountains, hot volcano, or poisoned swamps respectively).

### Screen Effects Ultimate

![Godot 4 Panini Projection](https://github.com/ArseniyMirniy/Godot-4-Color-Correction-and-Screen-Effects/blob/main/Extras/Panini.gif)

A heavy but reliable shader with tons of effects and features. It should run well on any modern system: effects are optimized, sampling is very limited (usually at 5–8 samples per effect). Blurring passes for bloom and overall blur-sharpening are the same. Pixelation is applied to everything, including the vignette and bloom. The goal of this shader is to be universal and cover the majority of use cases, but even the most aggressive effects, like chromatic aberrations, are safe by default and applied properly.

**Global:**

• Pixelation (scalable)

• Panini Projection

• Blur and Sharpening

• Chromatic Aberrations

• Bloom booster

• Halation

• Vignette 

• Saturation

• Color Filter

• Posterization

• Film Grain

**MAIN + Shadows, Midtones, Highlights:**

• Color Temperature

• Green Tint

• Brightness

• Contrast

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Day_to_Night.jpg)

## License

Unique files (shaders, scenes, and custom textures) are provided under Creative Commons Attribution license. You need to clearly mention Arseniy Mirniy as the author and provide the link to this repository. You are free to use these shaders, scenes, and textures in any projects, including commercial ones.

[![CC BY 4.0][cc-by-shield]][cc-by]

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

⚠️ Godot Icon (used as the project icon originally) and GameUnion.TV logo (part of the current icon) are licensed under other terms and can't be redistributed freely.

## Extra credits

The HDRi is [Klippad Sunrise 1](https://polyhaven.com/a/klippad_sunrise_1) by Greg Zaal from Poly Heaven, the license is CC0 for the image.
You can learn visual shaders (in Unreal and Unity) from [Ben Cloward YouTube channel](https://www.youtube.com/watch?v=ipKQt0BxQSA&list=PL78XDi0TS4lGORvoEKCyw_6dO9tzlu6Ox).
