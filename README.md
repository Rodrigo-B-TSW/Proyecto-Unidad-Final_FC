# Glosario: 40 Conceptos de Fundamentos 
 
| | |
|---|---|
| **Autor** | Rodrigo Barrera García (1B) |
| **Profesor** | Ubaldo Narvaez Montoya |
| **Institución** | Tecnológico de Software |
| **Ubicación** | Mérida, Yucatán. México |
| **Fecha** | 28/09/2026 |
 
---
 
## Fundamentos de Computación
 
---
 
### 1. Algoritmo
 
> **Definición:** Es un conjunto ordenado y finito de operaciones que permite hallar la solución de un problema.
 
**🔥 Ejemplo:** Seguir los pasos de una receta de cocina. 🔥
 
---
 
### 2. Programa
 
> **Definición:** Conjunto de instrucciones diseñadas para que una computadora realice tareas específicas.
 
**🔥 Ejemplo:** Implementar y escribir código usando Java, Python, Php, etc. 🔥
 
---
 
### 3. Código fuente
 
> **Definición:** Son líneas de texto expresadas en un lenguaje de programación para verificar la ejecución de un programa.
 
**🔥 Ejemplo:** Es el etapa de full programación, donde construyes tu código y tu programa. 🔥
 
---
 
### 4. Lenguaje de programación
 
> **Definición:** Es la construcción formal y profesional de programas informáticos para crear, diseñar y resolver problemas actuales.
 
**🔥 Ejemplo:** Java, es un lenguaje de propósito general y orientado a objetos muy completo. 🔥
 
---
 
### 5. Sintaxis
 
> **Definición:** Conjunto de reglas gramaticales que definen correctamente la secuencia de los elementos en un lenguaje de programación.
 
**🔥 Ejemplo:** En Python, cuando vamos a imprimir, sería un error de sintaxis si escribimos `println(Hola mundo)` en lugar de `println('Hola mundo')`. 🔥
 
---
 
### 6. Variable
 
> **Definición:** Es una porción de memoria que almacena un valor que puede cambiar (números, cadenas, objetos, colecciones…).
 
**🔥 Ejemplo:** Puedo declarar en mis variables `edad = 19`, `nombre = Rodrigo`, `Apellido = Barrera`. 🔥
 
---
 
### 7. Constante
 
> **Definición:** Es un espacio en la memoria cuyo valor se asigna una sola vez y no puede cambiar durante toda la ejecución del programa (el opuesto a la variable).
 
**🔥 Ejemplo:** El valor de PI = 3.1416, porque es una verdad matemática. 🔥
 
---
 
### 8. Tipo de dato
 
> **Definición:** Clasifica el tipo de dato que una variable, constante u objeto puede tener contenido.
 
**🔥 Ejemplo:** Existen los enteros (1), flotantes (1.2), caracteres (a), cadenas ("hola"), entre otros. 🔥
 
---
 
### 9. Operador
 
> **Definición:** Símbolo o palabra que representa una operación a realizar entre uno o más operandos.
 
**🔥 Ejemplo:** Si queremos sumar datos, restar, comparar, asignar, incrementar, etc. 🔥
 
---
 
### 10. Expresión
 
> **Definición:** Combinación de literales, variables, operadores y funciones que genera un valor al evaluarse.
 
**🔥 Ejemplo:** Por ejemplo, `5 + 3` genera `8`, o decir `"Hola " + "Juan"` = `"Hola Juan"`. Estas dos son expresiones. 🔥
 
---
 
### 11. Condicional
 
> **Definición:** Permite ejecutar diferentes instrucciones dependiendo de si una condición lógica es verdadera o falsa.
 
**🔥 Ejemplo:** Una condición básica usa `if/else` para evaluar una condición: 🔥
 
```python
if (condición) {
    // Código si es verdadero
} else {
    // Código si es falso
}
```
 
---
 
### 12. Bucle
 
> **Definición:** Construcción de programación que permite repetir un conjunto de instrucciones varias veces hasta que se cumpla una condición.
 
**🔥 Ejemplo:** En Python para contar del 1 al 4 usamos: 🔥
 
```python
for i in range(1, 4):
    print(f"Número {i}")
``` 
 
---
 
### 13. Función
 
> **Definición:** Bloques de código reutilizables que realizan tareas específicas en tus programas. Puede procesar datos y devolver un resultado.
 
**🔥 Ejemplo:** 🔥
 
