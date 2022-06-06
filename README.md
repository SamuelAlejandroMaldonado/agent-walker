# agent-walker

Paso 1. Elegir la versión, plan. Posteriormente proceder a descargar e instalar unity.
 ![image](https://user-images.githubusercontent.com/58333529/172213400-bb4fc8ed-0d2f-45a7-a35d-49daac0f60bc.png)


Paso 2. Descargar e instalar Python 3

 
![image](https://user-images.githubusercontent.com/58333529/172213432-b4006772-8460-4ca8-9fae-6cb9acdd7d47.png)


Paso 3 descargar ML-AGENTS para integrarlo en unity


 

![image](https://user-images.githubusercontent.com/58333529/172213439-2d93e31d-4d01-4956-908d-dc2f89047a20.png)



Paso 4 Desarrollo en Unity
 Window>Package Manager
 ![image](https://user-images.githubusercontent.com/58333529/172213457-db60c453-ad59-40b5-942e-9b6ad756217d.png)



Package manager> add package from disk


 ![image](https://user-images.githubusercontent.com/58333529/172213467-1e05ec91-5dd4-495c-a750-6605a88356a5.png)



Seleccionar el package.json de la carpeta ML-AGENTS previamente descargada

 
![image](https://user-images.githubusercontent.com/58333529/172213489-a81fe4be-ad53-46ff-92e3-b29e6438e69d.png)

Si se desea, tomar como base uno los ejemplos de la librería ml- agents, para el presente proyecto se tomo como base el modelo Walker pero se lo adapto para un modelo 3D bípedo.
 ![image](https://user-images.githubusercontent.com/58333529/172213495-87c0e0a6-54b5-4a38-aa5f-acc68d02bb19.png)





Modelo 3D, el siguiente paso es elegir un modelo que se adapte al objetivo propuesto.
 ![image](https://user-images.githubusercontent.com/58333529/172213506-fc6e4af2-139c-4e07-a7aa-caf7fb9dcb1b.png)
![image](https://user-images.githubusercontent.com/58333529/172213511-8003f4ff-698f-4271-a65e-2b6ce6e97dc3.png)
El siguiente paso es instalar las dependencias de ML-AGENTS.

 ![image](https://user-images.githubusercontent.com/58333529/172213577-a8c64173-05e6-4e15-92a4-5dfc64e0bd21.png)


Para entrenar el agente se deben seguir los siguientes pasos:
Ir a la carpeta del proyecto

![image](https://user-images.githubusercontent.com/58333529/172213631-0fc29f1e-4e73-41e8-a8ac-0066493d6a45.png)
Entrar a la carpeta Assets>sWalker
![image](https://user-images.githubusercontent.com/58333529/172213656-6ee9ef9d-525e-4e6c-becd-e54a13a75232.png)
Abrir una consola en la carpeta

![image](https://user-images.githubusercontent.com/58333529/172213706-c1b7ebc6-c9bd-4235-9358-f50151dac84f.png)
![image](https://user-images.githubusercontent.com/58333529/172213724-806a2ae9-3d7c-44c7-90cf-26050bd3acac.png)

Una vez abierta la consola, escribir el comando mlagents-learn.

![image](https://user-images.githubusercontent.com/58333529/172213761-8e5630a7-4407-4de5-bc6a-59d8c2f43d7a.png)



Presionar play en unity
Al presionar play se puede observar como primero el agente se cae y luego va aprendiendo a caminar.
![image](https://user-images.githubusercontent.com/58333529/172213788-a25e5e9a-1f01-4bba-a9e0-3683e38aa6de.png)


 
