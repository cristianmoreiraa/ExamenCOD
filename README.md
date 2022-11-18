# examenDAM
Para utilizarlo en el examen

##Cristian Moreira Examen COD

1--> Clonamos el repositorio: https://github.com/damiancastelao/examenDAM.git
	Lo clonamos utilizando: *git clone* https://github.com/damiancastelao/examenDAM.git
	
2-->Creo un repositorio en GitHub: https://github.com/cristianmoreiraa/ExamenCOD.git

3-->Con el comando mkdir desde la consola creo una nueva carpeta llamada "Programa", en la cual meteré el código.

4-->*git init*: para iniciar el repositorio Git

5-->*git add*. Para que se añada todo los ficheros que tengo en 'examenDAM'

6-->Hago la primera commit "1ra commit" usando: *git commit -m "1ra commit"*

7-->Cambio el remote para hacer el push en mi repositorio: *git remote set-url origin (link de mi repo)*
 
8-->Subo todo a mi repo usando: *git push*

9-->Cambio el nombre del autor del commit mediante el comando: *git config --global user.name "Cristian Moreira"*

10-->Subo el segundo commit

11--> Realizo el diagrama de flujo de mi programa llamado "ParaCOD"


	´´´mermaid
	graph TD;
    I-->mostrarMenu;
    mostrarMenu-->introducirOpcion;
    introducirOpcion-->B{switch};
    B--=1-->introducirLado;
    B--=2-->introducirB,H;
    B--=3-->introducirR;
    B-->opcionIncorrecta;
    introducirLado-->sup=L*L;
    sup=L*L-->VisualizarSup;
    VisualizarSup-->Fin
    introducirB,H-->sup=b*h/2;
    sup=b*h/2-->VisualizrSup;
    VisualizrSup-->Fin;
    introducirR-->sup=PI*r2;
    sup=PI*r2-->VisualizaSup;
    VisualizaSup-->Fin;
    opcionIncorrecta-->Fin;
   ´´´
