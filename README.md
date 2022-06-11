# Uso de Azure Cognitive Services para detectar rostros
En este repositorio tenemos una demostración del uso de Azure Cognitive Services, pare detectar rostros y conocer, su género, edad, y si usan lentes.

![Microsoft-Azure-Machine-Learning](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/Microsoft-Azure-Machine-Learning.jpg)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.

---

## Importante
- En este caso haremos la práctica desde una Notebook en Estudio de Microsoft Azure Machine Learning, pero se puede realizar desde un editor de texto.
- El código fue sacado desde https://github.com/josejesusguzman/face-api-consumption-python

---

## Pasos a seguir
- Como en este caso lo haremos desde Estudio de Microsoft Azure Machine Learning, nos iremos al apartado de "Notebooks".
- Crearemos un archivo y pegaremos el código del siguiente repositorio, https://github.com/josejesusguzman/face-api-consumption-python
![P1](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/P1.PNG)

- Ahora iremos a [Microsoft Azure](https://portal.azure.com) y crearemos una "API Face de Cognitive Services".
![P2](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/P2.PNG)

- Nos pedirá lo de siempre, Suscripción, Región, Nombre Y Grupo de Recursos, además de algunas configuraciones más.
![P3](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/P3.PNG)

- Ya creado el recurso, nos iremos al apartado de "Claves y punto de conexión".
- Copiaremos la "Clave" y lo pegaremos en el código que conseguimos anteriormente, en el apartado de "subscription_key".
- También copiaremos la "endpoint" o "extremo" y la pegaremos en el apartado de "face_api_url".
- Después pegaremos el link de nuestra imagen en "image_url".
![P4](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/P4.PNG)

- Y el resultado quedaría algo así, en este caso hice pruebas con dos imágenes diferentes, de la misma persona.
![P5](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/P5.PNG)
![P6](https://github.com/DagonNR/Cognitive-Services-Face-Detection/blob/main/images/P6.PNG)
