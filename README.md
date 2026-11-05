# AD-20-1 – End of Module Assessment

## 🇲🇽 Español

### Descripción del proyecto

Proyecto de JavaScript desarrollado como parte de la evaluación del módulo de Desarrollo de Aplicaciones. Incluye funciones matemáticas, administración de usuarios y pruebas unitarias utilizando **Jest**.
function divide(a, b) {
### Funcionalidades

#### 1. Calculadora (`Calculator`)

Implementación de operaciones y funciones matemáticas:

- Suma y resta.
- Multiplicación y división.
- Cálculo de promedio.
- Cálculo de factorial.
- Suma de los primeros números naturales.
- Fórmula general para resolver ecuaciones cuadráticas.
- Validación de división entre cero mediante el lanzamiento de un error.

#### 2. Administración de usuarios (`UserController`)

Permite gestionar usuarios mediante las siguientes operaciones:

- `add()`: agrega un usuario.
- `remove()`: elimina un usuario.
- `getUsers()`: obtiene la lista de usuarios.
- `findByEmail()`: busca un usuario por correo electrónico.
- `findById()`: busca un usuario por identificador.

La clase `User` permite crear usuarios con ID, nombre y correo electrónico.

### Pruebas unitarias

Se utilizó **Jest** para verificar el funcionamiento de las operaciones matemáticas y los métodos de administración de usuarios.

Las pruebas contemplan:

- Operaciones de la calculadora.
- Multiplicación y división.
test('divide 10 / 2 to equal 5', () => {
- Agregar y eliminar usuarios.
- Búsqueda de usuarios por correo electrónico e ID.
- Casos donde no se encuentra un usuario.

### Desarrollo Basado en Pruebas (TDD)

Se aplicó el ciclo TDD para controlar la división entre cero:

1. **RED:** se creó una prueba que esperaba un error al dividir entre cero.
2. **GREEN:** se modificó `divide()` para lanzar un error descriptivo cuando el divisor es cero.
3. **REFACTOR:** se mantuvo la implementación sencilla y legible.

### Tecnologías utilizadas

- JavaScript
- Node.js
- Jest
- Git
- GitHub

### Instalación y ejecución

Clona el repositorio:

```bash
git clone https://github.com/AlexanderOlivieri/AD-20-1-EvaluacionFinalAlex.git
```

Instala las dependencias:

```bash
npm install --save-dev jest
```

Ejecuta las pruebas:

```bash
npm test
```

---

## 🇺🇸 English

### Project Description

JavaScript project developed as part of the Application Development module assessment. It includes mathematical functions, user management, and unit testing using **Jest**.

### Features

#### 1. Calculator

Implementation of mathematical operations and functions:

- Addition and subtraction.
- Multiplication and division.
- Average calculation.
- Factorial calculation.
- Sum of the first natural numbers.
- Quadratic formula.
- Division-by-zero validation using error handling.

#### 2. User Management (`UserController`)

Provides basic user management operations:

- `add()`: adds a user.
- `remove()`: removes a user.
- `getUsers()`: retrieves the user list.
- `findByEmail()`: searches for a user by email.
- `findById()`: searches for a user by ID.

The `User` class creates users with an ID, name, and email address.

### Unit Testing

**Jest** was used to verify mathematical operations and user management methods.

The tests cover:

- Calculator operations.
- Multiplication and division.
- Division-by-zero handling.
- Adding and removing users.
- Searching users by email and ID.
- Cases where a user cannot be found.

### Test-Driven Development (TDD)

The TDD cycle was applied to handle division by zero:

1. **RED:** created a test expecting an error when dividing by zero.
2. **GREEN:** updated `divide()` to throw a descriptive error when the divisor is zero.
3. **REFACTOR:** kept the implementation simple and readable.

### Technologies

- JavaScript
- Node.js
- Jest
- Git
- GitHub

### Installation and Execution

Clone the repository:

```bash
git clone https://github.com/AlexanderOlivieri/AD-20-1-EvaluacionFinalAlex.git
```

Install dependencies:

```bash
npm install --save-dev jest
```

Run the tests:

```bash
npm install --save-dev jest
```


