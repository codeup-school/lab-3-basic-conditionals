# Lab: Introducción a los Condicionales en JavaScript

Este laboratorio te ayudará a practicar el uso de condicionales en JavaScript. A lo largo de estos ejercicios, escribirás código que toma decisiones lógicas en función de condiciones específicas.

## Requisitos previos

Antes de comenzar este laboratorio, asegúrate de tener los siguientes conocimientos:

- Tipos de datos básicos en JavaScript (números, cadenas, booleanos)
- Cómo definir y utilizar variables
- Estructura básica de los condicionales (`if`, `else if`, `else`)

---

## Ejercicio 1: Verificar si un número es positivo, negativo o cero

En este ejercicio, escribirás código que determine si un número es positivo, negativo o cero.

### Instrucciones

1. Declara una variable llamada `numero` y asígnale un valor numérico, por ejemplo:
   ```javascript
   let numero = 5;
   ```
2. Usa una estructura condicional para verificar si el número es:
   - Positivo (mayor que 0).
   - Negativo (menor que 0).
   - Cero (igual a 0).
3. Muestra un mensaje en la consola con el resultado, como:
   - "El número es positivo"
   - "El número es negativo"
   - "El número es cero"

### Ejemplo de código

```javascript
let numero = 5;

if (numero > 0) {
  console.log("El número es positivo");
} else if (numero < 0) {
  console.log("El número es negativo");
} else {
  console.log("El número es cero");
}
```

### Ejemplo de salida

```
El número es positivo
```

---

## Ejercicio 2: ¿Es un mayor de edad?

En este ejercicio, escribirás código que verifique si una persona es mayor de edad según su edad.

### Instrucciones

1. Declara una variable llamada `edad` y asígnale un valor numérico, por ejemplo:
   ```javascript
   let edad = 20;
   ```
2. Si la `edad` es 18 o mayor, muestra en la consola: "Eres mayor de edad".
3. Si la `edad` es menor de 18, muestra en la consola: "Eres menor de edad".

### Ejemplo de código

```javascript
let edad = 20;

if (edad >= 18) {
  console.log("Eres mayor de edad");
} else {
  console.log("Eres menor de edad");
}
```

### Ejemplo de salida

```
Eres mayor de edad
```

---

## Ejercicio 3: Validar una contraseña

En este ejercicio, escribirás código que valide si una contraseña ingresada coincide con la contraseña correcta.

### Instrucciones

1. Declara una variable llamada `contrasena` y asígnale una cadena de texto, como por ejemplo:
   ```javascript
   let contrasena = "123456";
   ```
2. Declara otra variable llamada `contrasenaCorrecta` y asígnale un valor, como `"123456"`.
3. Si `contrasena` es igual a `contrasenaCorrecta`, muestra en la consola: "Contraseña correcta".
4. Si `contrasena` no coincide con `contrasenaCorrecta`, muestra en la consola: "Contraseña incorrecta".

### Ejemplo de código

```javascript
let contrasena = "123456";
let contrasenaCorrecta = "123456";

if (contrasena === contrasenaCorrecta) {
  console.log("Contraseña correcta");
} else {
  console.log("Contraseña incorrecta");
}
```

### Ejemplo de salida

```
Contraseña correcta
```

---

## Notas adicionales

- Asegúrate de probar cada ejercicio con diferentes valores para verificar que tu código funcione correctamente.
- Si algo no funciona como esperabas, revisa la lógica de tus condicionales y cómo estás comparando los valores.
- Usa `console.log()` para ver los resultados de tus pruebas y depurar tu código si es necesario.

¡Buena suerte y disfruta programando con condicionales!
