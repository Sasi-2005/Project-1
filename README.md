# Project-1
Image to Pencil Sketch Converter

Welcome to the "Image to Pencil Sketch Converter" GitHub repository! This repository houses a Python tool that transforms ordinary images into captivating pencil sketches. Whether you're an aspiring artist, a photography enthusiast, or a developer exploring image processing, our simple yet powerful script allows you to unleash your creativity and turn photos into stunning monochrome sketches.

Key Features:
1. Image Conversion to Grayscale:
Our script begins by reading input images in the RGB format, and it promptly converts them into timeless grayscale renditions. This fundamental step lays the foundation for creating classic black and white visuals reminiscent of vintage photographs.

2. Grayscale Image Inversion (Negative Image):
Inverting the grayscale image is the next step. By doing this, we create a negative image that enhances image details, bringing out subtleties and textures that might be otherwise hidden. This inversion process adds an artistic touch to your sketches.

3. Gaussian Blur for Artistic Effect:
To achieve a smoother and more artistic appearance, our script optionally applies Gaussian blur to the inverted image. This step allows you to control the level of detail in your pencil sketches, making your artwork unique and visually appealing.

4. Pencil Sketch Generation:
The final and most exciting phase of the process involves blending the grayscale image with the optionally blurred, inverted image. The magic happens through simple yet effective pixel-wise division, thanks to the cv2 library in Python. The result is a stunning pencil sketch that preserves the essence of the original image while infusing it with an artistic flair.
