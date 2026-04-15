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

## 📋 Requisitos

Para ejecutar este proyecto, solo necesitas tener instalado:
* [Python 3.x](https://www.python.org/downloads/)

## 🛠️ Cómo ejecutar el proyecto

1.  Clona este repositorio en tu máquina local:
    ```bash
    git clone [https://github.com/TuUsuario/TuRepositorio.git](https://github.com/TuUsuario/TuRepositorio.git)
    ```
2.  Navega a la carpeta del proyecto:
    ```bash
    cd TuRepositorio
    ```
3.  Ejecuta el script desde tu terminal (o desde la terminal integrada de tu editor, como Windsurf o VS Code):
    ```bash
    python nombre_del_archivo.py
    ```
    *(Asegúrate de reemplazar `nombre_del_archivo.py` por el nombre real de tu script).*

## 🏗️ Estructura del Código

El código está dividido en tres partes principales:

1.  **Definición de Clases:** Donde se establece la arquitectura base de los objetos.
2.  **Sección de Ofertas:** Uso de bucles `for` y tuplas para mostrar los modelos en promoción.
3.  **Bucle Principal (Menú):** La lógica de interacción con el usuario usando `input()`, condicionales `if/elif/else`, y control de flujo con `break` y `continue`.

## 🤝 Contribuciones

Este es un proyecto de aprendizaje continuo. Las contribuciones, sugerencias o reportes de errores son bienvenidos. ¡Siéntete libre de hacer un *fork* y enviar un *pull request*!

---
*Desarrollado con 💻 y ☕*
