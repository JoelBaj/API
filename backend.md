<p align="center"><a href="#" target="_blank"><img src="https://duragaspromo.com/img/logo.png" width="400" alt="Duragas Logo"></a></p>

 
# Backend
## Contenido
- [1.- Configuraciones de manera local](#1--configuraciones-de-manera-local)
- [2.- Servidor](#2--servidordeployment)


## 1.- Configuraciones de manera local
---
### 1.1.- Levantar el proyecto
- Revisar si el servicio wildfly está detenido, si esta en ejecución proceda a detenerlo.
- Una vez clonado el proyecto de manera local, procedemos abrirlo en el IDE 
- Ubicarse en el archivo pom.xml, busque las siguientes dependencia en el cual debe seguir las siguientes instrucciones:
   
   * Debe tener comentado el tomcat como se presenta la siguiente imagen:

   ![alt text](./src/img/tomcat.png)

   * Debe tener descomentado el tomcat y jasper como se presenta las siguiente imagen:

   ![alt text](./src/img/tomcat_jasper.png)


- Una vez hecho las modificaciones, proceda actualizar el maven.

   ![alt text](./src/img/maven.png)

- Finalmente ejecutar el proyecto.


### 1.2.- En caso de error al levantar el proyecto

- Abrir la terminal del IDE, escribir los siguientes comandos
```
   rm -r target
   rm .classpath
   rm -proyect
   mvn eclipse:eclipse
   
```
- En caso de que no se compile el proyecto, Comunicar a la persona encargada: 
```
```
### 1.3 Deploy de proyecto de manera local

### 1.3.1- Guia para crear Archivo.War
 - Dirigise al archivo pom.xml
 - Debe tener descomentado el tomcat que se muestra en la siguiente imagen:
![alt text](./src/img/pom.png)
- Luego debe comentar el tomcat y jasper que se muestra en la siguiente imagen:
![alt text](./src/img/pom.xml.png)
- Una vez hecho los pasos anterior, Abrir la terminal del IDE, escribir los siguientes comandos
```
   rm -r target
   rm .classpath
   rm -proyect
   mvn eclipse:eclipse
   mvm clean package
```
- Por ultimo Ejecutar el proyecto.



Ubicacion de arhivo .war
 buscar archivo

---
### 1.4.- Deploy de archivo war de manera local
---
- Importante detener la api
- Seguir las instrucciones del manual en el siguiente URL:

```
 
``` 
- En caso de seguir con el error 
- Ubicarse en el parámetro: -XX:MaxMetaspaceSize modificarlo al tamaño de "3052m"

### 1.4.1.- En caso de error al deployar

 - Si exite problema al levantar el servidor, comuniquese con la persona encargada.
 ```
 
```


---
## 2.- Servidor(Deployment)
---
- Importante tener conectado la VPN
- Seguir las instrucciones del manual en el siguiente URL:
```
 
```
