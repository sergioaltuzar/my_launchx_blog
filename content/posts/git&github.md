---
title: "Git & Git Hub"
date: 2022-04-25
description: 'Que son Git & Git Hub y Sus Principales Diferencias'
---
Git y GitHub sirven para proveer un control de versiones de un código, unificarlo e inclusive compartirlo, 
pero estas son todas las similaridades de las dos plataformas, según señala el portal Simple Learn.
De hecho, señala que, si buscáramos una analogía, Git sería un computador, mientras que Github representaría
una red de computadores que están llevando a cabo una misma tarea, pero con diferentes métodos.

**¿Qué es Git?**  

Git es un sistema de control de versiones distribuido (DVCS) de software de código abierto y gratuito diseñado para administrar todo 
el historial del código fuente. Este les permite a los desarrolladores mantener un historial de las confirmaciones, revertir cambios y 
compartir códigos con otras personas. Para poder usarlo se debe instalar en el computador. Esto quiere decir que las personas que lo usan no
necesitan de Internet para usarlo o acceder a su repositorio local.

Es actualmente unas de las herramientas más conocidas y usado por empresas como Amazon, Microsoft, Facebook, por solo nombrar algunas.  
  
**¿Qué es Github?** 

Github es un repositorio de Git, ofrece control de versiones y administración de códigos entre otras funcionalidades. Por ejemplo, la creación de proyectos colaborativos y seguimiento de fallas o errores. Al ser una red, no está guardado en nuestro computador, sino en la nube. Lo que quiere decir que necesita de Internet y para usarlo o acceder a su biblioteca necesitamos una conexión.

Existen versiones de escritorio, pero esto no significa que este instalado en nuestro computador, en su lugar es una herramienta que ayuda a sincronizar nuestro computador con el servidor.

Los desarrolladoras pueden usarlo como backups para crear repositorios a los que acceden después y para compartirlo con otros. Además, es importante resaltar que Git puede ser usado sin Github, pero no en viceversa. Además, las dos son herramientas gratuitas, una de las principales características de los software open-source, pero no le pertenecen a la misma compañía. Git es de Linux y fue lanzado en 2015; mientras que Github es de Microsoft.

Actualmente tienen varios competidores; por ejemplo, Gitlab. Pero esta no tiene un repositorio tan extenso como Github.  

**¿Por qué GitHub es tan popular?**

GitHub aloja más de 100 millones de repositorios, la mayoría de los cuales son proyectos de código abierto. Esta estadística revela que GitHub se encuentra entre los clientes Git GUI más populares y es utilizado por varios profesionales y grandes empresas, como Hostinger.

Esto se debe a que GitHub es una plataforma de gestión y organización de proyectos basada en la nube que incorpora las funciones de control de versiones de Git. Es decir que todos los usuarios de GitHub pueden rastrear y gestionar los cambios que se realizan en el código fuente en tiempo real, a la vez que tienen acceso a todas las demás funciones de Git disponibles en el mismo lugar.

Además, la interfaz de usuario de GitHub es más fácil de usar que la de Git, lo que la hace accesible para personas con pocos o ningún conocimiento técnico. Esto significa que se puede incluir a más miembros del equipo en el progreso y la gestión de un proyecto, haciendo que el proceso de desarrollo sea más fluido.

1. Crear un Repositorio de GitHub
Un repositorio, o repo, será el eje central de tu proyecto. Puede ser un archivo o una colección de archivos que contengan código, imágenes, texto o cualquier otra cosa.

Para comenzar el proceso, sigue estos pasos:

