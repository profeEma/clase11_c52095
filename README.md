Repaso de git e incorporación de github
Recuerden que git trabaja de manera local y que github trabaja en la nube.
Yo tengo que tener un root con git inicializado y en paralelo, tener un repo creado dentro de mi usuario de github.
Luego de cumplir con estos dos pasos tengo que realizar la creación de un "tubo" que una las dos partes: en un extremo mi root local y en el otro, mi repo de github.
¿cómo creo mi repo en github?
Entro a mi usuario, toco sobre "repositorios" y luego toco el boton "new" (boton verde)
Ya en la pantalla de "crear repositorio" tengo que completarlo con un nombre único e irrepetible, dejar tildada la opción "public" y dejar todo como esta. Luego se me habilita el botón de "crear repositorio" (boton verde).
A partir de ahora, puedo usar el comando que crea el tubo entre las dos partes.
Cuál es el comando?
git remote add origin https://...
Este paso se ejecuta una sola vez y luego tengo que usar el comando:
git push -u origin master 
Para pasar toda la info de mi local por el tubo hasta mi repo de github. 