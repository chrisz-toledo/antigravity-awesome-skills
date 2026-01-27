# Module 02: Functional Tools (Herramientas Funcionales)

## Objetivos
-   Romper el miedo al código "real" (Python/JS).
-   La "Ley de Hierro" del TDD (Test Driven Development).
-   Crear tu primera herramienta útil (File Organizer).

## Conceptos Clave (Technical English Protocol)

| Español | Inglés (Bridge) | Immersion Context |
| :--- | :--- | :--- |
| Script | **Script** | "Run the python **script**..." |
| Función | **Function** | "Define a **function** to sort files..." |
| Prueba | **Test Case** | "Write a **test case** first..." |
| Variable | **Variable** | "Assign values to the **variable**..." |

## Lección 1: Scripting Basics

No vamos a aprender sintaxis de memoria. Vamos a aprender a *leer* lo que la IA nos da.
-   **Variables:** Cajitas donde guardamos cosas.
-   **Functions:** Pequeños robots que hacen tareas específicas.
-   **Loops:** Hacer lo mismo muchas veces.

## Lección 2: The Iron Law (TDD)

*Sabiduría de `test-driven-development` skill.*

Antes de decirle a la IA "haz un script que organice archivos", debemos definir: **¿Cómo sabemos si funciona?**

1.  **Red (Fallo):** Creamos una carpeta de prueba desordenada. Ejecutamos el script (que aún no existe). Falla.
2.  **Green (Éxito):** La IA escribe el código. Lo ejecutamos. Se ordenan los archivos.
3.  **Refactor (Mejora):** ¿Podemos hacerlo más limpio?

*Regla de Oro:* **"No Production Code Without a Failing Test First."**
(No aceptamos código si no hemos visto primero que algo fallaba sin él).

## Lección 3: Project - The File Organizer

Vamos a crear un script real que limpie tu carpeta de Descargas (o una de prueba).
-   Entrada: Carpeta llena de `.jpg`, `.pdf`, `.docx`.
-   Proceso: La IA escribe la lógica.
-   Salida: Carpetas `/Images`, `/Documents` con los archivos movidos.

**Challenge:** Modifica el script para que borre automáticamente archivos `.tmp` viejos.

## Glosario Automático
Updates: Script, Function, Test Case, Variable, TDD.