Dirigete a tu repositorio de GitHub, y el la seccion repositories da click en el boton verde New.
![1](https://user-images.githubusercontent.com/77743897/165181695-a14bf3e1-20cb-459f-b3ce-5e154e07d99b.png)


La sección Owner ya tendrá el nombre de tu cuenta. Crea un nombre de repositorio. Comprueba si está configurado como Público para que sea de código abierto, y luego marca la casilla Add a README file. Finalmente, haz clic en Create repository.

![2](https://user-images.githubusercontent.com/77743897/165182004-4daa01c5-1b78-4bf8-a9cb-82c98cababa1.png)


Felicitaciones, ya has creado un nuevo repositorio que contendrá el archivo original de tu proyecto. El siguiente paso es aprender lo que puedes hacer con él.

2. Crear ramas en GitHub
Con la creación de ramas, generas diferentes versiones de un repositorio. Al hacer cambios en el proyecto en la rama de características, un desarrollador puede ver cómo afectará al proyecto maestro cuando se integre.

Así es como puedes generar una rama de características:

Ve a tu nuevo repositorio. Pulsa el botón main e introduce el nombre de tu nueva rama de características. Haz clic en Create branch.

![3](https://user-images.githubusercontent.com/77743897/165182601-222c1c70-c55d-4690-847b-3d407fa9ab1a.png)

Ahora has creado una rama de características que se ve idéntica a la rama maestra. Puedes empezar a hacer cambios en ella libremente sin afectar al proyecto.

3. Entender los commits de GitHub
Los commits son la forma en que se denominan los cambios guardados en GitHub. Cada vez que cambies el archivo de la rama de características, tendrás que hacer un Commit para mantenerlo.

A continuación te explicamos cómo hacer y confirmar un cambio:

Accede a la rama de características haciendo clic en main y seleccionando tu rama recién creada en el menú desplegable.

![4](https://user-images.githubusercontent.com/77743897/165182698-ad638d65-c662-4b4a-b1e8-096f10674936.png)

Haz clic en el «icono del lápiz» para empezar a editar el archivo. Cuando hayas terminado, escribe una breve descripción de los cambios realizados. Haz clic en Commit changes.

![5](https://user-images.githubusercontent.com/77743897/165182753-6c7ec52c-d429-4844-bc30-4b0402fbe32b.png)

4. Crear solicitudes de extracción en GitHub
Para proponer los cambios que acabas de hacer a otros desarrolladores que trabajan en el mismo proyecto, debes crear una solicitud de extracción. Estas facilitan el trabajo conjunto en los proyectos, ya que son la principal herramienta de colaboración en GitHub.

Las solicitudes de extracción te permiten ver las diferencias entre el proyecto original y tu rama de características. Es la forma de pedir a tus compañeros que las revisen. Si los otros desarrolladores lo aprueban, pueden fusionar la solicitud de extracción, lo que aplicará esos cambios al proyecto principal.

Para hacer una solicitud de extracción sigue los siguientes pasos:

Haz clic en Pull requests -> New pull request. En Example comparisons, selecciona la rama de características en la que estabas trabajando.


![6](https://user-images.githubusercontent.com/77743897/165182828-9cd78388-e24a-4eb3-afe1-c52b18b6209a.png)


Revisa los cambios una vez más y haz clic en Create pull request. En la nueva página, escribe el título y proporciona una breve descripción de lo que has trabajado para promover la fusión. Haz clic en Create pull request.



![7](https://user-images.githubusercontent.com/77743897/165182890-15bb4e2d-dd96-497f-ab01-ea9bf77c48ee.png)

Ahora otros desarrolladores podrán fusionar los cambios que hiciste con los archivos originales del proyecto.

Si quieres saber todo lo demás sobre cómo empezar en GitHub, puedes consultar esta consulta esta [guía](https://docs.github.com/es/get-started/quickstart/hello-world).

Conclusión
Aunque GitHub es conocido principalmente dentro de la comunidad de desarrollo de software, puede ser utilizado en una variedad de industrias diferentes. Cualquier equipo o empresa que trabaje en diferentes proyectos que requieran desarrollo en forma de archivos puede utilizar este servicio.

Por ejemplo, los equipos de contenido y marketing pueden utilizar GitHub para organizar sus proyectos. Los creativos freelance pueden utilizarlo para gestionar su trabajo cuando trabajan con otras personas.

Usar GitHub no significa necesariamente usar código o ser un desarrollador. Es una plataforma de sistema de control de versiones gratuita que puede utilizarse de muchas maneras diferentes.


Referencias: 
https://docs.github.com/es/get-started/quickstart/hello-world

https://www.hostinger.es/tutoriales/que-es-github

https://kinsta.com/knowledgebase/git-vs-github/

https://aprendeia.com/que-es-git-y-github/







