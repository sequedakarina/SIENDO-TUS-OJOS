# SIENDO-TUS-OJOS

<b>INTEGRANTES:</b><br>     VERÓNICA LUCENA (2152903)  
                            KARINA SEQUEDA (2152476)  
                            
<b>DESCRIPCIÓN GENERAL:</b> El proyecto busca implementar los conocimientos adquiridos en la asignatura respecto a
Deep-Learning. Se incorporan también transformaciones morfológicas tales como cierre, apertura, dilitación y erosión, que permiten localizar los objetos de interés en una imagen para luego proceder a segmentarlos, logrando así un buen reconocimiento de caracteres, a partir del ingreso de una imagen(Fotografía) con texto, haciendo lectura de este a través de un reproductor de voz.

<b>DIRECCIÓN DEL DATASET:</b> https://www.westernsydney.edu.au/bens/home/reproducible_research/emnist

 <b>METODOLOGÍA Y DESCRIPCIÓN DE DATOS CAPTURADOS:</b> En el proyecto se empleará una base de datos propia, creada con la colaboración de un grupo de estudiantes de ingeniería de Sistemas, a quienes se les pidió escribir el alfabeto (excluyendo la ñ) en mayúscula y minúscula. El dataset cuenta con 832 imágenes etiquetadas, de las cuales se emplea el 80% para entrenamiento y el 20% para test.
 
El proyecto se desarrolla en cinco fases. En la primera fase se emplearán las imágenes del dataset para entrenar y evaluar el modelo con tres redes CNN, la primera red continene dos capas convolucionales, una con 30 y otra con 15 filtros, dos MaxPooling un Dropout para evitar overfitting y dos full connected, una con 128 y otra con 50 neuronas, la segunda red contiene dos capas convolucionales, una con 32 y otra con 64 filtros, dos MaxPooling, dos Dropout y una full connected con 128 neuronas y la tercera red continene dos capas convolucionales, una con 6 y otra con 16 filtros, dos MaxPooling un Dropout y dos full connected, una con 120 y otra con 84 neuronas.En la segunda fase se empleará EMNIST para entrenamiento y la base de datos propia para test. En la tercera fase se combinarán las dos bases de datos tanto para entrenamiento como para test. En la cuarta fase se empleará la base de datos propia para entrenar y evaluar el modelo. 

