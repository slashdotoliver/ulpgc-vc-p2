# Visión por Computador | Práctica 2

<p align="center">  
  <img src="./mandril.jpg">  
</p>  

Esta práctica ha permitido trabajar con diferentes técnicas de procesamiento digital de imágenes utilizando **OpenCV, Numpy, Matplotlib y Pillow**. Se han implementado operaciones básicas de lectura, conversión y visualización, así como el cálculo de histogramas y la detección de líneas predominantes en una imagen. Además, se han comparado los detectores de bordes **Sobel y Canny**, analizando visualmente sus diferencias.

También se desarrolló un demostrador interactivo con la webcam, que incorpora distintos modos de funcionamiento: sin filtro, inversión de canales y detección de bordes con Canny. Por último, se implementó un modo que permite “dibujar” en la imagen mediante el seguimiento de un objeto azul.

En el demostrador, para mostrar el modo activo se utiliza la fuente [**JetBrains Mono**](https://github.com/JetBrains/JetBrainsMono). Su licencia es **OPEN FONT LICENSE Version 1.1** y se encuentra en el archivo [OFL.txt](./font/OFL.txt).

## Fuentes

Las siguientes fuentes han sido utilizadas durante el desarrollo de la práctica para consultar el funcionamiento de funciones y técnicas de procesamiento de imágenes:

* **Documentación de OpenCV 2.4.13.7**: [https://docs.opencv.org/2.4.13.7/genindex.html](https://docs.opencv.org/2.4.13.7/genindex.html)
* `cv2.reduce`: [https://docs.opencv.org/2.4.13.7/modules/core/doc/operations_on_arrays.html#cv2.reduce](https://docs.opencv.org/2.4.13.7/modules/core/doc/operations_on_arrays.html#cv2.reduce)
* `cv2.line`: [https://docs.opencv.org/2.4.13.7/modules/core/doc/drawing_functions.html#cv2.line](https://docs.opencv.org/2.4.13.7/modules/core/doc/drawing_functions.html#cv2.line)
* `cv2.Sobel`: [https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/filtering.html#cv2.Sobel](https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/filtering.html#cv2.Sobel)
* `cv2.Canny`: [https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/feature_detection.html#cv.Canny](https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/feature_detection.html#cv.Canny)
* `cv2.cvtColor`: [https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/miscellaneous_transformations.html#cv2.cvtColor](https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/miscellaneous_transformations.html#cv2.cvtColor)
* `cv2.GaussianBlur`: [https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/filtering.html#cv2.GaussianBlur](https://docs.opencv.org/2.4.13.7/modules/imgproc/doc/filtering.html#cv2.GaussianBlur)
* `cv2.imshow`: [https://docs.opencv.org/2.4.13.7/modules/highgui/doc/user_interface.html#cv2.imshow](https://docs.opencv.org/2.4.13.7/modules/highgui/doc/user_interface.html#cv2.imshow)
* `cv2.VideoCapture`: [https://docs.opencv.org/2.4.13.7/modules/highgui/doc/reading_and_writing_images_and_video.html#cv2.VideoCapture](https://docs.opencv.org/2.4.13.7/modules/highgui/doc/reading_and_writing_images_and_video.html#cv2.VideoCapture)

---

Autor: Oliver Cabrera Volo