# 📱 Catálogo Interactivo de Celulares en Python

Un proyecto de consola desarrollado en Python que aplica conceptos fundamentales de Programación Orientada a Objetos (POO) para simular un sistema de consulta de especificaciones de teléfonos móviles.

## 🚀 Descripción del Proyecto

Este script permite a los usuarios visualizar las ofertas actuales de distintas marcas de celulares y navegar por un menú interactivo para consultar las especificaciones técnicas detalladas de modelos específicos (Xiaomi, iPhone y Samsung). 

El proyecto destaca por su estructura limpia y el uso de buenas prácticas de programación, ideal para demostrar conocimientos básicos/intermedios en Python.

## ✨ Características Principales

* **Programación Orientada a Objetos (POO):** Uso estructurado de clases y objetos.
* **Herencia (`Inheritance`):** Implementación de una clase padre `celulares` y clases hijas (`xiaomi`, `iphone`, `samsung`), reutilizando código mediante la función `super()`.
* **Polimorfismo y Métodos Específicos:** La clase `samsung` incluye atributos (`novedads`) y métodos (`nsamsung()`) exclusivos que no comparten las demás marcas.
* **Estructuras de Datos Inmutables:** Uso de **tuplas** para manejar el inventario fijo de ofertas, garantizando la integridad de los datos durante la ejecución.
* **Interfaz de Línea de Comandos (CLI):** Un menú interactivo con validación de entradas construido con bucles `while True` para una navegación continua y amigable.
