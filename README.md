# Detección deimagenes enfocado a basquetbol
## Objetivo:
Este trabajo busca sentar los cimientos para una incorporación de la inteligencia artificial en el ámbito deportivo al crear un modelo capaz de analizar imágenes de partidos a cualquier nivel ya sea profesional, semi-profesional o amateur, siendo capaz de detectar a los jugadores dentro de la cancha, al balón, los aros, los ´arbitros y en caso de que la imagen incluya marcador, también poder detectar los nombres de los equipos y sus puntos, así como el tiempo restante.

## Sobre el Repositorio:
Se trabajó de dos maneras distintas. Una a través de una laptop con procesador Ryzen 5 3600U con 8 GB de memoria RAM y SO Ubunutu 24.4, donde los entrenamientos se vieron interrumpidos por el bajo poder computacional del hardware. Por otro lado, se utilizó una computadora de escritorio con un procesador Ryzen 5 5500 y 16 GB de RAM, así como GPU Radeon RX 6600 utilizando WSL con Ubunutu 24.4 instalado en la cual los entrenamientos se llevaron de manera exitosa. Los ambientes virtuales utilizados intentaron basarse en DirectML para poder usar la GPU, sin embargo YOLO no está optimizado para GPUs AMD.
