# webcam_circleis
Circle detection from online webcam images


La transformada de Hough es una función utilizada en visión para reconocer rectas, circunferencias o elipses. Se tranforma la imagen a escala de grises para poder aplicar la ecuación.

https://es.wikipedia.org/wiki/Transformada_de_Hough

 

GAUSSIAN_BLUR_SIZE = dimensión de la matriz de ruido.
GAUSSIAN_BLUR_SIGMA = desviación estándar del desenfoque gaussiano.
CANNY_EDGE_TH = Umbral del detector de bordes. con vlores bajos la detección de los bordes es menor.
HOUGH_ACCUM_RESOLUTION = Resolución del acumulador de Hough, en términos de relación inversa de resolución de imagen
MIN_CIRCLE_DIST = minima distancia entre centro de los circulos
HOUGH_ACCUM_TH = es el umbral del acumulador para decidir la detección del centro
MIN_RADIUS = radio mínimo
MAX_RADIUS = radio máximo

