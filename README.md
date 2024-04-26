# pruebas_saber_pro_colombia
#Repositorio dedicado al proyecto de pruebas saber pro Colombia para la materia de Introducción a la Inteligencia Artificial

## Miembros del grupo
* Rafael Osorio Gómez, CC.1036928503, Ingeniería de Sistemas
  
## Datos
Los datos del proyecto vienen de la competición [UDEA/ai4eng 20241 - Pruebas Saber Pro Colombia](https://www.kaggle.com/competitions/udea-ai4eng-20241). 

Los pasos para hacerlos disponibles en google collab son los siguientes:

1. Estando logueado en la cuenta de Kaggle, irse a Settings y dar click en "Create New Token":  

![image](/Create new token.png)

Después de dar click, se descargará un archivo llamado Kaggle.json

2. En el notebook de google Collab ejecutar las siguientes lineas de comando:
```
  !pip install kaggle
  
  from google.colab import files 
  files.upload()
```
Luego dar click en el boton "Elegir archivos" para cargar el archivo .json

![image](https://user-images.githubusercontent.com/55060788/233894298-1c75936e-c9ab-4c9d-8264-da97fa2920e0.png)

3. Por ultimo ejecutar las siguientes lineas de codigo:

```
  ! mkdir ~/.kaggle
  ! cp kaggle.json ~/.kaggle/
  ! chmod 600 ~/.kaggle/kaggle.json
  !kaggle competitions download -c allstate-claims-severity
  !unzip allstate-claims-severity.zip
```
Entrega 2.

Enlace del video 




