# Visual artifacts of realtime rendering systems

This is a collection of effects resulting by the design of realtime rendering systems and appropriate solutions to these issues. 

## Aliasing - Antialiasing

*Problem:* Aliasing of polygonal edges

*Solution:* Subpixel Morphologic Anti-Aliasing

![Aliasing](aliasing.png)

## Minification/Moire and much more - Mipmaps

*Problem:* Variing texture sharpness with magnification/minification as well as moire effects

*Solution:* Mipmaps. Generate multiple versions with different resolution of one texture

![Mipmaps](mipmaps.png)  

## Pixelation of Textures - Texture filtering

*Problem:* Magnified Textures will generate a pixellated look. 

*Solution:* Filtering textures will smooth out pixelation. 

![Texture Filtering](texturefiltering.png)