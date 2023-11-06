# IAW-practica0_Pull-request

## Creamos un repositorrio sin añardir el README
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/b14633e3-a101-4565-b009-dc6c8da15af6)

## Creamos el directorio
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/829fccc5-f9ec-4937-b2da-e7a571394db5)

## Creamos el repositorio
Iniciamos git 
con git add añadimos el readme
hacemos un commit de los cambios 
con git branch creamos una nueva rama 
con git remote add añadimos el repositorio 
aqui lo estamos estamos intentado conectar por http pero nos da fallo con la autetificacion, no podemos entrar
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/59b7ac44-2694-46dd-a3bc-bee14bbf409d)

## Clave SHH
ahora lo intentamos por ssh y no funciona 
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/104ec5f5-46f2-44ac-ba3f-ca9178bcdd76)

## Ver repositorios 
Git remote -v Este comando muestra una lista de los repositorios remotos configurados para el repositorio local, junto con las URL para recuperar (fetch) y enviar (push) datos. En este caso, se muestra que hay un repositorio remoto llamado "origin" con las URL (https) correspondientes.
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/c81ca187-84ad-4a5e-8b73-4174da253c03)

## Borrar repositorios 
git remote rm origin: Este comando elimina el repositorio remoto llamado "origin". (https) Esto significa que ya no se harán operaciones de push o fetch desde ese repositorio remoto. 
volvemos a hacer git remote -v y vemos que no hay nada y ahora si añadimos el repositorio por SSH, volvemos a hacer git remote -v y vemos que están añadidos.
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/fc6b3979-15cd-465b-aebd-e633cf17b77c)

## Guardar cambios
Ahora con git push -u origin main: Este comando envía (push) los cambios locales a la rama "main" del repositorio remoto "origin". El uso de "-u" establece la rama local "main" para hacer seguimiento de la rama remota "main" en "origin". Esto significa que en futuros comandos "git push" o "git pull", no necesito especificar el repositorio y la rama, ya que se utilizará "origin" y "main" por defecto. Nos pide la clave SSH
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/b0484aec-8d9b-4123-9df0-3273de532cc6)

## Ressultado final
Aqui vemos el repositorio remoto para trabajar en GitHub
![imagen](https://github.com/freddy13513/IAW-practica0_Pull-request_documentacion/assets/146179724/3b37e671-3de5-4c28-894d-b730e7df2394)







