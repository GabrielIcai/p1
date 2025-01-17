# Práctica 1

Este es el repositorio: https://github.com/GabrielIcai/p1 

## Comandos git básicos
Empezamos haciendo un git clone de p1 para tenerlo en local. Este comando hace una copia de un repositorio remoto y lo pega al local. Primero me muevo a tmp:

![Comando git clone](image.png)

Ahora me voy a crear un fichero que se llame prueba1 y con git status podremos ver información como comprobar si han habido cambios, la rama en la que me encuentro etc. Pero antes es necesario utilizar un git add para añadir el fichero. Este git add sirve para añadir los cambios realizados al area de preparación para que luego el git commit los pueda reconocer y establecerlos. Sin él, el fichero no es reconocible luego cuando haga el git commit:

![Comando git add y git status](image-1.png)

Ahora es necesario confirmar esos cambios. Como se puede observar en la imagen de debajo sigue habiendo cambios al escrcibir sobre el README que no estan confirmados:

![](image-2.png)

Hacemos el git commit que se encarga de registrar estos cambios y además añadimos una descripción de los que hemos confirmado:

![](image-3.png)

Ahora vamos a hacer el git push. Este comando nos permite subir los cambios de mi repositorio local al remoto que en este caso se identifica como origin:

![](image-4.png)

Finalmente vamos a probar los comandos de checkout. En primer lugar el git checkout -b "name" crea una nueva rama con el nombre "name" y te mueve a ella.

![](image-5.png)

Por último el git checkout main cambia a la rama main pero como ya esta creada no utiliza la -b:

![](image-6.png)

Como ya hemos terminado necesito hacer un commit de el README ya que estoy realizando la práctica aqui ademas de añadir todas las imagenes que he ido pegando y hacer un commit de ellas . 

Softwares Requeridos:
![](image-7.png)
![](image-8.png)
![](image-9.png)
![](image-10.png)