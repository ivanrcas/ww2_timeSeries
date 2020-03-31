# VIDEOJUEGO DE LA SEGUNDA GUERRA MUNDIAL
<img src="https://image.slidesharecdn.com/historiadelosvideojuegossobrelaguerramundial-2-171124094019/95/la-segunda-guerra-mundial-en-los-videojuegos-1-638.jpg" alt="Proyecto Simulación Digital" border="4px">
Predicciones de características a través de Series de tiempo para inmersión realista en un juego de guerra.

## Estructura del proyecto
* [Presentación](https://docs.google.com/presentation/d/1Jek3ZC5iuSYVQHXnlP4yfbvKM9JjYZ4A2Df90MdzWFo/view#slide=id.p)
* [Vídeo](https://)
* [Notebook en Colab (preferible para mejor visualización de gráficas)](https://colab.research.google.com/drive/10rGTw8C8FvheUwVxND1Vo5mkhQwfSanG)
* [Notebook en Github](https://github.com/ivanrcas/ww2_timeSeries/blob/master/notebook_proyectoVideojuego.ipynb)
* [Datasets](https://drive.google.com/drive/folders/1csFPpRdUN41foRGsrURePwd1oYAy-6Vq?usp=sharing)

## Descripción del Problema
Una empresa quiere crear un videojuego sobre la segunda guerra mundial. Desea que sus jugadores tengan experiencias únicas de juego y que al mismo tiempo sean lo más semejantes a la realidad. Se desea mostrar la historia de un ciudadano entre las fechas de enero de 1945 y Julio del mismo año dentro de una de las ciudades partícipes de la segunda guerra mundial (el jugador escoge dónde comenzar su historia). Una de las características principales que hace que el jugador se sumerja en la historia son; la cantidad de bombas que la ciudad seleccionada por el jugador recibe y la atmósfera o clima que este debe percibir al estar inmerso en la historia. Para esto se necesita predecir las bombas que caeran y el clima que prevalecera en el desarrollo del juego.

## Solución
Se cuenta con un par de Datasets con datos del clima y los bombardeos entre septiembre de 1944 y enero de 1945 pero no se cuenta con los datos de bombardeo en las fechas que se quiere recrear la historia del juego. Aplicando series de tiempo se hará uso de esta información para predecir el clima y la cantidad de bombardeos que debe experimentar un jugador dependiendo de la ciudad en la que esté jugando. Garantizando así una inmersión única dentro de la historia de la segunda guerra mundial.

## Dependencias- Librerías
* python - jupyter notebook
* pandas
* stats models
* pyramid-arima

## Créditos
Ivan Rodrigo Castillo Cañas - 2130501 <br>
Damar Nicolás Rojas Chacón - 2122079 <br>
Juan Sebastian Rondon Arango - 2130501 <br>
Javier Camilo Rueda Serrano - 2141380 <br>
Grupo D1 - Simulación Digital - UIS
