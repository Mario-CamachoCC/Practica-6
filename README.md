# Practica 6

## Creando Apps Services

Pimero en la barra de busqueda del Portal de Azure busque "Apps Services" me fuí a la opción que aparecia, y ahí le di en crear.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/1.png)

En la configuración para crear la App Service y cambie solo los siguientes aspectos:

- **Grupo de Recursos:** Aquí cree un nuevo grupo de recursos llamado "Sesion4-AppService".

- **Nombre:** Este es el nombre de la instancia, así que yo le puse "MrGvRestaurant".

- **Pila del entorno en tiempo de ejcución:** Aquí puse PHP 8.0.

- **Región:** Aquí puse "South Central US" ya que es la más cercana a mi, y esto hace que tenga menos latencia.

- **SKU y tamaño:** Aquí escogí el plan gratuito.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/2.png)

Después de esto le di en "Revisar y crear", una vez validados los datos solo le di en "Crear" y espere a que se implementara la App Service. Mientras se implementaba me dirigí al acordeón del examen que el Sherpa nos dejo en Github y "Repliqué" un repositorio que había ahí, para ello copie el link que me daba.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/3.png)

Me dirigí a la carpeta donde quería clonarlo, y en la barra de direcciónes puse "cmd" y se abrio el simbolo del sistema con la dirección de es misma carpeta, y aquí puse el cómando "git clone" seguido del link que copie anteriormente, y con ello se clono el repositorio en la carpeta.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/4.png)

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/5.png)

Una vez hecha la carpeta la subi a github, en la practca 4 explico cómo hago eso.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/6.png)

Después regrese al recuros que cree, la App Service, y en su menú me fuí al apartado de "Implemntación" y de ahí a la opción de "Centro de Implementación".

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/7.png)

Ahí cambie ciertas opciones que son:

- Origen: Aquí le puse "Github" ya que se implementara desde el repositorio creado anteriormente.

- Sesión iniciada cómo: Aquí es mi cuenta de github donde tengo el repositorio.

- Organización: Aquí es mi usuario, que es donde tengo publicado el repositorio.

- Repositorio: Este es el repositorio donde esta la pagina web.

- Rama: main, aquí si que no se mucho de por que es main.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/8.png)

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/9.png)

Después de hacer todo esto simplemente le di en "Guardar", que esta en la barra de opciones de arriba.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/10.png)

Una vez hecho todo esto, podemos ir a el repositorio en GitHub, en la pestaña de "Actions" podremos ver cómo el repositorio ya se esta implementando.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/11.png)

Después de que se implementara ya podemos visitar la pagina web.

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/12.png)

![](https://github.com/Mario-CamachoCC/Practica-6/blob/main/img/13.png)

Puden visitarla en la siguiente liga [[Aquí](https://mrgvrestaurant.azurewebsites.net)]. Cómo es un plan gratuito solo se muestra por 60 minutos por día.
