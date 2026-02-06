# 👁️ Reconocimiento Facial en Tiempo Real con Face-API.js

Este proyecto representa mi **primera interacción con redes neuronales artificiales**, explorando las capacidades de la visión artificial (Computer Vision) directamente en el navegador.


## 📌 Descripción

La aplicación utiliza la cámara web del usuario para detectar rostros en tiempo real, identificando puntos biométricos, estimando la edad, el género y reconociendo expresiones faciales. Todo el procesamiento se realiza en el **lado del cliente**, lo que garantiza privacidad y rapidez.

## 🧠 Modelos de IA Implementados

Para lograr el funcionamiento completo, el sistema carga y ejecuta simultáneamente los siguientes modelos:

* **SSD Mobilenet V1:** Para la detección precisa de rostros.
* **Face Landmark 68:** Para identificar los puntos clave de la estructura facial.
* **Face Expression:** Para detectar emociones (felicidad, tristeza, sorpresa, etc.).
* **Age & Gender:** Para la estimación demográfica de los sujetos.

## 🛠️ Tecnologías

* **Lenguaje:** JavaScript (ES6+)
* **Biblioteca IA:** [Face-api.js](https://github.com/justadudewhohacks/face-api.js) (basada en TensorFlow.js).
* **Renderizado:** HTML5 Canvas para el dibujo de máscaras y etiquetas en vivo.

## 🚀 Instalación y Uso

1. **Clona este repositorio:**
   ```bash
   git clone [https://github.com/Emilianoking/reconocimiento-facial-con-face-api.git](https://github.com/Emilianoking/reconocimiento-facial-con-face-api.git)
