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

# Reflexión

## GitHub y el open source

GitHub transformó la colaboración en proyectos abiertos. Antes, coordinar con otras personas era engorroso: parches por correo, listas de discusión, permisos para todo. Ahora, con Pull Requests, Issues y forks, cualquiera puede contribuir sin fricciones y el historial queda ordenado por defecto.

También funciona como vitrina profesional: lo que publicás y cómo contribuís es visible para quienes te quieran contratar o colaborar.

## Estandarizar el flujo de trabajo

Usar ramas, escribir buenos mensajes de commit y trabajar con Pull Requests no es burocracia, es lo que hace que un proyecto sea legible y que alguien nuevo pueda sumarse sin pedir explicaciones. El flujo ya es conocido; la curva de entrada baja sola.

## Documentar bien

Un proyecto sin README claro es una herramienta sin instrucciones: puede ser excelente, pero nadie lo va a usar. En el ámbito académico, además, documentar bien es parte del aprendizaje: obliga a organizar ideas y justificar decisiones. Un trabajo comprensible para otros demuestra que uno mismo lo entendió.
