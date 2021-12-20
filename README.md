# 4.2_Feature_matching
Es la segunda tarea del cuarto parcial de mi materia de Análisis y Procesamiento de Imágenes

## **INSTRUCCIONES**

Esta tarea encontrará los matches entre dos imágenes. La primera será la foto de una carta de cartón ( lotería,uno, baraja, etc.). La segunda será una foto de 4 cartas de ese mismo mazo y, entre ellas, la primer carta. Posteriormente se utilizará un código de feature matching como ORB o SIFT (recomiendo el código a continuación) para graficar los matches en forma cruzada (una rayita que une cada par igual).  
- [Enlace 1](https://blog.francium.tech/feature-detection-and-matching-with-opencv-5fd2394a590)

Entregables:
- Código utilizado con formato PY
- Imagen original de carta sola JPG
- Imagen original de las 4 cartas JPG
- Imagen con el matching cruzado JPG


Funciones nuevas dentro de este código:


- [orb_create (orientado rápido o oriented brief 2011) - nfeatures](https://docs.opencv.org/3.4/db/d95/classcv_1_1ORB.html)


- [detectandcompute - keypoints, descriptors](https://docs.opencv.org/3.4/d0/d13/classcv_1_1Feature2D.html)


- [bfmatcher - (normhamming se usa con orb, l1 l2 con sift) crosscheck cruza por parejas para encontrar matches](https://docs.opencv.org/3.4/d3/da1/classcv_1_1BFMatcher.html)


- [knnMatch - lambda se utiliza para definir parametros en un arreglo](https://docs.opencv.org/3.4/db/d39/classcv_1_1DescriptorMatcher.html)


- [drawmatches - none es una bandera que no se necesita](https://docs.opencv.org/3.4/d4/d5d/group__features2d__draw.html)
