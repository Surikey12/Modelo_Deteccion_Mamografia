# Modelo_Deteccion_Mamografia
Este proyecto contiene el entrenamiento de un modelo de deteccion de anomalias en mamografias usando Keras/TensorFlow.

## Contenido
- Notebook de entrenamiento (.ipynb)
- Modelo entrenado (.h5)
El modelo en formato .h5 se encuentra en: https://drive.google.com/file/d/1QP46nnfKvWqNhIz3c1iecefX4p_kpmiD/view?usp=drive_link

## Cómo cargar el modelo
from tensorflow.keras.models import load_model
model = load_model("modelo.h5")

## Requisitos para ejecutar el proyecto
Este proyecto utiliza un dataset descargado desde Kaggle, por lo que es necesario contar con el archivo kaggle.json para la autenticación
Pasos: 
- Crear cuenta en Kaggle
- Ir a Setting -> API -> Crear New Token
- Se descarga el archivo kaggle.json.
## 
El archivo es personal y no se incluye en este repositorio por motivos de seguridad.
