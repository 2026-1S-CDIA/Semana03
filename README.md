# Semana 03 - Programación II

## Unidad 1: Programación Orientada a Objetos en Python

### Tema de la semana
**Herencia, polimorfismo y uso de `super()` en Python**

---

## Descripción

En esta semana se profundiza en los principios de la Programación Orientada a Objetos mediante el uso de:

- herencia,
- polimorfismo,
- reutilización de constructores con `super()`.

Como caso aplicado, se continúa trabajando con el archivo **`iris.csv`**, no desde el análisis de datos todavía, sino desde el **modelado orientado a objetos**. El objetivo es ampliar el sistema construido en semanas anteriores para representar de manera más estructurada las muestras del conjunto Iris.

---

## Objetivo de aprendizaje

Al finalizar la semana, el estudiante será capaz de:

- identificar relaciones de herencia entre clases,
- reutilizar atributos y métodos comunes mediante clases base y derivadas,
- aplicar polimorfismo en comportamientos compartidos,
- utilizar `super()` para simplificar y mejorar la reutilización del código.

---

## Relación con el sílabo

Esta semana corresponde a la **Unidad 1**, específicamente al tema:

- **1.2.1. Herencia y sintaxis de herencia**
- **1.2.2. Polimorfismo y funciones `super()`**

---

## Caso aplicado: `iris.csv`

Durante esta semana se propone ampliar el sistema orientado a objetos que representa las muestras del archivo `iris.csv`.

### Idea central
Cada fila del archivo representa una muestra de flor.  
A partir de esa representación, se buscará organizar el sistema con clases más generales y clases derivadas que permitan reutilizar estructura y comportamiento.

---

## Actividades de la semana

### 1. Revisión del modelo base
Se retomará el modelo desarrollado en semanas anteriores, en el que ya se cuenta con:

- una clase base para representar una muestra,
- atributos encapsulados,
- métodos básicos de acceso y visualización,
- una clase que agrupa o gestiona varias muestras.

### 2. Identificación de oportunidades de herencia
Se analizará el diseño actual para responder preguntas como:

- ¿qué elementos son comunes entre distintos tipos de muestras?
- ¿conviene definir una clase general?
- ¿qué clases podrían derivarse de una clase base?

### 3. Aplicación de herencia
Se ampliará el sistema creando clases relacionadas por herencia, con el fin de:

- reutilizar atributos comunes,
- evitar duplicación de código,
- organizar mejor las responsabilidades del sistema.

### 4. Aplicación de polimorfismo
Se trabajará con métodos que puedan comportarse de forma diferente según la clase del objeto, manteniendo una interfaz común.

### 5. Reutilización con `super()`
Se empleará `super()` para reutilizar constructores o comportamientos definidos en una clase padre.

---

## Producto esperado

Al finalizar la semana, el estudiante deberá contar con un avance funcional del proyecto que incluya:

- una jerarquía básica de clases,
- uso correcto de herencia,
- al menos un ejemplo de polimorfismo,
- reutilización de lógica mediante `super()`.

---

## Evidencias de aprendizaje

Se espera que el estudiante entregue o desarrolle:

- avance del proyecto de la Unidad 1,
- estructura de clases actualizada,
- prueba de funcionamiento de clases derivadas,
- explicación breve del diseño implementado.

---

## Recomendaciones

- Antes de crear una herencia, verificar que exista una relación lógica entre las clases.
- Evitar usar herencia solo para compartir código sin sentido conceptual.
- Priorizar claridad en el diseño.
- Mantener continuidad con el proyecto de `iris.csv`.

---

## Proyecto de la Unidad 1

**Sistema orientado a objetos para representar y gestionar muestras del archivo `iris.csv`**

La Semana 03 corresponde a la etapa de ampliación del proyecto mediante relaciones de herencia y polimorfismo, fortaleciendo la estructura orientada a objetos del sistema.

---

## Recursos sugeridos

- Diapositivas de la semana
- Notebook de sesión práctica
- Archivo `iris.csv`
- Material de apoyo sobre herencia y polimorfismo en Python

---

## Cierre

Esta semana es clave porque marca el paso desde un modelo básico de clases y objetos hacia una solución más potente y reutilizable. La herencia y el polimorfismo permiten que el sistema crezca de manera más ordenada, preparando la base para los siguientes contenidos de la unidad.
