# Algoritmo `ExpertFiesta`

ExpertFiesta es un algoritmo que permite esconder tus mensajes en imágenes de forma segura y confiable. El algoritmo se hizo en base a [este paper](https://www.hindawi.com/journals/jcnc/2018/9475142/), se implementaron dos mejoras (una inicial y otra final, detalladas [aquí](docs/report.pdf)) cuyo producto es **ExpertFiesta**.

En la rama `mejoraInicial` se encuentra el código de la mejora inicial, mientras que en `main` se encuentra la mejora final.

## Autores

- Rodrigo Céspedes
- Gabriel Spranger
- Benjamín Díaz

## Requerimientos

- Python 3.9

## Notas

- Si al ver `main.ipynb` sale un mensaje diciendo que el notebook se demoró mucho en renderizar, recargar la página
- Al correr la última celda, se generará un archivo `results.txt` donde se muestra para cada imagen en el _dataset_ el MSE y PSNR entre la imagen original y la imagen con un mensaje oculto de distintos tamaños usando nuestro algoritmo
