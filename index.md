# Visión por Computadora 2025

Este es un curso introductorio a la visión computacional (CV). Haremos un recorrido por las técnicas estándar para el procesamiento de imágenes digitales, el diseño de filtros básicos y aplicaciones de transformaciones, las cuales sirvan como base para el desarrollo de aplicaciones inteligentes asociadas a imágenes.

Aprenderemos y estudiaremos los algoritmos más comunes para la detección, extracción y comparación de características. Abordaremos también el estudio geométrico de imágenes de una vista (*one-point-view*) y de dos vistas (*two-point-view*), y sus transformaciones asociadas. Estos algoritmos se utilizan para alinear y unir imágenes para crear una única imagen de una escena más grande, y para recrear escenas 3D a partir de imágenes planas.

Abordaremos también grandes temas como la clasificación y segmentación de imágenes, y estudiaremos los métodos actuales de aprendizaje automático para este objetivo, principalmente redes neuronales convolucionales. Abordaremos también temas como la detección de objetos en una imagen, así como estimación de movimiento y seguimiento de objetos con aprendizaje automático. Al final del curso y si el tiempo lo permite haremos un breve recorrido por metodologías y herramientas actuales de IA generativa, para producir imágenes a partir de descripciones.

El curso requiere madurez por parte del estudiante, pues se integran contenidos de muchos cursos de computación, matemática y estadística. Entre los prerrequisitos se encuentra tener un buen dominio de las técnicas vistas en los cursos de matemática discreta, grafos, álgebra lineal, programación y algoritmos, cálculo diferencial e integral, y estadística. 


# Programa del curso
<div id='id-programa'/>

(El programa aún está sujeto a modificaciones. Las fechas y algunos temas pueden cambiar).

