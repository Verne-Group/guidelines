# Primeros pasos:
## 1. ¿Obsidian?
---
De acuerdo a Wikipedia:
>**Obsidian** es un [software](https://es.wikipedia.org/wiki/Software "Software") para [tomar notas](https://es.wikipedia.org/wiki/Toma_de_notas "Toma de notas") y crear una base de conocimientos personal que funciona con archivos [Markdown](https://es.wikipedia.org/wiki/Markdown "Markdown"). Permite crear enlaces entre las notas y ver visualmente cómo están conectadas en forma de gráfico. Esto ayuda a organizar y estructurar ideas y conocimientos de una manera flexible y creativa. Además, es gratuito para uso personal y también ofrece licencias comerciales.

Hemos elegido Obsidian como herramienta para gestionar nuestra documentación por su comodidad de uso, por ofrecer su uso completamente gratuito y permitir mantener la posesión completa de los archivos que se escriben en él. Obsidian cuenta además con una creciente comunidad y cantidad de [plugins](https://obsidian.md/plugins) bastante útiles para nuestros propósitos.

Si bien Obsidian no es de código abierto, el que permita poseer los archivos que se crean nos hace pasar por alto esta característica. Obsidian nos permite visualizar, crear y editar nuestras notas y documentaciones de manera cómoda y amigable para todas las partes.

>[!faq] ¿Y usar uno open-source?
>Es posible cambiar a una alternativa open-source a este software si se llega a encontrar o desarrollar un buen candidato.

## 2. Instalación
---
<center><i>Antes de continuar, comprueba si tu plataforma soporta Obsidian. Puedes consultar sus distribuciones en el siguiente <a href="https://obsidian.md/download#platforms">enlace</a></i> </center>

- ### Windows
En la [página de descargas](https://obsidian.md/download) de Obsidian presionaremos el botón para descargar el ejecutable

>![[download-button.png]]

Una vez descargado el instalador, lo ejecutaremos y seguiremos el proceso habitual de instalar en Windows, que consiste en presionar siguiente > siguiente > aceptar > siguiente... hasta que esté instalado correctamente y esperar a que se abra.

## 3. Configuración con Github
---
#### Instalación del plugin Obsidian Git

Antes de empezar, debemos saber que esto es algo que deberemos hacer cada vez que creemos un vault para nuestras notas. Los plugins y sus configuraciones son guardadas localmente en cada directorio.
En el apartado de Settings ![[settings.png]]  > Community Plugins > Turn on community plugins > Community Plugins > Browse, buscaremos Obsidian Git (puede ser también encontrado en este [enlace](obsidian://show-plugin?id=obsidian-git)) y lo instalaremos, luego presionaremos Enable para habilitarlo (O en la pestaña de Community Plugins dentro de Settings, presionar el botón correspondiente al plugin, [^veáse la siguiente imagen]).

![[plugin-settings-button.png]]

>[!tip] Importante
>Obsidian git necesita que haya un repositorio .git creado en el mismo directorio del vault o en algún directorio anterior a este para poder funcionar. De lo contrario, no reconocerá el repositorio ni hará sus acciones correspondientes.

#### Configuración con Github

Este punto puede resultar algo tedioso tanto de hacer como explicar. Así que redirigiremos los pasos a sitios externos que han sabido explicarlo mejor que nosotros.

-  [Conectar a Github con SSH](https://docs.github.com/es/authentication/connecting-to-github-with-ssh)
- [Obsidian Git para principiantes](https://dannyhatcher.com/obsidian-git-for-beginners/)
>[!tip]
>A pesar de lo que diga el tutorial de arriba, no es necesario instalarse el Github Desktop. Con tener el SSH-Agent configurado en ~/.bashrc basta. Es **IMPORTANTE** que al momento de clonar los repositorios se haga con HTTPS si se quieren evitar complicaciones o problemas de autenticación.

A partir de este punto Obsidian Git ya tendrá soporte para los cambios que se vayan haciendo.

>[!tip]
>Recomendamos establecer en las configuraciones del plugin un tiempo de backup de 10 minutos (Para que en ese lapso de tiempo haga el stage, el commit y el push) y activar el pull automático al iniciar Obsidian.

# ¿Cómo usar Obsidian?:
---
Obsidian es una herramienta intuitiva de usar. Para sacarle el máximo proyecto recomendamos tener a la mano una [cheatsheet de markdown](https://www.markdownguide.org/cheat-sheet/) y leer cómo funciona dicho lenguaje. Si has usado herramientas similares como Notion o Evernote, esto te será sencillo de asimilar, es un poco lo mismo sólo que escribiendo tal cual lo que vas a poner en vez de una interfaz gráfica

Uno de los puntos más sólidos que constituyen a Obsidian son los gráficos y diagramas que se pueden hacer. Para entenderlos bien recomendamos dirigirse a la [documentación oficial](https://help.obsidian.md/Editing+and+formatting/Advanced+formatting+syntax).