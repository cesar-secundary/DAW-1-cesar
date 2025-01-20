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

/\*\*/
