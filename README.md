# Unity Camera Cutout
A simple Image Effect to only render certain parts of the screen by comparing the original image to a cutout texture.

# Examples

Source
 ![Alt text](https://i.imgur.com/eH52PdP.png "Source")
 
 Cutout Texture
 ![Alt text](https://i.imgur.com/ajKUSrr.png "Cutout Texture")
 
 Fade Shader:
 ![Alt text](https://i.imgur.com/ZGHVHlM.png "Fade")
 
 Solid Shader:
 ![Alt text](https://i.imgur.com/hSNwm0P.png "Solid")


# Usage

Drag the CameraCutout.cs component to your Camera.
Create a new Material and add either the CutoutSolid or the CutoutFade shader.
Create a Cutout Texture the same resolution as your game's and add it to your material under "Cutout".
Set a color.


Make sure your texture settings look like this: 

![Alt text](https://image.prntscr.com/image/e3GzJyqvTyO_u5pLXGUF7A.png "Settings")
