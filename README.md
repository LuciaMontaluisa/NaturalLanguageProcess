# Servicio de Traducción con Flask y HuggingFace en Google Colab

Este proyecto implementa un servicio web de traducción que utiliza Flask, HuggingFace Transformers y pyngrok. La aplicación expone una interfaz web que permite ingresar texto en inglés y recibir su traducción al español.

## Requisitos

- **Google Colab:** Se ejecuta en un notebook de Google Colab.
- **Conexión a Internet:** Para instalar dependencias y descargar el modelo de HuggingFace.
- **Cuenta de ngrok :** El plan gratuito suele ser suficiente para pruebas simples.

## Dependencias

El proyecto utiliza los siguientes paquetes:
- **flask:** Microframework para crear la aplicación web y definir rutas.
- **transformers:** Biblioteca para cargar modelos NLP preentrenados (modelo de traducción).
- **torch:** Framework de deep learning, utilizado como backend por transformers.
- **flask-cors:** Extensión que habilita CORS, permitiendo peticiones desde distintos orígenes.
- **pyngrok:** Herramienta para exponer el servidor local a internet mediante túneles públicos.
- **sacremoses:** Tokenizador recomendado para mejorar el procesamiento del texto en modelos NLP.

## Instrucciones de Ejecución

### 1. Abrir Google Colab

Abrir noteboook en google colab y ejecutar todas las celdas hasta
