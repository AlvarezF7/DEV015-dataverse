# House of Rock

## Indice

* [1. Descripción ](#1-descripción)
* [2. Objetivo ](#4-Objetivo)
* [3. Historias de Usuario](#2-Historias-de-Usuario)
* [4. Prototipos de baja fidelidad ](#4-prototipos-de-baja-fidelidad)
* [5. Prototipos de alta fidelidad ](#5-prototipos-de-baja-fidelidad)
* [6. Aspectos Técnicos ](#5-aspectos-técnicos)
* [5. Vista del proyecto ](#4-vista-del-proyect)


  ***
  ## 1. Descripción
  
  La pagina House of Rock fue creada con la finalidad de entregar a los usuarios información
  detallada sobre las bandas de rock y metal más famosas de las ultimas decadas, lo cual puede
  ser beneficioso tanto para los fanaticos consolidades del genero como para aquellos curiosos
  que siempre andan en busca de escuchar algo nuevo; ademas muestra datos curiosos atravez de
  sus estadisticas.

  ## 2. Objetivo
  
  El objetivo del proyecto es crear una pagina  de bandas de música rock que sea dinamica e intuitiva
  para el usuario, la cual proporcione información especifica y relevante sobre las divesas bandas de
  este genero musical. ademas se incorpora el uso de diferentes inteligencias artificiales, tanto para
  la creacion del set de datos utilizando prompts y la creacion de la imagen del banner atravez del
  gestor de imagenes de bing.

  ## 3. Historias de Ususario
  
  Pensando en las necesidades de nuestros usuarios se decidio entregar la siguientes funcionalidades:
  
  ![](https://github.com/AlvarezF7/DEV015-dataverse/blob/main/historia%20de%20usuario.jpg)
  
  

   
  ## 4. Prototipo de baja fidelidad
  
  ![](https://github.com/AlvarezF7/DEV015-dataverse/blob/develop/prototipo%20baja%20fidelidad.jpg)
  
  ## 5. Prototipo de alta fidelidad
  
  ![](https://github.com/AlvarezF7/DEV015-dataverse/blob/develop/alta%20fidelidad.jpg)
  
  ## 6. Aspectos Técnicos
  Encuanto a ls aspectos técnicos y funcionalidades, el proyecto se desarrollo utilizando JavaScript puro,
  HTML5 y CSS3 no se utilizaron librerias o frameworks. Ademas se consideraron los principios de modularización
  del codigo asi como los principios de diseño.
  
  Funciones:
  * FilterData: Esta función fue diseñada para filtrar los datosde las bandas segun su año de creación
    permite al usuario que conoce la cantidad de bandas creadas por año.
  * SortData :Esta función es la encargada de ordenar los datos de forma asendente y desendente, de esta
    forma el usuario logra ordenar las tarjetas alfabeticamente de la a a la z y biceversa.
  * ComputeStat: Esta función es la encargada de calcular la cantidad de bandas creadas en estados unidos
    para ello utiliza el metodo filter.
  * DecadasData:Esta función es la encargada de calcular el porcentaje de bandas creadas en la decadas de los
    noventa, para ello utiliza el metodo map y reduce.
  * para cada función mencionada con anterioridad se desarrollaron pruebas unitarias, estas se corrieron sobre
    un set de tatos acotado (fakeData) con la finalidad de revisar el correcto funcionamiento del codigo. 

## 7. Vista del Proyecto
[Link aplicación](https://github.com/AlvarezF7/DEV015-dataverse/tree/develop/src)
  
 
