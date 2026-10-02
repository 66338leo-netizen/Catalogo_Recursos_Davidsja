1. ¿Qué ventaja tiene registrar las dependencias del proyecto en requirements.txt en lugar de compartir la carpeta .venv?

La ventaja es que requirements.txt permite registrar las librerías y versiones necesarias para que otra persona pueda instalar las mismas dependencias en su propio entorno virtual. La carpeta .venv no se comparte porque contiene archivos específicos de la computadora y puede ocupar mucho espacio.

2. ¿Por qué el repositorio que tienes ahora en tu computadora no es el mismo concepto que el fork creado en GitHub?

El repositorio local es una copia del proyecto que está almacenada en nuestra computadora y donde hacemos cambios y commits. El fork es una copia del repositorio creada dentro de nuestra cuenta de GitHub, que permite trabajar y subir cambios de manera independiente al repositorio original.

79. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?
Consultando la documentación de Git, usando la ayuda de los comandos y buscando ejemplos relacionados con la tarea.

80. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?
Preparar un archivo lo agrega al área de preparación con git add. Crear el commit guarda esos cambios en el historial con git commit.

81. ¿Cómo puedes comprobar en qué rama estás trabajando?
Con el comando git branch o git status.

82. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?
Con el comando git status.

83. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?
Con el comando git diff.

84. ¿Por qué debe reconstruirse .venv después de obtener un repositorio?
Porque .venv normalmente no se guarda en GitHub. Se debe crear nuevamente el entorno e instalar las dependencias usando requirements.txt.

85. ¿Qué relación existe entre requirements.txt y .gitignore?
requirements.txt registra las dependencias necesarias del proyecto, mientras que .gitignore evita subir archivos o carpetas innecesarias, como .venv.

86. ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?
Porque permite realizar cambios de forma independiente sin afectar directamente la versión principal del proyecto.

87. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?
Porque una solicitud de cambios puede actualizarse con nuevos commits realizados en la misma rama. Los nuevos cambios aparecen automáticamente en el Pull Request existente.

88. Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?
Porque el repositorio local todavía puede tener una versión anterior de main. Es necesario hacer git pull para descargar los cambios realizados en GitHub.