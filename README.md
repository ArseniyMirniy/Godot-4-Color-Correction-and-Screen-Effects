# Godot 4 Color Correction and Screen Effects Visual Shaders

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Godot_4_Color_Correction_and_Screen_Effects_Visual_Shader_Overview.jpg)

## Description

Color correcting shader graph (visual shader) for Godot 4.3 (may work with other versions too), will probably work with Redot Engine as well.

There are two branches: ColorCorrection Mini and Screen Effects Ultimate. Mini only has basic tools, but is very lightweight and can be used without any noticeable performance costs on any platform. Color correction works similar to video editing software and is fully compatible with basic environment and camera features of Godot Engine. All values have sliders (shader parameters) that can be animated and controlled from your code. It allows to use and combine all these features for the whole game and change them in runtime.

## Installation
1. Download two folders (Materials and Shaders, Textures) from GitHub;
2. Source has never versions, but 1.0 Stable Release is also fine;
3. Drop these folders into your Godot 4.3 project;
4. Then you need a 2D or 3D scene with the Camera;
5. Add CanvasLayer node as a child of the camera and disable mouse events in it;
6. Add ColorRectangle node as the child of the CanvasLayer;
7. Make ColorRect full-screen in its settings: Layout, Anchors Preset, Full Rect;
8. Add shader (MINI or ULTIMATE) to ColorRect Material slot;
9. Now you can tune the values (but it’s only visible in runtime, not within the editor);
10. Add Noise Texture (from Textures folder), if you want Film Grain.
11. Same with Color Gradient Filter (4 examples can be found in Textures folder)
12. Place your UI into another Canvas Layer (or it will be also affected).
13. You can draw different parts into different Viewports (each with its own shader)

To modify values, you can open the Inspector Tab of the Color Rectangle node: click on shader material, open Parameters, and move sliders around. Yet again, changes will be visible in runtime, not in the editor. Keep in mind that these values can be Animated and controlled from the code (or both).

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

![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Bistro.jpg)
![Godot 4 Color Correction and Screen Effects Visual Shaders](https://github.com/ArseniyMirniy/Godot-4-Free-Color-Correction-and-Screen-Effects-Visual-Shader/blob/main/Extras/Bistro2.jpg)

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
