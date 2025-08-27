## 📅 Semana 1 – Fundamentos de Python

**Objetivo:** Sintaxis básica, estructuras de datos, funciones y un vistazo a OOP.
**Mini-proyecto viernes:** Analizador de texto (word counter + frecuencia + longitud media).

---

### 📌 Lunes – “Wasaaaaap?” y tipos de datos

* **Conceptos:**

  * Sintaxis base de Python (`print`, comentarios `#`).
  * Tipos primitivos: `int`, `float`, `str`, `bool`.
  * Variables (naming conventions: `snake_case`).
* **Actividades:**

  * Escribe tu primer `hey_you.py`.
  * Haz operaciones aritméticas básicas.
  * Manipula strings: slicing, concatenación.
* **Vocabulario dev:**

  * *Script:* un archivo `.py` que corre en la terminal.
  * *Runtime:* el momento en que tu código se está ejecutando.
  * *Bug:* error en el código.

---

### 📌 Martes – Estructuras de datos

* **Conceptos:**

  * `list`, `tuple`, `dict`, `set`.
  * Operaciones comunes: `append`, `pop`, slicing en listas, acceso por `key` en diccionarios.
  * Introducción a iteración (`for`, `while`).
* **Actividades:**

  * Crea una lista de palabras y ordénala.
  * Construye un diccionario con datos ficticios (ej. `{'nombre': 'Tony', 'edad': 23}`).
  * Practica loops que recorren listas y diccionarios.
* **Vocabulario dev:**

  * *Data structure:* forma en la que guardas/organizas datos.
  * *Iterable:* cualquier objeto que se puede recorrer con un `for`.
  * *Index:* posición de un elemento en una lista.

---

### 📌 Miércoles – Funciones y modularidad

* **Conceptos:**

  * Definir funciones con `def`.
  * Parámetros y `return`.
  * Buenas prácticas: funciones cortas, responsabilidad única.
  * *Type hints*: `def sumar(a: int, b: int) -> int:`.
* **Actividades:**

  * Escribe funciones pequeñas: suma, resta, contar caracteres.
  * Divide tu código en varios archivos `.py` y usa `import`.
* **Vocabulario dev:**

  * *Module:* archivo Python que puede ser importado.
  * *Namespace:* espacio donde viven los nombres/variables.
  * *Refactor:* reescribir código para hacerlo más limpio.

---

### 📌 Jueves – Introducción a OOP (Programación Orientada a Objetos)

* **Conceptos:**

  * ¿Qué es una clase? ¿Qué es un objeto?
  * Atributos (`self.variable`) y métodos (`def metodo(self):`).
  * Instanciación (`obj = Clase()`).
* **Actividades:**

  * Define una clase `Persona` con atributos `nombre`, `edad`.
  * Agrega un método `presentarse()` que imprima un mensaje.
  * Practica creando varias instancias de tu clase.
* **Vocabulario dev:**

  * *Class:* plantilla para crear objetos.
  * *Instance:* objeto creado a partir de una clase.
  * *Method:* función definida dentro de una clase.

---

### 📌 Viernes – Proyecto mini: Analizador de texto

* **Objetivo:** Implementar un programa que:

  1. Reciba un texto (input o archivo `.txt`).
  2. Cuente número total de palabras.
  3. Calcule frecuencia de cada palabra.
  4. Obtenga la longitud media de las palabras.
* **Actividades:**

  * Diseña funciones: `tokenizar(texto) -> list[str]`, `contar_frecuencia(palabras: list[str]) -> dict[str, int]`.
  * Usa diccionarios para contar.
  * Opcional: crea una clase `AnalizadorTexto` para practicar OOP.
* **Vocabulario dev:**

  * *Algorithm:* conjunto de pasos para resolver un problema.
  * *Pipeline:* secuencia de pasos en un flujo de datos (aquí: leer texto → limpiar → contar → mostrar resultados).
  * *CLI (Command Line Interface):* ejecutar el programa desde terminal (`python analizador.py`).

---