```python
def saludar(nombre):
    return f"¡Hola, {nombre}!"
 
# Llama a la función
mensaje = saludar("Miguel")
print(mensaje)
```
 
---
 
### 14. Parámetro
 
> **Definición:** Variable que se utiliza en la definición de una función o método para recibir valores de entrada cuando se llama a la función.
 
**🔥 Ejemplo:** Aquí, el parámetro es "nombre" porque estamos indicando nuestra variable contenedora que va a recibir y guardar ese dato: 🔥
 
```python
def saludar(nombre):
    return f"¡Hola, {nombre}!"
```
 
---
 
### 15. Argumento
 
> **Definición:** Es el valor real que le envías a la casilla cuando ejecutas la función.
 
**🔥 Ejemplo:** Volviendo al ejemplo del inciso 13: 🔥
 
```python
saludar("Miguel")  # "Miguel" es el argumento real
```
 
---
 
### 16. Retorno
 
> **Definición:** Resultado o valor que una función o método entrega al código que la mandó llamar.
 
**🔥 Ejemplo:** Aquí un ejemplo de return en Java: 🔥
 
```java
// Definición de la función
int Suma(int a, int b) {
    return a + b;
}
// Uso de la función Suma
int resultado = Suma(3, 5);
```
 
---
 
### 17. Arreglo
 
> **Definición:** Estructura de datos que almacena un conjunto de elementos del mismo tipo en ubicaciones contiguas de memoria.
 
**🔥 Ejemplo:** `int edades[5] = {18, 25, 30, 22, 27};` 🔥
 
---
 
### 18. Objeto
 
> **Definición:** Representan cosas del mundo real, así como conceptos abstractos con sus características y comportamientos específicos.
 
**🔥 Ejemplo:** Las propiedades de un libro, cuenta bancaria, persona… 🔥
 
---
 
### 19. Método
 
> **Definición:** Procedimiento programado que se define como parte de una clase y está disponible para cualquier objeto instanciado de esa clase.
 
**🔥 Ejemplo:** 🔥
 
```python
def __init__(self, nombre):
    self.nombre = nombre
 
# Método
def saludar(self):
    print(f"Hola, soy {self.nombre}")
```
 
---
 
### 20. Evento
 
> **Definición:** Suceso o acción que ocurre en el sistema y al cual el programa puede reaccionar.
 
**🔥 Ejemplo:** Un clic del usuario en un botón, teclear una letra en un formulario, deslizar la pantalla en una app móvil, etc. 🔥
 
---
 
### 21. Compilador
 
> **Definición:** Es el programa que toma todo el código fuente escrito por el usuario y lo traduce por completo a lenguaje máquina.
 
**🔥 Ejemplo:** Cuando escribes un programa en Python y usas un compilador para transformarlo en un archivo .exe. 🔥
 
---
 
### 22. Intérprete
 
> **Definición:** Es el programa que lee, traduce y ejecuta el código fuente instrucción por instrucción en tiempo real.
 
**🔥 Ejemplo:** Al ejecutar un programa en Python, la computadora lee la línea 1 y la procesa, luego la línea 2, y si encuentra un error en la línea 5, se detiene exactamente ahí. 🔥
 
---
 
### 23. Depurador (Debugger)
 
> **Definición:** Es la herramienta que permite pausar la ejecución de un programa e inspeccionarlo paso a paso para localizar y corregir errores (o bugs) en el código.
 
**🔥 Ejemplo:** Ejecutar un algoritmo paso a paso para inspeccionar en tiempo real cómo cambia el valor de una variable en cada iteración y detectar por qué el programa se queda congelado. 🔥
 
---
 
### 24. IDE
 
> **Definición:** Es la aplicación de software completa que agrupa en una sola interfaz las herramientas básicas para programar.
 
**🔥 Ejemplo:** Utilizar Apache NetBeans o Eclipse para programar en Java. 🔥
 
---
 
### 25. Editor de código
 
> **Definición:** Es el programa ligero enfocado principalmente en escribir y editar texto con código fuente.
 
**🔥 Ejemplo:** Abrir Visual Studio Code o Sublime Text para escribir un archivo HTML. 🔥
 
---
 
### 26. Biblioteca (Library)
 
> **Definición:** Colección de código y funciones predefinidas que un desarrollador puede importar y utilizar en su proyecto para realizar tareas específicas sin tener que escribirlas desde cero.
 
