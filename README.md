# devjumpers

__GIT - GITHUB : Ejercitación Final__

- git clone https://github.com/francobenjaminformigo/devjumpers __(Dlonamos el repositorio)__

- touch README.md
  __(Desde el main, creamos el archivo README.md)__

- git add .
  __(Agregamos los cambios)__

- git commit -m "commit inicial"
  __(Commiteamos para registrar los cambios)__

- git push
 __(subimos los cambios al repositorio)__

- mkdir privada
  __(creamos la carpeta privada)__

- touch privado.txt
  __(creamos el archivo privado.txt)__

- touch .gitignore
  __(creamos el archivo gitignore)__

- __Dentro del archivo .gitignore agregamos lo siguiente:__
  /privado.txt
  privada/

- touch 1.txt
  __(creamos el archivo 1.txt)__

- git checkout -b v0.2
  __(creamos la rama v0.2 y nos redirigimos a la misma)__

- touch 2.txt
  __(creamos el archivo 2.txt)__

- git add .
  __(Agregamos los cambios)__

- git commit -m "creacion de archivos 1.txt, 2.txt, .gitignore y rama v0.2"
  __(Commiteamos para registrar los cambios)__

- git push
  __(subimos los cambios al repositorio)__

- git checkout main
  __(volvemos al main)__

- git merge v0.2
  __(hacemos merge de la rama v0.2 al main)__

- __Escribimos "Hola" en el archivo 1.txt__

- git add .
  __(Agregamos los cambios)__

- git commit -m "modificacion en archivo 1.txt"
  __(Commiteamos para registrar los cambios)__

- git checkout v0.2
  __(nos posicionamos en la rama v0.2)__

- __Escribimos "Adios" en el archivo 1.txt__

- git add .
  __(Agregamos los cambios)__

- git commit -m "modificacion en archivo 1.txt en la rama v0.2"
  __(Commiteamos para registrar los cambios)__

- git checkout main
  __(volvemos al main)__

- git merge v0.2
  __(hacemos merge de la rama v0.2 al main)__

- __Nos aparece un errror, lo resolvemos y commiteamos__

- git add .
  __(Agregamos los cambios)__

- git commit -m "solucion de conflictos"
  __(Commiteamos para registrar los cambios)__

- git branch --merged
  __(para que nos devuelva la rama main)__

- git branch --no-merged
  __(para que nos devuelva la rama v0.2)__

- git branch -D v0.2
  __(borramos la rama v0.2)__

- git push
  __(subimos los cambios al repositorio)__

- git list
  __(vemos el listado de los commits)__

* a26926e (HEAD -> main, origin/main) solucion de conflictos
  |\
  | \* 9a93451 modificacion en archivo 1.txt en rama v0.2
* | 5bd080e modificacion en archivo 1.txt
  |/
* 0ba3e9d creacion de archivos 1.txt, 2.txt, .gitignore y rama v0.2
* 8e5ddae commit inicial

- FOTO DE PERFIL AGREGADA
- DOBLE FACTOR DE AUTENTIFICACION ACTIVADO CON LA APP AUTHY

| NOMBRE         | GITHUB                            |
| -------------- | --------------------------------- |
| DAMIAN CORONEL | [https://github.com/Damsh-bit]    |
| CAMILA RIOS    | [https://github.com/camilarios01] |
| CRISTIAN ORTIZ | [https://github.com/Cristian550/] |
