"# in-practica2-250677" 
# Int1-Practica02-250677
---

En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones de proyectos de desarrollo de software, aplicando princiíos de buenas prácticas den Documentación, Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador

Elaborado por: **Cristhian Azael Alvarado Escamilla**

Materia: **Proyecto Integrador**

Docente: **M.T.I Marco Antonio Ramírez Hernández**

Periodo: *Mayo - Agosto*

## Comandos Básicos para Maquetado de la Documentación titularizando el estandar de Markdown (.md)
---

Markdown es el estándar utilizado por Git y GitHub, para estilizar (maquetar) la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

###1.- Encabezados o Títulos (HEADERS)
**EJEMPLOS**

# Enabezado de nivel 1
## Enabezado de nivel 2
### Enabezado de nivel 3
#### Enabezado de nivel 4
##### Enabezado de nivel 5
###### Enabezado de nivel 6
####### Encabezado de nivel 7 - *El estandar solo permite 6 niveles para títulos , a partir del séptimo será presentado como texto plano (sin estilo)* 

### 2. Separadores (SEPARATORS)

Si se desea marcar una separación visual de los contenidos podemos utliizar una línea horizontal indicando tres caráctees - continuos, en el maquetado.

***EJEMPLO***

### Título de la sección
---
Texto después del separador

### 3.- Párrafos (PARRAGRAPHS)

Son utilizados para presentar grandes secciones de texto que describen detalladamente el contenido de las secciones de la documentación, detallan procesos, explican código o contexto teórico.

***Ejemplo***
Párrafo 1: Este texto es del párrafo 1 Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1.

Párrafo 2: Este texto es del párrafo 2 Este texto es del párrafo 2 Este texto es del párrafo 2 Este texto es del párrafo 2 Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2.Este texto es del párrafo 2.

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**, **centrado** o **justificado**, debemos utilizar una etiqueta ```<p>``` con la propiedad align y la dirección deseada.

<p align="left"> Parrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la 


<p align="right"> parrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la 


<p align ="center">parrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centrada

<p align = "justify"> parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado.

### 4. Enfatizado de Texto

- Texto en Negritas: Para resaltar texto importante que no sea un título por que esto inicialmente están en negrita, deberemos encerrar el texto deseado entre dobles asteríscos (**).

Ejemplo: Este texto esta en **negrita**.

- Texto en cursova (itálica): Para hacer referencia a tezto utilizando el formato inclinado o itálico bastara con encerrar el texto deseado entre dos asterisccos simples (*).

Ejemplo: Este *texto* estará *inclinando*.

- Texto en Cursiva y negrita: Para lograr esta estilización en la documentación basta juntar ambas configuraciones, es decir encerramos el texto en un triple asterísco (***).

Ejemplo ***Este texto esta Negrita e Itálico.***

- Texto tacahdo: En algunas ocaciones es necesario dar frormato al texto con un efecto de como es incorrectom generalmente esta idea se trasmite por que el texto esta tachado, es decir como una línea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tínde de (~).

Ejemplo: Se dice haya no ~haiga~.

- Texto subrayado: En este tipo de formato el texto queda sobre una línea inferior para denotar su relevancai, este formato no tiene una versión rápida en el estándar MARKDOWN, perodado su smilaridad a HMTL oidemos utilizar las etiquetas ``` <u> ``` y ``` <u> ```.

Ejemplo: El <u>texto</u> deve estar <u>subrayado</u>.
- Texto en Super Índice: En algunas ocaciones se requiere dar formato a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utlizar el tag de HTML ```<sup>``` y ```</sup>``` para delimitar, el formato.

Ejemplo: Para elevar x al cuadradotendriamos lo siguiente x <sup>2</sup>

- Texto en Subíndice: En el caso de química se utlizan subíndices para representar formulas, para ello podemos utlizar el formato de texto con la etiqueta HTML.

Ejemplo: La fórmula del Agua es H<sub>2</sub>O

### 5. Listas

Cuando realiamoz documentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementosm requisitos de hardware, requisitos de software o enumerar pasos de cómo el software debe ser instalado paso a paso, por eso debemos saber cómo crear listas de las cuales hay de 3 tipos: **Ordenadas (Números)**, **Desrodenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas Ordenadas 

Estas deberán enumeradas con un núnero seguido por un punto y un espacio en blanco para comenzar con el listado:

1. PC
2. Wifi
3. Modém
4. Smartphone
6. Smar TV
5. Tablet

2. Listas Desordenadas

Estas listas no llevan núnero, sino una viñeta (simbolo), y suele listar elementos que no requieren un orden especifico
 
- Pan
- Leche 
- Huevo
- Azucar

3. Listas Mixtas

Son aquellas que mezcla ambos elementos

- 3° A DSM
    1. Juan
    2. Pedro
    3. Alejandra
- 3° B DSM
    1. Romina
    2. Daniel
- 3° C DSM
    1. Yhair
    2. Liseth
    3. Jeovany
    4. Erick

### 6. Bloque de Códigos (CODE BLOCKS) o Citas (BLOCK QUOTES)

Estos estilos de texto se utilizan para llamar la atención  del lector, en pasos que son importantes, realizar alguna reseña o segmentar líneas de código  que se deberán ingresar en una terminal de comandos o líneas de ejecución.

- Cuadros de citas (BLOCK QUOTES)
Son cajas estilizadas en colores grises por defecto con un margén más claro.

Ejemplo:

> C:/dir

Después oprimimos la tecla *Enter*

También podemos usar texto multitarea 

**Ejemplo:**

Pasos para instalar MySQL

> - Descargar el archivo instalador desde la páfina oficiel www.mysql.com
> - Instalar el servidor de Bases de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializamos el servidor de bases de datos
> - Conectarnos a la base de datos para verificar que se instaló correctamente.

- bloques de código

Es común que en la documentacion del proyecto de software demos al usuraio un par de instrucciones de como instalar, configurarm desplegar y testear (pruebas), nuestro produceto desarrollado, por tal motico el estandar markdown nos permite enfatizar estas instrucciones, simulando estar en una terminal de sistema operativo para delimietar este codigo hasta encerrarlo en un triple caracteres de backtlick (acento o tílde inversa ) 

Ejemplo:

Para clonar el proyecto ingresa la siguiente isntruccion
``` 
C:\Users\PC-17\Desktop > git clone https://github.com/Werick-UTX/Int1-Practica02-250780.git

```
A diferencia de los bloques de citas, la tipografía y significado asociado cambian.

### 7. Tablas

En caso de que necesitemso estructurar datos o información relevante para la documentación podremos utilizar el formato de tablas, para lo que tenemos que considerar la estructura base de una tabla:

- Usa | para delimitar las columnas
- Usa --- para separar las filas del encabezado

Ejemplo:

|Título 1 |Título 2 |Título 3 |Título 4 |
|---|---|---|---|
|Fila 1, celda 1|Fila 1, celda 2|Fila 1, celda 3|Fila 1, celda 4|
|Fila 2, celda 1|Fila 2, celda 2|Fila 2, celda 3|Fila 2, celda 4|
|Fila 3, celda 1|Fila 3, celda 2|Fila 3, celda 3|Fila 3, celda 4|

### 8. Hipervinculos (Links)

Para poder hacer referencuas a documentos internos o externos dentro del repositorio, debemos respetar la siguiente estructura:

```
[Texto que el usuraio leera](url a dodne te dirigirá) "texto que aparecerpa cuando pongas el cursosr sobre la liga"
```
Ejemolo

-Ligas externas
[Google](https://google.com "Google papá")

-Ligas internas
[Acerca del Autor](./aboutme.md "Conoce más")
