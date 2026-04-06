# 00-CHelloWorld: "Hello, World!" en C23

Este ejercicio consiste en la configuración inicial del entorno de desarrollo, la instalación de un compilador que soporte el estándar C23 y la verificación del flujo de trabajo (edición, compilación, ejecución y redirección).

## Información del Compilador
* **Compilador seleccionado:** GCC (GNU Compiler Collection)
* **Versión del compilador:** 13.3.0 (Ubuntu 13.3.0-6ubuntu2~24.04)
* **Versión de C:** C23 (compilado mediante el flag `-std=c2x`, que activa el soporte preliminar completo en esta versión de GCC).

## Instrucciones de Compilación y Ejecución

### Compilación Manual
Para compilar el programa utilizando el estándar C23 (C2x):
```bash
gcc -std=c2x hello.c -o hello