**🔥 Ejemplo:** Importar la biblioteca "Math" en tu programa para usar la función `Math.sqrt()` y calcular una raíz cuadrada en lugar de programar la fórmula matemática de forma manual. 🔥
 
---
 
### 27. Framework
 
> **Definición:** Es la estructura de trabajo que proporciona una base organizativa, reglas y herramientas sobre las cuales se construye una aplicación.
 
**🔥 Ejemplo:** Utilizar Angular para construir una aplicación web en TypeScript. 🔥
 
---
 
### 28. API
 
> **Definición:** Es el conjunto de reglas y protocolos que permite a dos programas o sistemas informáticos intercambiar información entre sí.
 
**🔥 Ejemplo:** Una aplicación de clima en el celular que le solicita los datos meteorológicos actualizados al servidor de Google para mostrarlos en tu pantalla. 🔥
 
---
 
### 29. Repositorio
 
> **Definición:** Es el espacio digital de almacenamiento donde se guardan el código fuente, los archivos y todo el historial de cambios de un proyecto informático.
 
**🔥 Ejemplo:** Una carpeta rastreada en tu computadora que contiene todas las versiones del código de tu proyecto final escolar. 🔥

---
 
### 30. Control de versiones
 
> **Definición:** Es el sistema que registra los cambios realizados en los archivos de un proyecto para poder revisar historiales, recuperar versiones anteriores y colaborar en equipo.
 
**🔥 Ejemplo:** Restaurar mi código al estado en el que estaba ayer porque la actualización que escribiste hoy arruinó el programa. 🔥
 
---
 
### 31. Git
 
> **Definición:** Sistema de control de versiones gratuito que rastrea las modificaciones en el código fuente durante el proceso de desarrollo de software.
 
**🔥 Ejemplo:** Escribir comandos en la terminal de tu equipo como `git status` o `git add` para guardar el progreso de mis archivos. 🔥
 
---
 
### 32. Github
 
> **Definición:** Es la plataforma web en la nube que permite almacenar repositorios de Git, facilitar el trabajo colaborativo entre desarrolladores y gestionar proyectos de software.
 
**🔥 Ejemplo:** Subir el repositorio de mi tarea a "github.com" para que tus compañeros puedan descargarlo y aportar cambios. 🔥
 
---
 
### 33. Rama (Branch)
 
> **Definición:** Es la línea de trabajo independiente dentro de un repositorio que permite desarrollar o probar nuevas funcionalidades sin alterar la versión principal del proyecto.
 
**🔥 Ejemplo:** Crear una rama llamada para diseñar una nueva función visual sin arriesgar el main. 🔥
 
---
 
### 34. Commit
 
> **Definición:** Guardado de los archivos en Git que incluye un mensaje descriptivo para registrar un avance específico en el proyecto.
 
**🔥 Ejemplo:** Guardar cambios realizados mediante el comando `git commit -m "Se creó el proyecto"`. 🔥
 
---
 
### 35. Merge
 
> **Definición:** Operación en sistemas de control de versiones que fusiona e integra las modificaciones hechas en una rama con los cambios de otra rama.
 
**🔥 Ejemplo:** Unir una rama con la rama principal main una vez que la nueva función fue probada y no tiene errores. 🔥
 
---
 
### 36. Callback
 
> **Definición:** Es la función que se pasa como argumento dentro de otra función para ser ejecutada después cuando ocurra un evento o finalice una tarea.
 
**🔥 Ejemplo:** Programar que cuando el usuario haga clic en un botón de la página, el navegador ejecute una función que muestre un mensaje de bienvenida. 🔥
 
---
 
### 37. Programación sincrónica
 
> **Definición:** Es el modelo de ejecución en el que las instrucciones se procesan en orden secuencial una por una, obligando a esperar a que termine cada tarea antes de continuar.
 
**🔥 Ejemplo:** Hacer una fila en la caja de un banco. La cajera atiende a una persona a la vez y la siguiente debe esperar obligatoriamente a que finalice el turno previo. 🔥
 
---
 
### 38. Programación asincrónica
 
> **Definición:** Es un estilo de programación de ejecución que permite iniciar tareas de larga duración sin detener ni bloquear el flujo del programa.
 
**🔥 Ejemplo:** Pedir comida en un restaurante de comida rápida. Te dan un ticket con tu número y atienden a otros clientes mientras la cocina prepara tu pedido sin detener la atención. 🔥
 
