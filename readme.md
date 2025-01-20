# Capturas git

## Creamos un fichero txt con su contenido

![fichero txt](/img/fichero_create_txt.png)

### Comprobacion de usuario y email correctos

Como ya tengo el usuario y el correo configurados revisemos si estan bien con el siguente comando

```git
 git config user.name
 git config user.email
```

![git config](/img/git_config.png)

### inicializar repositorio

Inicializamos el repositorio de git y añadimos el remoto para
conectar nuestro repositorio a el repositorio que esta subido en github

![git init y git add remote](/img/image.png)

### cambiamos la Rama de maister a main

![git branch](/img/image.png)

Como podemos ver hemos cambiado nuestra rama principal de
main a master

### Revisamos la url del repositorio remoto

![git remote](/img/git_remote.png)

Vamos a comprobar si el repositorio remoto coincide con el de github

## añadimos contenido nuevo al archivo

![contenido nuevo](/img/fichero_create_txt_modify.png)

### Vamos a ejecutar el siguente comando

```git
git status
```

![git add](/img/git_addd.png)

Como podemos ver en la imagen dice que en la rama main no hay comits y dice que los ficheros no estan en seguimiento para incluirlos podemos usar el siguente comando

```git
git add ./
```

Usamos un git status para verficar si se añadieron

![Añadiendo ficheros](/img/git_add_files_add.png)

### Realizando commit

Un commit es como una fotografia del proyecto para guardar el progreso o si fallamos volver a el

```git
$ git commit -m "Primer commit del proyecto"
[main b245231] Primer commit del proyecto
 2 files changed, 3 insertions(+), 1 deletion(-)
 create mode 100644 img/git_add_files_add.png
```

### Ahora subimos este repositorio a github con este comando

Nos dara esta salida al ejecutar el comando

```git
 git push origin main
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 4 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 83.28 KiB | 6.94 MiB/s, done.
Total 17 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/cesar-secundary/DAW-1-cesar.git
 * [new branch]      main -> main
```

### Utilzamos este comando para ver el historial de commits

```git
git log
git reflog
```

Sin querer agrege un commit de mas por hacerlo en el archivo readme

![git log](/img/git_log.png)

### Git clone

Clonamos el repositorio desde git con este comando

```git
 git clone https://github.com/cesar-secundary/DAW-1-cesar.git

  Esta el la salida

Cloning into 'DAW-1-cesar'...
remote: Enumerating objects: 22, done.
remote: Counting objects: 100% (22/22), done.
remote: Compressing objects: 100% (18/18), done.
remote: Total 22 (delta 4), reused 22 (delta 4), pack-reused 0 (from 0)
Receiving objects: 100% (22/22), 98.52 KiB | 97.00 KiB/s, done.
Resolving deltas: 100% (4/4), done.

EDU+cesgarmun@C03010132-INFO6-41503 MINGW64 ~/Desktop/code/entornos
$ cd DAW-1-cesar/
```

### Renombramos el archivo

Realizamos un nuevo commit con estos comandos
