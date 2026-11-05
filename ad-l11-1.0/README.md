# ad-l11
AD-20-1 Assessment-Individual

# 🧮 Calculator — JavaScript + Jest

## 🇪🇸 Español

Proyecto de práctica para desarrollar y probar funciones matemáticas en **JavaScript**, utilizando **Node.js, npm y Jest**. El objetivo fue aplicar pruebas unitarias y practicar un flujo básico de trabajo con **Git y GitHub**.

## 📋 Ejercicios realizados

El proyecto contiene las siguientes funciones:

1. **Promedio**
   - Calcula el promedio de un conjunto de números.
   - Ejemplo: `average([10, 8, 6])` → `8`

2. **Factorial**
   - Calcula el factorial de un número.
   - Ejemplo: `factorial(5)` → `120`
   - También se contempla el caso `0! = 1`.

3. **Suma de números naturales**
   - Calcula la suma de los primeros `n` números naturales.
   - Ejemplo: `sumNaturalNumbers(5)` → `15`

4. **Fórmula general / Chicharronera**
   - Resuelve ecuaciones cuadráticas de la forma:
     `ax² + bx + c = 0`
   - Ejemplo: `quadraticFormula(1, -5, 6)` → `[3, 2]`

## 🛠️ Tecnologías utilizadas

- JavaScript
- Node.js
- npm
- Jest
- Git
- GitHub

## 🧪 Pruebas con Jest

Se implementaron pruebas unitarias para verificar el funcionamiento de cada operación.

Para ejecutar las pruebas:

```bash
npm test
```

También puede utilizarse:

```bash
npx jest
```

Las pruebas verifican diferentes escenarios, incluyendo:

- Valores positivos y negativos.
- Promedios.
- Factoriales.
- Casos límite como `0!`.
- Suma de números naturales.
- Ecuaciones cuadráticas con soluciones reales.
- Ecuaciones con una solución repetida.

## 📁 Estructura del proyecto

```text
calculator-jest/
│
├── calculator.js
├── calculator.test.js
├── package.json
└── README.md
```

### `calculator.js`

Contiene las funciones matemáticas:

```js
add()
subtract()
divide()
multiply()
average()
factorial()
sumNaturalNumbers()
quadraticFormula()
```

### `calculator.test.js`

Contiene las pruebas unitarias realizadas con Jest.

## 🔄 Flujo de trabajo con Git

Durante el desarrollo se utilizaron commits independientes para identificar los cambios realizados en cada tarea.

Ejemplo:

```bash
git add calculator.js calculator.test.js
git commit -m "feat: add average calculator and tests"
git push
```

Se utilizaron commits relacionados con cada ejercicio para mantener un historial organizado del proyecto.

## 🎯 Objetivo de aprendizaje

Este proyecto permitió practicar:

- Creación de funciones en JavaScript.
- Uso de `module.exports` y `require`.
- Creación de pruebas unitarias con Jest.
- Uso de `expect()` y diferentes matchers como `toBe()` y `toEqual()`.
- Identificación de casos límite.
- Ejecución de pruebas mediante npm.
- Control de versiones con Git.
- Organización y publicación de un proyecto en GitHub.

---

# 🇺🇸 English

## 🧮 Calculator — JavaScript + Jest

Practice project focused on developing and testing mathematical functions using **JavaScript, Node.js, npm, and Jest**. The main goal was to practice unit testing and a basic development workflow with **Git and GitHub**.

## 📋 Exercises Completed

The project includes the following functions:

1. **Average**
   - Calculates the average of a set of numbers.
   - Example: `average([10, 8, 6])` → `8`

2. **Factorial**
   - Calculates the factorial of a number.
   - Example: `factorial(5)` → `120`
   - The `0! = 1` case is also covered.

3. **Sum of Natural Numbers**
   - Calculates the sum of the first `n` natural numbers.
   - Example: `sumNaturalNumbers(5)` → `15`

4. **Quadratic Formula**
   - Solves quadratic equations in the form:
     `ax² + bx + c = 0`
   - Example: `quadraticFormula(1, -5, 6)` → `[3, 2]`

## 🛠️ Technologies Used

- JavaScript
- Node.js
- npm
- Jest
- Git
- GitHub

## 🧪 Jest Tests

Unit tests were created to verify the behavior of each function.

To run the tests:

```bash
npm test
```

You can also run:

```bash
npx jest
```

The tests cover different scenarios, including:

- Positive and negative values.
- Average calculations.
- Factorials.
- Edge cases such as `0!`.
- Natural number sums.
- Quadratic equations with real solutions.
- Quadratic equations with repeated solutions.

## 📁 Project Structure

```text
calculator-jest/
│
├── calculator.js
├── calculator.test.js
├── package.json
└── README.md
```

### `calculator.js`

Contains the mathematical functions:

```js
add()
subtract()
divide()
multiply()
average()
factorial()
sumNaturalNumbers()
quadraticFormula()
```

### `calculator.test.js`

Contains the unit tests implemented with Jest.

## 🔄 Git Workflow

The project was developed using independent commits to keep track of the changes made for each task.

Example:

```bash
git add calculator.js calculator.test.js
git commit -m "feat: add average calculator and tests"
git push
```

Separate commits were used for each exercise to maintain an organized project history.

## 🎯 Learning Objectives

This project helped practice:

- Creating functions in JavaScript.
- Using `module.exports` and `require`.
- Writing unit tests with Jest.
- Using `expect()` and matchers such as `toBe()` and `toEqual()`.
- Identifying edge cases.
- Running tests with npm.
- Using Git for version control.
- Organizing and publishing a project on GitHub.

## 👨‍💻 Author

**Alexander Olivieri**

Java Full Stack Developer in training.