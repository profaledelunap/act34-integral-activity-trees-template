![Tec de Monterrey](images/logotecmty.png)

# Act 3.4 - Actividad Integral de Árboles (Evidencia Competencia)

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>

En este repositorio encontrarás los archivos de entrada, así como las salidas esperadas que podrás usar para probar tu implementación. También encontrarás un archivo "main.cpp". Ahí deberás implementar tu solución. En el archivo deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:

```
// =========================================================
// File: main.cpp
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```

<span style="text-decoration: underline;">De manera individual</span>, desarrolla la solución del siguiente problema:

El canal de Suez es un canal navegable que conecta el mar Mediterráneo con el mar Rojo a través de alrededor de 190 km, uniendo por un el lado del mar Mediterráneo desde el puerto Said hasta el golfo de Suez en el mar Rojo. Este canal es navegado entre 49 y 97 barcos diariamente. Se tiene un registro de los barcos que navegan por el canal con el siguiente formato.

```
<fecha> <hora> <punto-entrada> <UBI-Identificador único del buque>
```

Ejemplo:

```
03-01-20 13:45 M 8PAK7
```

Donde:

- El punto de entrada puede ser **M – Mar Mediterráneo** y **R – Mar Rojo**.
- La fecha estará entre **01-01-2020** y **31-12-2020**.
- El tiempo estará en formato de 24 Hrs.

En equipo, deberán hacer una aplicación que:

- Lea un archivo de entrada (ej. canal.txt), en el cual el primer renglon consiste del numero de registros a leer. Después, se leen y contabilizan el número de incidencias de cada una de las series (los primeros tres caracteres del UBI). Las series y el número de incidencias se deberan guardar en dos árboles binarios de búsqueda, uno para las series de buques que entraron por el mar Mediterráneo y otro para las series que entraron por el mar Rojo.
- Despliegue los datos almacenados en cada uno de los árboles en forma descendente, donde la prioridad esta dada por el número de incidencias de cada prefix (a mayor incidencias mayor proridad). El resultado se deberá de desplegar en el siguiente formato:

```
Mar Rojo
<prefix> <cantidad>
.
.
.
Mar Mediterráneo
<prefix> <cantidad>
```

Para probar tu implementación, compila tu programa con el comando:

```
make
```

Si quieres probar únicamente un test en particular, ejecuta el comando respectivo:

```
make testX
```

donde X representa el cnumero correspondiente a uno de los 4 tests.

Recuerda actualizar tu repositorio (_git push_) a lo largo del desarrollo de la actividad.

Por último, realiza una investigación y reflexión de la importancia y eficiencia del uso de BST en una situación problema de esta naturaleza, generando un documento llamado **"ReflexAct34_A0XXXXX.pdf"**

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **80%** - Para cada una de las funcionalidades se evaluará:

  - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
  - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
  - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
  - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se respetenan los nombres de las funciones en la aplicación.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>

Esta actividad forma parte tanto de tu calificación final del curso, así como del portafolio de evidencias de las competencias a desarrollar del curso, por lo que se te pide que en forma individual:

- Realices una entrega del código fuente de la solución del problema, en la sección correspondiente dentro de esta plataforma, así como el documento de reflexión individual (**ReflexAct3.4.pdf**).
  En la carpeta personal llamada **TC1031(Portafolio_Final)** que generaste desde la entrega de la actividad 1.3 y que te servirá como preparación para la entrega del portafolio de competencias que se realizará al final del curso, coloca en la subcarpeta **Act3.4** tus archivos que solucionaron la <span style="text-decoration: underline;">actividad 3.4</span> así como el documento de reflexión individual (**ReflexAct3.4.pdf**) .
