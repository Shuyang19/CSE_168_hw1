# CSE 168 HW additional features
## pixel antialiasing
- For antialiasing, I generate 100 rays per pixel, and then get the average color.
- Below is the comparation of graphs before and after pixel antialiasing:

![Image](scene4-ambient.png)
![Image](scene4-ambient-pixel-antialiasing.png)

- It may not very clear, let's zoom in part of them:

![Image](before_pixel_antialiasing.jpg)
![Image](after_pixel_antialiasing.jpg)


- And we can see the difference of edge pixels for object.
- It is obvious that after pixel antialiasing, the edge is softer.
