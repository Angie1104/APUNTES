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
![Texto alternativo](https://cienciayt.com/wp-content/uploads/matematicas/transformadas-integrales/tabla-transformada-laplace-a.png)

## 6. Descomposición de Fraccciones parciales
Para la descomposición en fracciones parciales se deben factorizar las raíces del polinomio del numerador, se puede saber para que valores de s se eliminan algunos términos; lo cuál reduceel Sistema de 
ecuaciones que debe ser solucionado.

![Texto alternativo](https://www.disfrutalasmatematicas.com/algebra/images/partial-fractions-b.svg)

## 6.1 Caso 1: Raices reales diferentes
Si el denominador 𝑄(𝑥) de la fracción tiene factores lineales distintos, es decir, de la forma:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Q(x)=(x-a)(x-b)(x-c)"><img src="http://www.alciro.org/cgi/tex.cgi?Q(x)=(x-a)(x-b)(x-c)" title="Q(x)=(x-a)(x-b)(x-c)" border="0" /></a>

Entonces podemos escribir la fracción original como una suma de fracciones parciales, asignando una constante a cada factor lineal:
![Captura de pantalla 2025-03-07 181716](https://github.com/user-attachments/assets/05afe350-573e-4511-bbd3-dda56254ed97)

Ejemplo

![image](https://github.com/user-attachments/assets/98486825-e97e-4866-bf80-db4d53832105)

![image](https://github.com/user-attachments/assets/f0b8bcc1-2d00-4f33-b8b6-23f59fd77a55)

## 6.2 Raices Reales iguales:
Si el denominador tiene un factor lineal repetido, es decir, de la forma:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Q(x)=(x-a)^n"><img src="http://www.alciro.org/cgi/tex.cgi?Q(x)=(x-a)^n" title="Q(x)=(x-a)^n" border="0" /></a>

entonces la descomposición en fracciones parciales debe incluir términos con potencias crecientes del factor repetido:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P(x)}{(x-a)^n}=\frac{A{1}}{(x-a)}+\frac{A{2}}{(x-a)^2}+\frac{A{n}}{(x-a)^n}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{P(x)}{(x-a)^n}=\frac{A{1}}{(x-a)}+\frac{A{2}}{(x-a)^2}+\frac{A{n}}{(x-a)^n}" title="\frac{P(x)}{(x-a)^n}=\frac{A{1}}{(x-a)}+\frac{A{2}}{(x-a)^2}+\frac{A{n}}{(x-a)^n}" border="0" /></a>

Ejemplo:

![image](https://github.com/user-attachments/assets/33847143-584a-4fc7-8706-8414e5b35c4d)
![image](https://github.com/user-attachments/assets/94636c36-8cac-4cd5-8f39-9375e4d0f908)

## 6.3 Raices Reales conjugadas
Si la función de transferencia F(s) tiene raíces complejas conjugadas, es decir

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F(s) = (s - (a   jb))(s - (a - jb))"><img src="http://www.alciro.org/cgi/tex.cgi?F(s) = (s - (a   jb))(s - (a - jb))" title="F(s) = (s - (a   jb))(s - (a - jb))" border="0" /></a>

donde a y b son números reales y j es la unidad imaginaria, entonces la transformada inversa de Laplace es:
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=f(t) = 2e^{at} \times  (A \times  cos(bt)   B \times sin(bt))"><img src="http://www.alciro.org/cgi/tex.cgi?f(t) = 2e^{at} \times  (A \times  cos(bt)   B \times sin(bt))" title="f(t) = 2e^{at} \times  (A \times  cos(bt)   B \times sin(bt))" border="0" /></a>

## Fracciones parciales en Matlab
![image](https://github.com/user-attachments/assets/a886941d-b3d5-422d-ad7a-cffc4b52260f)
![image](https://github.com/user-attachments/assets/c4f2dbd7-f0ec-404d-896c-f747d4fcee7e)


## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
