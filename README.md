# Hand Gesture Recognition with Mediapipe

Este proyecto utiliza OpenCV y Mediapipe para reconocer gestos de mano en tiempo real a través de una cámara. Puede detectar varios gestos y mapearlos a letras del alfabeto.

## Requisitos

- Python 3.x
- OpenCV
- Mediapipe

Puedes instalar los requisitos mediante:

pip install opencv-python mediapipe

## Uso

1. Ejecuta el script `hand_gesture_recognition.py`.
2. Asegúrate de tener una cámara conectada.
3. Coloca tu mano frente a la cámara y haz gestos para ver las letras correspondientes.

## Funcionalidades

- Reconoce letras del alfabeto a partir de gestos de mano.
- Muestra la detección en tiempo real a través de una interfaz de cámara.
- Utiliza Mediapipe para detectar los puntos clave de la mano.

## Detalles del Proyecto

- `hand_gesture_recognition.py`: Contiene el código principal para el reconocimiento de gestos.
- `condicionalesLetras()`: Define las letras del alfabeto y sus respectivos gestos.
- `obtenerAngulos()`: Calcula los ángulos entre los dedos para determinar los gestos.
- Usa OpenCV para capturar y mostrar el video de la cámara.
- Utiliza Mediapipe para detectar los puntos clave de la mano y las conexiones entre ellos.

## Contribuyendo

¡Siéntete libre de contribuir a este proyecto abriendo problemas o enviando solicitudes de extracción!

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE.txt).