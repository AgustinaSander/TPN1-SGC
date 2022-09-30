# TPN1-SGC
TPN1 - Sistema de gestion de la configuracion
Grupo N5:
- Feresin, Mariano
- Sander, Agustina
- Sarina, Araceli
- Vergara, Agustina

2b) Al subir un proyecto a Github, generalmente se cuenta con una gran cantidad de archivos de configuraciones locales o dependencias del proyecto. Si no es necesario subirlos al repositorio externo se puede optar por crear un archivo .gitignore y definir todos los archivos que se desean ignorar a la hora de hacer un push del proyecto.

2g) Siguiendo Gitflow, para llevar un release al entorno productivo primero se debe hacer un PR de develop a master para mergear las ramas, pudiendo especificar un tag con el número de versión del release. Finalmente se debe hacer un backport de master a develop por si se realizaron hotfix.

2k) Siguiendo Gitflow, para llevar un feature al entorno productivo primero se debe hacer un PR de feature a develop, luego otro PR de develop a master para mergear las ramas, pudiendo especificar un tag actualizando el número de versión. Finalmente se debe hacer un backport de master a develop.

3a) En git está la posibilidad de documentar el proyecto mediante la creación de un archivo readme. Este se puede utilizar para informar acerca de la utilidad del proyecto, los encargados del mantenimiento y desarrollo del mismo, como las personas pueden iniciarlo y utilizarlo en su computadora, entre otras cosas. 

3b) Al realizar un Pull Request, GitHub nos brinda la posibilidad de agregar un titulo y una descripcion al PR. Con esto se puede especificar las funcionalidades y cambios que se quieren incorporar a otra rama.
A su vez, nos permite agregar reviewers los cuales seran los encargados de revisar los cambios propuestos y mergearlos o no a la rama destino.

