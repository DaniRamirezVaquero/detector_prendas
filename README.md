# Clasificador de prendas 👕👟🧥

## Descripción
Aplicación web realizada con Streamlit que permite clasificar imágenes de prendas de ropa en 10 categorías diferentes. 

El modelo de clasificación utilizado es una red neuronal convolucional (CNN) entrenada con el dataset [Fashion MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist).

## Instrucciones de uso
1. Subir una imagen de una prenda de ropa.
2. Hacer click en el botón "Clasificar".
3. Esperar a que el modelo realice la predicción.
4. Ver la predicción realizada por el modelo.

## Apliación web
![App 🌐](https://detectorprendas.streamlit.app/)

## Instalación
1. Clonar el repositorio.
2. Levantar el entorno dockerizado con el comando `docker-compose up`.
3. Acceder a la aplicación web en `http://localhost:8501`.