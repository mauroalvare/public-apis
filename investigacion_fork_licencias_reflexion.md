## Fork

### ¿Qué es un fork?

Un fork consiste en la creación de una copia de un repositorio dentro de la cuenta personal del usuario en GitHub. A diferencia de un clone, esta copia no se encuentra en el entorno local, sino que permanece alojada en los servidores de la plataforma. A partir de su creación, el usuario posee control total sobre dicho repositorio, pudiendo modificarlo, eliminar contenido o reestructurarlo sin afectar al repositorio original.

### ¿Para qué se utiliza?

El uso principal de un fork es facilitar la contribución a proyectos desarrollados por terceros. En situaciones donde no se dispone de permisos de escritura, el flujo habitual implica realizar un fork, trabajar sobre esa copia y posteriormente enviar un Pull Request para que los responsables del proyecto evalúen la incorporación de los cambios.

Asimismo, el fork permite experimentar de manera independiente sobre un proyecto sin comprometer su estado original. También puede emplearse como punto de partida para el desarrollo de nuevos proyectos basados en implementaciones existentes, especialmente en el ámbito del software de código abierto.

### ¿Qué implica trabajar en un fork?

Es importante considerar que un fork no se sincroniza automáticamente con el repositorio original. Por lo tanto, si este último recibe actualizaciones, el usuario deberá integrarlas manualmente en su copia.

Además, el fork mantiene la licencia del proyecto original, lo cual implica respetar sus condiciones. Por ejemplo, en el caso de una licencia MIT, es obligatorio conservar el aviso de copyright y reconocer la autoría original.

### Diferencias entre fork y clone

Aunque suelen utilizarse conjuntamente, el fork y el clone cumplen funciones distintas.

El fork genera una copia remota en la cuenta del usuario dentro de GitHub, mientras que el clone descarga un repositorio al entorno local para su edición. En términos prácticos, el flujo más habitual consiste en realizar primero un fork y luego un clone de ese repositorio para trabajar localmente.

|                          | Fork                         | Clone                    |
| ------------------------ | ---------------------------- | ------------------------ |
| Ubicación                | Cuenta de GitHub             | Computadora local        |
| Visibilidad en GitHub    | Sí                           | No                       |
| Posibilidad de enviar PR | Sí                           | No directamente          |
| Uso principal            | Copia remota del repositorio | Trabajo en entorno local |

---

## Licenciamiento

### Licencia del proyecto

El proyecto public-apis se distribuye bajo la licencia MIT.

### Tipo de licencia

La licencia MIT es una licencia de software libre de carácter permisivo. Esto implica que permite un amplio rango de usos del código sin imponer restricciones significativas sobre su reutilización.

A diferencia de licencias más restrictivas, como la GPL, la MIT no obliga a que los proyectos derivados mantengan una licencia de código abierto.

### Permisos

La licencia MIT permite:

-Utilizar el código en proyectos personales o comerciales
-Modificar el código según las necesidades del usuario
-Distribuir o vender el software
-Integrar el código en proyectos con otras licencias

### Restricciones

La única condición relevante es la obligación de conservar el aviso de copyright y el texto de la licencia en cualquier redistribución del software.

### Uso en el ámbito académico

Incorporar una licencia en trabajos académicos, aunque no siempre sea obligatorio, constituye una buena práctica. Permite establecer claramente las condiciones de uso del trabajo y familiariza al estudiante con estándares propios del desarrollo profesional.

---

## Reflexión

### Rol de GitHub en el desarrollo open source

GitHub se ha consolidado como una plataforma central en el desarrollo de software de código abierto. Antes de su aparición, la colaboración distribuida resultaba considerablemente más compleja, ya que dependía de mecanismos como el envío de parches por correo electrónico y listas de discusión.

La plataforma introduce herramientas como Pull Requests, Issues y control de versiones accesible, lo que simplifica la coordinación entre múltiples desarrolladores. Además, el modelo de fork permite que cualquier usuario pueda contribuir a un proyecto sin requerir permisos iniciales.

Por otro lado, GitHub funciona como un portafolio profesional, donde la actividad del usuario —repositorios, contribuciones y frecuencia de trabajo— es visible para potenciales empleadores y colaboradores.

### Estandarización de prácticas

La adopción de prácticas estandarizadas responde a la necesidad de organizar el trabajo colaborativo. El uso de ramas, mensajes de commit descriptivos y Pull Requests permite mantener un flujo de trabajo ordenado y revisable.

Estos estándares también facilitan la incorporación de nuevos colaboradores, quienes pueden integrarse a proyectos sin necesidad de instrucciones detalladas, dado que el flujo de trabajo es ampliamente conocido.

### Importancia de la documentación

La documentación cumple un rol fundamental en proyectos colaborativos. Un proyecto sin documentación resulta difícil de comprender y utilizar para terceros, lo que limita su adopción y desarrollo.

Un archivo README claro y completo permite entender rápidamente el propósito del proyecto, su funcionamiento y las formas de contribuir. En el ámbito académico, la documentación también es clave, ya que forma parte del proceso de aprendizaje en el desarrollo de software y garantiza que el trabajo sea comprensible para otros.
