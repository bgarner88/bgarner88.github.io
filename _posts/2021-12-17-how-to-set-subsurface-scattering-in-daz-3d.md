---
layout: post
title: "How to Set Subsurface Scattering in Daz3d"
categories: daz3d
---

## Introduction

Setting the proper subsurface scattering values in Daz3d will allow for more natural looking skin textures in your renders. This guide will walk you through changing the following settings:

- Base color
- Base color effect
- Translucency color
- Translucency weight
- SSS reflectance tint
- SSS mode
- Transmitted measurement distance
- Scattering measurement distance
- SSS color
- SSS direction

The following example images were taken using the Flower Road HDRI from hdrihaven.com. The link to dowload that can be found [here](https://hdrihaven.com/hdri/?h=flower_road). This map has a strong, bright sun which will let you seen the subsurface scattering effects more clearly. You can use any HDRI you like, but this one is good to use while getting everything set up. 

Before you begin, load the Flower Road HDRI in your environment settings. Next, enable **spectral rendering** in the render settings. Set the **spectral conversion intent** to natural, and the **spectral observer** to cie1964. This will render colors more natural and realistic. 

| Spectral rendering settings |
| :----: |
| ![Spectral rendering settings](\assets\img\daz3d\spectral-rendering-settings.PNG) |
| :----: |

## Base Color Settings

Set **base color** and **translucency color** to white (1.0, 1.0, 1.0) and use the diffuse texture map for both. Some characters use a different map for translucency color. If yours does, change it to the diffuse map. 

The **translucency weight** determines the fleshiness of the skin and should be a value between .85 and .95. There is no need for a texture map here. 

If the skin looks too dark, there are two ways to adjust it. First, you can increase the gamma or brighten the texture in your photo editing software of choice. Second, you can go to the parameter settings for translucency color and turn off limits, which will allow you to set the translucency color values to a number higher than 1. The first option generally gives better results.

Set the **base color effect** to scatter & transmit or scatter & transmit intensity. This allows for more control of the SSS settings.

| Base color settings |
| :----: |
| ![Base color settings](\assets\img\daz3d\diffuse-settings.PNG) |
| :----: |

## SSS Settings

First, set the **SSS mode** to chromatic. This will enable the option to change SSS color.

Set **Transmitted color** to (0.99, 0.99, 0.99). If this is set to full white, you'll get a lot of glowing on the the skin.

Set the **SSS color** to (0.99, 0.84, 0.35).

| SSS settings |
| :----: |
| ![SSS settings](\assets\img\daz3d\sss-settings.PNG) |
| :----: |

See below for the RGB values of **transmitted color** and **SSS color**. 

| SSS RGB values |
| :----: |
| ![SSS color RGB values](\assets\img\daz3d\sss-color.PNG) |
| :----: |

| Transmitted color RGB values |
| :----: |
| ![Transmitted color RGB values](\assets\img\daz3d\transmitted-color.PNG) |
| :----: |

The SSS hue can be changed to affect the skin tone. If your character's skin is too yellow, change the hue to 30. If it's too pink, change it to 338. You can expirement with those numbers to see what works best for your character, but those are good starting points for a human figure. 

The **transmitted measurement** distance and **scattering measurement distance** are based on the height of the character in centimeters. For a character that is 180cm, the **transmitted measurement distance** will be 0.018 and the **scattering measurement distance** will be 0.013. If you know the specific height of your figure, use that value for the transmitted measurement distance and subtract 5 for the scattering measurement distance. The average Genesis figure is about 180cm, so these values will be fine for most human characters. 

And that's it. After changing the above settings, your character should now have a much more natural looking skin tone. See below for a before/after comparison.

| Final look |
| :----: |
| ![Comparison](\assets\img\daz3d\sss-before-after.png) |
| :----: |
