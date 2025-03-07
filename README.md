# TRANSFORMADAS DE LAPLACE
Las Transformadas de Laplace son una herramienta matemática utilizada para convertir ecuaciones diferenciales en ecuaciones algebraicas, lo que facilita su análisis y resolución. Se utilizan ampliamente en ingeniería, física y matemáticas aplicadas, especialmente en el análisis de sistemas dinámicos, circuitos eléctricos, mecánica y control automático.>## 1. DEFINICIONES
## 1. Definiciones
>**Sistema**
Conjunto de elementos que actuan para alcanzar un objetivo, se pueden relacionar por medio de reglas que relacionan salidas con entradas.

>**Planta**
Sistemas fisicos o procesos que se desean para controlar.

>**Proceso**
Es la secuencia de pasos que permite el desarrollo, o fabricación de un objetivo o producto. Pueden ser representados por ecuaciones diferenciables.

>**Sistema Dinamico**
>Se les conoce como sistemas dinamicos si su salida en el presente depende de una entrada en el pasado.
>![Texto alternativo](https://sites.icmc.usp.br/efcosta/modelo_motor.jpg)

>Si su salida en curso depende de su entrada en curso se conoce como estatico
>
>![Texto alternativo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ7IjGqmlcXbckB6SmwJ3RR63DymmO96KV_ehC28KeULOesoPFqGDGctQC5I6LpUM6R3AQ&usqp=CAU)


>**Modelos Dinamicos**
En control interesa obtener un modelos matematico que relacione las variables con el tiempo

**<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=f(x)"><img src="http://www.alciro.org/cgi/tex.cgi?f(x)" title="f(x)" border="0" /></a>**

Es necesario cuantificar cuanto cambia la variable en un tiempo.

**<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{df(t)}{dt}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{df(t)}{dt}" title="\frac{df(t)}{dt}" border="0" /></a>**

>**Modelos de Ecuaciones Diferenciables**
Son combinaciones lineas de derivadas de diferente orden.

 >**<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=a{1}*\frac{d^{2}f}{dt}+a{2}*\frac{df}{dt}+a{3}f=4f"><img src="http://www.alciro.org/cgi/tex.cgi?a{1}*\frac{d^{2}f}{dt}+a{2}*\frac{df}{dt}+a{3}f=4f" title="a{1}*\frac{d^{2}f}{dt}+a{2}*\frac{df}{dt}+a{3}f=4f" border="0" /></a>**

>**F** = Salida del sistema  
**U** = Entrada del sistema 

>**Sistemas lineales y no lineales**
Un Sistema se considera lineal cuando cumple con el principio de superposición

>•Un Sistema lineal Tambien tiene la característica de
proporcionalidad entre la entrada y la salida
>Los sistemas no lineales no cumplen con el principio de superposición

>**Modelamineto y Validación**
>Al incorporar leyes físicas en un modelo matemático de un sistema, es importante considerar que siempre existirá un cierto grado de incertidumbre en el resultado final.

>**Inluencia de Parametros**
>Comportamiento sinusuidal
>![Texto alternativo](https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/DampedCosine.svg/langes-1100px-DampedCosine.svg.png)
>
>Comportamiento Exponencial

>![Texto alternativo](https://math.libretexts.org/@api/deki/files/2815/CNX_Calc_Figure_06_08_002.jpeg)

## 2. Transformada de LaPlace
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(s)=\int_{0}^{\propto }x(t)*e^{-s*t}at"><img src="http://www.alciro.org/cgi/tex.cgi?x(s)=\int_{0}^{\propto }x(t)*e^{-s*t}at" title="x(s)=\int_{0}^{\propto }x(t)*e^{-s*t}at" border="0" /></a>
### 2.1. Transformada Inversa de LaPlace
Las transformadas inversas de Laplace permiten recuperar una función en el dominio del tiempo a partir de su representación en el dominio de la frecuencia

![Captura de pantalla 2025-03-07 172337](https://github.com/user-attachments/assets/85fb7ea0-9f1a-41be-8676-7337771c0b35)


## 3. Ejemplo Transformada de LaPlace
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(t)=e^{-3t}"><img src="http://www.alciro.org/cgi/tex.cgi?x(t)=e^{-3t}" title="x(t)=e^{-3t}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(s)=\int_{0}^{\propto}x(t)e^{-st}dt"><img src="http://www.alciro.org/cgi/tex.cgi?x(s)=\int_{0}^{\propto}x(t)e^{-st}dt" title="x(s)=\int_{0}^{\propto}x(t)e^{-st}dt" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(s)=\int_{0}^{\propto}e^{-3t}e^{-st}dt"><img src="http://www.alciro.org/cgi/tex.cgi?x(s)=\int_{0}^{\propto}e^{-3t}e^{-st}dt" title="x(s)=\int_{0}^{\propto}e^{-3t}e^{-st}dt" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\int_{0}^{\propto }e^{-(s+3)t}dt"><img src="http://www.alciro.org/cgi/tex.cgi?\int_{0}^{\propto }e^{-(s+3)t}dt" title="\int_{0}^{\propto }e^{-(s+3)t}dt" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\int e^{-at}dt=\frac{e^{-at}}{a}"><img src="http://www.alciro.org/cgi/tex.cgi?\int e^{-at}dt=\frac{e^{-at}}{a}" title="\int e^{-at}dt=\frac{e^{-at}}{a}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(s)=\frac{0-1}{-(s+3)}"><img src="http://www.alciro.org/cgi/tex.cgi?x(s)=\frac{0-1}{-(s+3)}" title="x(s)=\frac{0-1}{-(s+3)}" border="0" /></a>


![image](https://github.com/user-attachments/assets/c9545df6-dd8a-4ea2-90f1-2835e04fc49c)

## 4. Tabla de transformadas de LaPalce
![Texto alternativo](https://imgv2-2-f.scribdassets.com/img/document/382276862/original/69e1941825/1?v=1)

## 5. Tabla de Transformadas Inversas de LaPlace
![Texto alternativo](https://blogs.ugto.mx/rea/wp-content/uploads/sites/71/2022/01/Captura-de-Pantalla-2022-01-19-a-las-10.29.14.png)

## 6. Descomposición de Fraccciones parciales
![Texto alternativo](https://www.disfrutalasmatematicas.com/algebra/images/partial-fractions-b.svg)
Todas las figuras que incluya deben ser generadas por ustedes, **no utilizar las figuras de las presentaciones**. Para incluir figuras puede seguir los siguientes pasos:
* Primero escribimos ![]().
* Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.
* Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local). Se recomienda poner las imágenes en una carpeta que se llame imágenes dentro del repositorio github para que no tengan problemas al cargar las imágenes.

💡**Ejemplo 2:**

![Figura de prueba](images/plantilla/Captura2.PNG)

Figura 1. Figura de prueba

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

## 7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡**Ejemplo 3:** 

| **Resultado** | **x = número de intentos hasta primer éxito** |
|---------------|-----------------------------------------------|
|       S       |                       1                       |
|       FS      |                       2                       |
|      FFS      |                       3                       |
|      ...      |                      ...                      |
|    FFFFFFS    |                       7                       |
|      ...      |                      ...                      |

Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

## 8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡**Ejemplo 4:**
```
var sumar2 = function(numero) {
  return numero + 2;
}
```

## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## Rúbrica
| 0-1                                                                                   | 1-2                                                                                  | 2-3                                                                                                                                                                               | 3-4                                                                                                                                                                       | 4-5                                                                                                                                                                               |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Presenta menos del 10% de los temas o no presenta por  el medio y formato  solicitado | Presenta menos del 40% de los temas solicitados, y  cumple parcialmente la plantilla | Presenta menos del 60% de los temas solicitados (con descripciones, gráficos tablas, etc), y cumple  parcialmente la plantilla. No presenta la totalidad  de ejercicios resueltos | Presenta menos del 80% de los temas solicitados (con descripciones, gráficos, tablas, etc) y cumple con  la plantilla. No presenta  la totalidad de ejercicios  resueltos | Presenta el 100% de los temas vistos en clase (con descripciones, gráficos, tablas, etc), siguiendo totalmente la plantilla. presenta la  totalidad de los ejercicios solicitados |

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