[Programa del curso](programa/Programa-cv2025.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes, de 18:10 a 19:45 horas. Jueves, de 17:20 a 18:55 horas.

### Office Hours
<div id='id-office'/>

* Por definir. Por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                       | **Recursos**
-------- | ------------ | ----------------------------------------------------------------- |  -------------------------------------
01       | 14.01.2025   | Introducción al curso. Desarrollo de la VC. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | 
02       | 14.01.2025   | Tipos de imágenes: binarias, escala de grises, a color, multiespectro. [Aula 02](aulas/Aula02.pdf){:target="_blank"}  | 
03       | 16.01.2025   | Transformaciones básicas en imágenes. Histogramas. Corrección $\gamma$. | [plane.png](code/plane.png){:target="_blank"} [plane_mask.png](code/plane_mask.png){:target="_blank"} [quetzal.png](code/quetzal.png){:target="_blank"} <br/> [image-types.ipynb](code/image-types.ipynb){:target="_blank"}
04       | 23.01.2025   | Formación de imágenes. Luminancia y crominancia. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Forsyth-Ponce, Cap. 1 
05       | 23.01.2025   | Espacios de color: RGB, HSV y HSL, CIExy, YUV, YCbCr. | [house.jpeg](code/house.jpeg){:target="_blank"} [bananas.jpeg](code/bananas.jpeg){:target="_blank"} [fresas.png](code/fresas.png){:target="_blank"} <br/> [color-spaces.ipynb](code/color-spaces.ipynb){:target="_blank"} [color-perception.ipynb](code/color-perception.ipynb){:target="_blank"} [color-detection.ipynb](code/color-detection.ipynb){:target="_blank"} 
06       | 28.01.2025   | Ecualización de Histogramas. Algoritmos de binarización: Riddler-Calvard, Otsu. | [thresholding2.ipynb](code/thresholding2.ipynb){:target="_blank"} <br/> [tree.jpg](code/tree.jpg){:target="_blank"} [document.png](code/document.png){:target="_blank"}
07       | 30.01.2025   | Algoritmos de binarización II. Cuantización. Segmentación de imágenes. | [quantization.ipynb](code/quantization.ipynb){:target="_blank"} <br/> [horse.jpg](code/horse.jpg){:target="_blank"} [playa.jpeg](code/playa.jpeg){:target="_blank"}
L1       | 30.01.2025   | Lab 1.  [Lab 01](labs/lab01.pdf){:target="_blank"}  <br/> **Fecha de Entrega: 11 de febrero.** | [rice.jpg](labs/rice.jpg){:target="_blank"} [coca-cola.jpeg](labs/coca-cola.jpeg){:target="_blank"} [pepsi.png](labs/pepsi.png){:target="_blank"} 
08       | 04.02.2025   | Morfología matemática: *dilation*, *erosion*, *opening*, *closing*, *Top-Hat*. [Aula 06](aulas/Aula06.pdf){:target="_blank"} | [circles.png](code/circles.png){:target="_blank"} [Cosmos_original.jpeg](code/Cosmos_original.jpeg){:target="_blank"} <br/> [morphology1.ipynb](code/morphology1.ipynb){:target="_blank"}
09       | 06.02.2025   | Esqueletización. Detección de componentes conexas. Operador *Hit-or-Miss*. | [octagons.png](code/octagons.png){:target="_blank"} [text.png](code/text.png){:target="_blank"} [text2.png](code/text2.png){:target="_blank"} <br/> [morphology2.ipynb](code/morphology2.ipynb){:target="_blank"} 
10       | 11.02.2025   | Morfología matemática para imágenes *grayscale*. Algoritmo *Watershed*. | [quetzalgris.png](labs/quetzalgris.png){:target="_blank"} [morphology3.ipynb](code/morphology3.ipynb){:target="_blank"} 
L2       | 13.02.2025   | Lab 2.  [Lab 02](labs/lab02.pdf){:target="_blank"}  <br/> **Fecha de Entrega: 25 de febrero.** | [brain-scan.jpeg](labs/brain-scan.jpeg){:target="_blank"} [rice.jpg](labs/rice.jpg){:target="_blank"} [microscope.png](labs/microscope.png){:target="_blank"} [butterfly.jpeg](labs/butterfly.jpeg){:target="_blank"} [quetzalgris.png](labs/quetzalgris.png){:target="_blank"} [chestxray.jpeg](labs/chestxray.jpeg){:target="_blank"} [wheat.png](labs/wheat.png){:target="_blank"} 
11       | 18.02.2025   | Convolución y correlación. Filtros binarios. | 
12       | 20.02.2025   | Tipos de *padding*. Filtros lineales: Prewitt, Sobel, Laplace. | 
13       | 25.02.2025   | Filtros de orden, filtro de medianas. Eliminación de ruido. | 
14       | 27.02.2025   | Filtros gaussianos. Fitros de Gabor. Bancos de filtros. | 
15       | 04.03.2025   | Transformada rápida de Fourier. <br/> |  
16       | 11.03.2025   | Filtro de Canny. Transformada de Hough. <br/> |  
17       | 11.03.2025   | Filtros de Haar. Imagen integral. Algoritmo de Viola-Jones para detección de caras. | [Paper Viola-Jones (2001)](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf){:target="_blank"} <br/> [facial-expressions.jpeg](code/facial-expressions.jpeg){:target="_blank"} [haar1.ipynb](code/haar1.ipynb){:target="_blank"}
18       | 13.03.2025   | Ejemplos de filtros de Haar. Uso de librerías MediaPipe. | [volei.jpeg](code/volei.jpeg){:target="_blank"} [clocks.jpeg](code/clocks.jpeg){:target="_blank"} [haar2.ipynb](code/haar2.ipynb){:target="_blank"} [haar3.ipynb](code/haar3.ipynb){:target="_blank"}
19       | 20.03.2025   | Histograma de Gradientes Orientados (HoG). | [Paper Dalal-Triggs (2005)](https://lear.inrialpes.fr/people/triggs/pubs/Dalal-cvpr05.pdf){:target="_blank"} <br/> [person.png](code/person.png){:target="_blank"} [hog-on-scratch.ipynb](code/hog-on-scratch.ipynb){:target="_blank"} [hog.ipynb](code/hog.ipynb){:target="_blank"}
L3       | 25.03.2025   | Construcción de un HoG. <br/> [Lab 03](labs/lab03.pdf){:target="_blank"} [person.png](labs/person.png){:target="_blank"} | **Fecha de Entrega: 01 de abril.** 
20       | 27.03.2025   | Puntos característicos. Detector de esquinas de Harris. | [harris-detector.ipynb](labs/harris-detector.ipynb){:target="_blank"}


# Proyectos
<div id='id-proj'/>

En el curso se desarrollarán cuatro proyectos, los cuales se indicarán más adelante.

## Proyecto 1
<div id='id-proj1'/>

**No.**  | **Fecha**    | **Tópicos**                                   | **Recursos**
-------- | ------------ | --------------------------------------------- |  -------------------------------------
 1       | 13.02.2025   | Proyecto 1 - *Angiogramas coronarios*.        | [Proyecto 1](proyectos/pr1/Proyecto1.pdf){:target="_blank"} <br/>  [database.zip](proyectos/pr1/database.zip){:target="_blank"} 
 2       | 13.03.2025   | Entrega del proyecto.                         | 


## Proyecto 2
<div id='id-proj2'/>

**No.**  | **Fecha**    | **Tópicos**                                   | **Recursos**
-------- | ------------ | --------------------------------------------- |  -------------------------------------
 1       | 20.03.2025   | Proyecto 2 - *Detección de objetos*.        | [Proyecto 2](proyectos/pr2/Proyecto2.pdf){:target="_blank"} <br/> 
 2       | 10.04.2025   | Entrega del proyecto.  

 
# Referencias
<div id='id-ref'/>

### Textos:

* [R. Szeliski (2022). *Computer Vision: Algorithms and Applications*.](https://libgen.li/ads5b158374b784fa7fc9d6559b45352ea16FJLGN45){:target="_blank"}

### Otras Referencias:

* [D. Forsyth y J. Ponce (2011). *Computer Vision: A Modern Approach*.](https://libgen.li/ads11030c8ae6b3351ace96677c84ff5440DE9WOXXP){:target="_blank"}

* [R. Hartley y A. Zisserman (2004). *Multiple View Geometry in Computer Vsion*.](https://libgen.li/ads5b9fabf3b531864cd07f3e8ab4d03d87HBTX6J1C){:target="_blank"}

* [R. Gonzalez y R. Woods (2018). *Digital Image Processing*. 4th Edition](https://libgen.li/adsf60088a723f71a363b945da511dcbec1DUEGD40P){:target="_blank"}

---
