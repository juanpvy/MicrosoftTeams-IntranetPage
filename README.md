# MicrosoftTeams + IntranetPage

En este post vamos a ver cómo podemos mostrar una página de SharePoint online en Microsoft TEAMS en la barra de apps.

![image](https://user-images.githubusercontent.com/50918464/135352248-83c30000-f8a2-429e-9104-e99ada79a590.png)

Para hacerlo tenemos que hacer un archivo ZIP que contendrá tres archivos.
* manifest.json
* color.png
* outline.png


## Configuración

En la carpeta Intranet encontraras los tres arhivos , hay que descargarlos y  editar el archivo manifest.json , reemplazando todo lo que diga [TENANT] por el valor adecuado.
Se puede editar las imágenes para utilizar otros logos, solo hay que respetar el formato y las dimensiones.

Teniendo los tres archivos listos

![image](https://user-images.githubusercontent.com/50918464/135354186-7ab1c97b-924b-47c2-92c5-28da5dbf2b01.png)

Es necesario crear un archivo ZIP seleccionado los tres archivos, NOOO hay que crear una carpeta para que los contenga , tienen que estar los tres a nivel raíz.

![image](https://user-images.githubusercontent.com/50918464/135354467-6b6c51a9-811d-49f2-bfff-c8ee7c33a30d.png)

Lo siguiente es cargar el archivo a Microsoft TEAMS, seleccionamos el icono de "apps" > "Upload a custom app" > "Upload for my org" > "Seleccionar el archivo ZIP"

![image](https://user-images.githubusercontent.com/50918464/135354684-7a78d65c-4764-4e4a-8fe6-b94fef634c03.png) 

La app "Intranet" saldrá en el catálgo de apps de la organización , hay que seleccionarla y dar clic en "ADD"
![image](https://user-images.githubusercontent.com/50918464/135355049-c1a4eb6f-f0a0-44bd-922a-8951dcae9b3d.png)

La  app se mostrara en el lado izquierdo con el nombre de intranet

![image](https://user-images.githubusercontent.com/50918464/135354882-3f43b389-0ce1-4bdb-929e-2e6e6c7f1415.png)

Copia, Pega, Edita y Prueba !!!