---
 
### 39. JavaScript
 
> **Definición:** Es un lenguaje de programación interpretado de alto nivel que se utiliza para crear páginas web interactivas y dinámicas.
 
**🔥 Ejemplo:** Programar un botón para que, al presionar una imagen en una página web, se abra una galería de fotos. 🔥
 
---
 
### 40. TypeScript
 
> **Definición:** Es un lenguaje de programación basado en JavaScript, añadiendo tipado de datos explícito para reducir errores en aplicaciones.
 
**🔥 Ejemplo:** Programar la lógica necesaria para que, al presionar una imagen en una página web, se abra una galería desplegable. 🔥
 
---
 
# Referencias (fuentes)

En esta parte adjunté todos y cada uno de los links de distintas fuentes donde saqué las definiciones, está hecho de esta manera ya que yo no hice mis referencias en APA en mis tareas 2 y 4, sino que en cada concepto, en la parte de abajo, están los links de consulta.
 
1. Algoritmo: <https://dle.rae.es/algoritmo?m=form>
2. Programa: <https://desarrollarinclusion.cilsa.org/tecnologia-inclusiva/que-es-un-programa/>
3. Código fuente: <https://concepto.de/codigo-fuente/>
4. Lenguaje de programación: <https://concepto.de/lenguaje-de-programacion/#google_vignette>
5. Sintaxis: <https://dle.rae.es/sintaxis>
6. Variable: <https://www.domestika.org/es/blog/12614-que-es-una-variable-en-programacion>
7. Constante: <https://es.wikipedia.org/wiki/Constante_(inform%C3%A1tica)>
8. Tipo de dato: <https://www.datdata.com/blog/tipos-de-datos>
9. Operador: <http://adrformacion.com/knowledge/programacion/_que_es_un_operador_en_programacion_.html>
10. Expresión: <https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/Nivel2/5_Expresiones.html>
11. Condicional: <https://www.luisllamas.es/programacion-condicionales/>
12. Bucle: <https://iddigitalschool.com/bootcamps/que-es-un-bucle-en-programacion/>
13. Función: <https://newsletter.cuarzo.dev/p/que-es-una-funcion-en-programacion>
14. Parámetro: <https://mimo.org/glossary/programming-concepts/parameter>
15. Argumento: <https://www.idtech.com/blog/what-is-an-argument-in-programming>
16. Retorno: <https://www.luisllamas.es/programacion-retorno-funciones/>
17. Arreglo: <https://onmex.mx/tecnologia-y-desarrollo/que-son-los-arreglos-en-programacion/>
18. Objeto: <https://ebac.mx/blog/objeto-en-programacion>
19. Método: <https://www.techtarget.com/whatis/definition/method>
20. Evento: <https://profile.es/blog/programacion-orientada-a-eventos/>
21. Compilador: <https://immune.institute/blog/que-es-un-compilador/>
22. Intérprete: <https://codica.la/guias/interpreter>
23. Depurador (Debugger): <https://www.ibm.com/es-es/topics/interpreter>
24. IDE: <https://goo.su/PUskEws>
25. Editor de código: <https://iddigitalschool.com/bootcamps/que-es-un-editor-de-codigo/>
26. Biblioteca (Library): <https://goo.su/lwFgnk>
27. Framework: <https://goo.su/TOTjhO>
28. API: <https://goo.su/7srDM>
29. Repositorio: <https://www.datacamp.com/es/blog/what-is-a-repository>
30. Control de versiones: <https://unity.com/es/glossary/version-control>
31. Git: <https://www.theforage.com/blog/skills/what-is-git>
32. Github: <https://docs.github.com/es/get-started/start-your-journey/what-is-github>
33. Rama (Branch): <https://msmk.university/branch-en-programacion/>
34. Commit: <https://es.wikipedia.org/wiki/Commit>
35. Merge: <https://www.collinsdictionary.com/es/diccionario/ingles/merge>
36. Callback: <https://msmk.university/que-es-un-callback/>
37. Programación sincrónica: <https://clickup.com/es-ES/blog/236044/programacion-sincrona-frente-a-programacion-asincrona>
38. Programación asincrónica: <https://clickup.com/es-ES/blog/236044/programacion-sincrona-frente-a-programacion-asincrona>
39. JavaScript: <https://ebac.mx/blog/que-es-javascript>
40. TypeScript: <https://www.typescriptlang.org/>
 




