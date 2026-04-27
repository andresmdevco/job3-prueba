# 🐍 Funciones Básicas en Python + Tests

Este repositorio contiene una colección de funciones básicas en Python junto con pruebas unitarias utilizando el módulo `unittest`. Su propósito es practicar y demostrar conceptos fundamentales de programación y testing.

## ⚙️ Funcionalidades

El archivo `funciones.py` incluye las siguientes funciones:

- `saludar(nombre)`: Retorna un saludo personalizado.
- `sumar(*args)`: Suma una cantidad variable de números.
- `mayor_edad(edad)`: Determina si una persona es mayor de edad.
- `devolver_variable(var)`: Retorna la variable recibida.
- `devolver_none(var)`: Retorna `None` si la longitud del parámetro es mayor a 4, de lo contrario retorna `"Hola"`.
- `dividir(a, b)`: Realiza una división entre dos números.
- `convertir_numero(a)`: Convierte un valor a entero, lanzando un error si no es posible.

## ✅ Pruebas Unitarias

Se implementan múltiples pruebas unitarias usando `unittest`, cubriendo diferentes tipos de validaciones:

- `assertEqual` / `assertNotEqual`
- `assertTrue` / `assertFalse`
- `assertIs` / `assertIsNot`
- `assertIsNone` / `assertIsNotNone`
- `assertIn` / `assertNotIn`

Cada archivo `testX.py` valida una funcionalidad específica.

## ▶️ Cómo ejecutar las pruebas

Puedes ejecutar cada archivo de prueba individualmente:

```
python test1.py
```

O ejecutar todas las pruebas con:

```

python -m unittest discover
```
