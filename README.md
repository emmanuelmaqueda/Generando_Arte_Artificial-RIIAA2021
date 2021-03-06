# Generando Arte Artificial con GAN's - RIIAA 2021 Summer School

## Introducción

Las redes neuronales en general son una técnica de la IA la cuál se encuentra en auge en el
campo y son utilizadas usualmente, en especifico, las redes generativas adversarias (GANs) son
una técnica relativamente nueva la cuál tiene como finalidad (como su nombre lo indica)
generar nuevos datos (usualmente imágenes) a raíz de sus datos de entrenamiento los cuales
generalmente también son imágenes.
Las GANs se han usado en muchos aspectos como la generación de nuevas moléculas de
proteínas objetivo implicadas en el cáncer, la inflamación y la fibrosis, pueden reconstruir
modelos 3D de objetos a partir de imágenes, se usan para visualizar el efecto que tendrá el
cambio climático en sitios específicos o para simular apariencias de fotografías de rostros como
la senectud o el cambio de sexo, sin embargo una utilidad reciente y en tendencia ha sido el
llamado arte artificial siendo sus creadores los artistas digitales, artistas contemporáneos que
se enfocan en la generación de nuevas obras artísticas a través de éste tipo de técnicas.
¿Cómo sería una nueva obra de Rembrandt? o ¿Cuál sería el resultado sí combináramos el
estilo de arte de Monet y Frida Kahlo?. Con un aproximado podemos responder a estas
preguntas alimentando el generador de una GAN con obras de Rembrandt o de Monet y Frida 
Kahlo y dando salida a imágenes nuevas a raíz de las iniciales. Lo mismo puede hacerse con
fotografías, con diseños etc.
[Más información](https://riiaa.org/summer-school.html)

## Instrucciones para los asistentes

<b> 1. Descargar el dataset </b>  

Para prepararse para el tutorial deberá tenerse descargado un dataset con el cúal se entrenará la red neuronal GAN, decidimos dar libertad en este sentido así que ponemos a disponibilidad dos conjuntos de datos para generación de imágenes: 

<b> 1.1 Monet Dataset</b>

Conjunto de aproximadamente 900 imágenes de obras artísticas de Monet junto con algunas fotografías de imágenes reales de paisajes. Con este dataset podremos generar imágenes artificiales de paisajes con el estilo artístico de Monet.

[Descargar](https://turing.iimas.unam.mx/~ivanvladimir/gans/monet.zip)

<b> 1.2 CelebA Dataset</b>

CelebFaces Attributes Dataset (CelebA) es un conjunto de datos de atributos faciales a gran escala con más de 200.000 imágenes de celebridades, esta es una versión reducida de dataset con alrededor de 1000 imágenes. Las imágenes de este conjunto de datos cubren grandes variaciones de pose y desorden de fondo. Con este dataset podremos generar imágenes de rostros artificialmente.

[Descargar](https://turing.iimas.unam.mx/~ivanvladimir/gans/celeba.zip)

<b> * Al tener descargado el archivo comprimido debe subirse dicho archivo a su Google Drive personal (se debe crear una carpeta llamada 'data_tutorial' en el directorio raíz  con las dos notebooks que se encuentran en el directorio './notebooks' de este repositorio y el archivo comprimido del dataset elegido) </b>

<b> * Tener en cuenta que se requiere alrededor de 1.5 GB libres en su Google Drive personal </b>

---

<b> 2. Configurar el entorno de Google Colab para el uso de GPU's </b>  

Una vez alojada la notebook 'Artificial_Art_GAN' en el Google Drive debe poder abrir el archivo en el entorno de Google Colab, una vez dentro deberá dirigirse a la barra de herramientas en la sección de <b> Entorno de Ejecución </b> en la opción de <b> Cambiar tipo de entorno de Ejecución </b> como se muestra en la imagen ilustrativa.

![image](https://user-images.githubusercontent.com/64985126/128061872-2ee99561-7a75-4fff-94c7-cd3aa5fbd597.png)

Al seleccionar la opción obtendrá una ventana emergente como la que se muestra en la imagen ilustrativa siguiente, ahi deberá seleccionar la opción de <b>GPU</b> en la sección de <b>Acelerador de Hardware</b>, al terminar se deberan guardar los cambios lo cual hará que el entorno de ejecución se reinicie con la configuración actual.

![image](https://user-images.githubusercontent.com/64985126/128063503-b4ed7dd1-d90e-41f8-9be9-2160c91ef29c.png)

Para verificar que la configuración fue exitosa podemos acudir a la esquina superior derecha donde encontraremos un pequeño botón que referencía a la memoria RAM y el HD de nuestra máquina virtual, si lo presionamos abrira una ventana donde obtendremos las estadísticas del uso de los recursos computacionales de la misma, si la configuración fue exitosa esta ventana hara referencia a que esta en uso una GPU del equipo de Google.

![image](https://user-images.githubusercontent.com/64985126/128063769-8dec528f-8c70-404b-83fe-e78eacf1d062.png)

---

<b> 3. Recomendaciones finales </b>  

* Dentro de este mismo repositorio en el directorio <b> ./data </b> se encuentra un documento llamado 'Apuntes - Introducción a las redes neuronales' el cuál es una breve introducción a las redes neuronales y su funcionamiento, puede consultarse previo al tutorial para tener mas contexto de la temática del mismo.

* Si se tiene un problema con alguno de los pasos antes mencionados no dude en [contactarnos](mailto:dmaqueda71@gmail.com).

<b> ¡ Nos vemos en unos días en la RIIAA 2021 ! &#128521; </b> 


