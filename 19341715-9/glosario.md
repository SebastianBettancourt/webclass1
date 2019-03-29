a. Control de versiones (VC): Registra los cambios realizados en un proyecto / sistema a traves del tiempo , ademas da la informacion de quien hizo el cambio entre otras mas

https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones


b. Control de versiones distribuido (DVC) : Los que acceden al repositorio local no solo tienen acceso a el , si no que replican todo el repositorio en su computador (clonar )
por lo que en caso de que el repositorio remoto se caiga , este no se pierda ya que todos los que interactuaron con el tienen una copia de este

https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones 

c. Repositorio remoto y Repositorio local: Un repositorio remoto es alguna version del proyecto que se encuentra alejado en un servidor externo , a su vez el repositorio
local es lo mismo pero alojado en nuestro computador (localmente )

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

d. Copia de trabajo / Working Copy:Es una copia de nuestro proyecto que le podemos realizar todos los cambios que queramos , sin modificar nada del original

http://www.syncrosvnclient.com/software-archive/InstData4.2/doc/ug-syncroSVNClient/define-working-copy.html
https://stackoverflow.com/questions/581220/what-is-a-working-copy-and-what-does-switching-do-for-me-in-tortoise-svn

e. Área de Preparación / Staging Area: Es un area o caja de pruebas donde podemos hacer cambios pero sin todavia "actualizarlos en el repositorio "

https://dev.to/sublimegeek/git-staging-area-explained-like-im-five-1anh

f. Preparar Cambios / Stage Changes: 

https://dev.to/sublimegeek/git-staging-area-explained-like-im-five-1anh
g. Confirmar cambios / Commit Changes: Esto confirma que el area de stage este lista , y pushea los cambios que se generaron en esta al repositorio

https://dev.to/sublimegeek/git-staging-area-explained-like-im-five-1anh

h. Commit:confirma cambios en la rama principal del repositorio local

https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

i. clone:crea una copia (working copy) de nuestro repositorio local y/o clona un repositorio remoto a nuestro repositorio local
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

j. pull:Carga los cambios de la/s ramas del repositorio remoto al repositorio local actualizandolo con la ultima version del remoto
https://git-scm.com/docs/git-pull

k. push: envia cambios a la rama principal del repositorio remoto
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

l. fetch: Parecido al pull pero la diferencia es que los cambios recibidos los guarda en otras ramas distintas 
https://es.stackoverflow.com/questions/245/cu%C3%A1l-es-la-diferencia-entre-pull-y-fetch-en-git

m. merge:combina dos ramas en una
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

n. status: muestra una lista con los cambios realizados en el repositorio local
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

o. log:
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

p. checkout: crea una nueva rama o para cambiar a otra rama de trabajo
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

q. Rama / Branch: una rama es una parte del repositorio o mas bien como "como un subrepositorio", lo cual sirve para hacer cambios solo en 1 branch y no afectar al repositorio como un total
https://git-scm.com/book/en/v1/Git-Branching-What-a-Branch-Is
https://longair.net/blog/2009/04/16/git-fetch-and-merge/

r. Etiqueta / Tag: Es una funcion para marcar puntos y/o renombrar versiones del repositorio
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Creando-etiquetas

