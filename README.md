# Lab: Introducción a los Condicionales en JavaScript

Este laboratorio está diseñado para ayudarte a practicar el uso de condicionales en JavaScript. A lo largo de estos tres ejercicios, vas a implementar decisiones lógicas que cambiarán el comportamiento del código en función de las condiciones que definas.

## Requisitos previos

Antes de comenzar este laboratorio, asegúrate de tener los siguientes conocimientos:

- Tipos de datos básicos en JavaScript (números, cadenas, booleanos)
- Cómo definir y utilizar variables
- Estructura básica de los condicionales (`if`, `else if`, `else`)

---

## Ejercicio 1: Verificar si un número es positivo, negativo o cero

En este ejercicio, escribirás una función que tome un número como entrada y determine si es positivo, negativo o cero.

### Instrucciones

1. Crea una función llamada `verificarNumero`.
2. Esta función debe tomar un parámetro llamado `numero` (un número).
3. Dentro de la función, utiliza condicionales para verificar si el número es:
   - Positivo: si el número es mayor que 0.
   - Negativo: si el número es menor que 0.
   - Cero: si el número es igual a 0.
4. Muestra un mensaje en la consola con el resultado, como por ejemplo:
   - "El número es positivo"
   - "El número es negativo"
   - "El número es cero"

### Pista

Recuerda que puedes usar `if`, `else if` y `else` para manejar los tres posibles casos.

### Ejemplo de salida

```javascript
verificarNumero(5); // Debería mostrar "El número es positivo"
verificarNumero(-3); // Debería mostrar "El número es negativo"
verificarNumero(0); // Debería mostrar "El número es cero"
```

---

## Ejercicio 2: ¿Es un mayor de edad?

En este ejercicio, escribirás una función que verifique si una persona es mayor de edad según su edad.

### Instrucciones

1. Crea una función llamada `esMayorDeEdad`.
2. La función debe tomar un parámetro llamado `edad` (un número).
3. Si la `edad` es 18 o mayor, muestra en la consola: "Eres mayor de edad".
4. Si la `edad` es menor de 18, muestra en la consola: "Eres menor de edad".

### Pista

Utiliza un condicional para verificar si la edad es mayor o igual a 18.

### Ejemplo de salida

```javascript
esMayorDeEdad(20); // Debería mostrar "Eres mayor de edad"
esMayorDeEdad(16); // Debería mostrar "Eres menor de edad"
```

---

## Ejercicio 3: Validar una contraseña

En este ejercicio, crearás una función que valide si una contraseña ingresada coincide con la contraseña correcta.

### Instrucciones

1. Crea una función llamada `validarContrasena`.
2. La función debe tomar un parámetro llamado `contrasena` (una cadena de texto).
3. Define dentro de la función una variable llamada `contrasenaCorrecta` y asígnale un valor, como por ejemplo `"123456"`.
4. Si `contrasena` es igual a `contrasenaCorrecta`, muestra en la consola: "Contraseña correcta".
5. Si `contrasena` no coincide con `contrasenaCorrecta`, muestra en la consola: "Contraseña incorrecta".

### Pista

Recuerda que para comparar cadenas de texto, puedes utilizar el operador `===`.

### Ejemplo de salida

```javascript
validarContrasena("123456"); // Debería mostrar "Contraseña correcta"
validarContrasena("abcdef"); // Debería mostrar "Contraseña incorrecta"
```

---

## Notas adicionales

- Asegúrate de probar cada función varias veces con diferentes valores de entrada.
- Si algo no funciona como esperabas, revisa la sintaxis de tus condicionales y verifica que estés comparando los valores correctamente.
- Usa `console.log()` para ver los resultados de tus pruebas.

¡Buena suerte y diviértete programando!
