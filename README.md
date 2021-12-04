# PROYECTO FINAL DE IA - DETECCIÓN DE ARMAS EN IMAGENES HACIENDO USO DE DEEP LEARNING
Los sistemas actuales implementados para la vigilancia y control de armas todavía requieren supervisión humano (visión e intervención) y pueden llegar a ser costosas o incluso
con porcentajes de error alto. En este trabajo proponemos hacer uso de redes convolucionales con el modelo VGG16 para la resolución de este problema.

## Comenzando ⚙️

El programa cuenta con 3 carpetas principales: En la carpeta "models" se encuentra el modelo ya entrenado, en "test" almacenamos las imagenes que vamos a evaluar para saber a 
qué clase pertenecen y por último, "train" que es una carpeta que contiene las imágenes para entrenar al modelo, esta dividida a su vez en 3 subcarpetas: "Class 1, class 2, class 3"
(clase 1-> armas blancas, clase 2-> armas de fuego, clase 3-> sin armas).
En "cnn.py" tenemos el código para entrenar a nuestra red y en "tester.py" el código para evaluar una conjunto de imágenes.
### Instalación🔧
Para instalar descargue la carpeta la carpeta completa y ejecute el programa tester.py. En caso quiera entrenar la red ejecute cnn.py

### Demo 🔧
El programa toma como entrada las imagenes de la carpeta "tester", en este caso son 3 imágenes
<img src="https://github.com/YahairaGomez/proyecto_final_ia">

Luego, ejecutamos el programa tester.py el cual retorna una matriz, donde el número de filas es la cantidad de imágenes evaluadas y las columnas contienen la probabilidad 
de que cada imagen pertenezca a la clase 1, 2 y 3 respectivamente

<img src="https://github.com/YahairaGomez/IA/blob/main/Images/resultado.jpg">

En este caso la primera imagen que es "gun.jpg" tiene un mayor porcentaje de pertenecer a la clase 2 que es con armas de juego.

## Autor ✒️

* **Yahaira Gomez Sucasaca** - *Documentación* - [YahairaGomez](https://github.com/YahairaGomez)
* **Anel Veliz Choque** - *Documentación* - [alexa1999](https://github.com/alexa1999)
* **Rayza Rodriguez Injante** - *Documentación* - [RayzaRodriguez](https://github.com/RayzaRodriguez)

## Expresiones de Gratitud 🎁

* Agradecimiento especial a YouTube, computación gráfica y a la cafeína ☕
