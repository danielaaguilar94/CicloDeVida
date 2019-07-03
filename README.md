# CicloDeVida
Ciclo de vida de un Activity
En esta aplicación hice uso de las diferentes fases o etapas que tiene el ciclo de vida de una actividad
empezando a crearse en el método onCreate(), iniciar la activity con el método onStart() y estar interactuando 
dentro de la actividad en el onResume(), al minimizar dicha actividad de tal forma que queda en segundo plano, 
pasa por las etapas/métodos onPause() y onStop(), al volver a dicha actividad (sin cerrarla) se inician los 
métodos onRestart(), onStart() y vuelve a onResume(). Al rotar la pantalla cambiando de orientación, la actividad 
pasa por los métodos onPause(), onStop(), onDestroy() y se vuelve a crear con onCreate(), vuelve a iniciar onStart() 
y on Resume(). Al cerrar la actividad se ejecuta el método onDestroy(). 
Por medio de un Log se pueden ver depende las acciones realizadas la información referida a cada método.
