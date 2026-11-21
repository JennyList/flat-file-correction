# Flat field correction workflows
Cameras will often apply a colour map to the images they take, to correct for lens imperfections. Thus when you modify the camera, the resulting images and videos have a colour cast to them. These files contain the shell commands for Image Magick and ffmpeg to correct the colours in still images and videos.

Both workflows have essentially the same process. Take an unfocused image or video of a evenly lit white surface. Process it into an image normalised to 50% grey. Use the resulting image map in a divide process to remove the colour cast.

One thing to note, the image map must be the same pixel width and height as your images or videos.
