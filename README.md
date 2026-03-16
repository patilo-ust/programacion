# 🚀 Fundamentos de Programación con Python

Este repositorio contiene una guía rápida y práctica sobre los pilares fundamentales de la programación, desde la lógica visual hasta las estructuras de datos avanzadas.

## 1. Lógica y Diseño
### 📊 Diagramas de Flujo
Antes del código, diseñamos la lógica. Los símbolos principales son:
* **Óvalo:** Inicio / Fin.
* **Paralelogramo:** Entrada / Salida de datos (`input` / `print`).
* **Rectángulo:** Procesos y cálculos.
* **Rombo:** Toma de decisiones (`if`).

## 2. Elementos Básicos
### 📦 Variables y Tipos de Datos (Primitivos)
Las variables son contenedores con nombre.
* `int`: Enteros (ej. `10`)
* `float`: Decimales (ej. `9.99`)
* `str`: Texto (ej. `"Hola"`)
* `bool`: Lógicos (`True` / `False`)

### 🗣️ Comunicación (I/O)
* `input()`: Recibe datos del usuario (siempre como texto).
* `print()`: Muestra datos en consola. Usa `f-strings` para mezclar variables: `print(f"Hola {nombre}")`.

### 🔠 Manipulación de Texto
* `.lower()`: Todo a minúsculas.
* `.upper()`: Todo a MAYÚSCULAS.

## 3. Estructuras de Control
### 🛣️ Decisiones (if-else / match-case)

# if-elif-else
if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")

# match-case (El 'switch' de Python)
match dia:
    case "Lunes": print("Inicio de semana")
    case "Viernes": print("Casi fin de semana")
    case _: print("Otro día")
