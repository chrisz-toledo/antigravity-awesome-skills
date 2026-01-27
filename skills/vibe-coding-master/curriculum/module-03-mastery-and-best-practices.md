# Module 03: Mastery & Best Practices (Maestría)

## Objetivos
-   Dejar de adivinar (`systematic-debugging`).
-   Conceptos de "Clean Code" en la era de la IA.
-   Leer y aprender de los `SKILL.md` existentes.

## Conceptos Clave (Technical English Protocol)

| Español | Inglés (Bridge) | Immersion Context |
| :--- | :--- | :--- |
| Depuración | **Debugging** | "Start **debugging** the error..." |
| Causa Raíz | **Root Cause** | "Find the **root cause**, don't guess..." |
| Refactorizar | **Refactor** | "**Refactor** this function to be cleaner..." |
| Documentación | **Documentation / Docs** | "Read the **docs**..." |

## Lección 1: Stop Guessing (Systematic Debugging)

*Sabiduría de `systematic-debugging` skill.*

Cuando algo falla, el instinto es decir a la IA: "Arrglalo". **ERROR.**
La IA adivinará. Tú te confundirás.

**El Vibe Correcto:**
1.  **Read:** Leer el error completo (Stack Trace).
2.  **Hypothesis:** "¿Creo que falla porque el archivo no existe?".
3.  **Verify:** Comprobar la hipótesis *antes* de cambiar código.

## Lección 2: Clean Code is for Humans

La IA escribe código rápido, pero a veces sucio.
Tú eres el editor.
-   Variables con nombres claros (`user_list` mejor que `ul`).
-   Funciones cortas (si hace 10 cosas, divídela).
-   Comentarios que expliquen el *POR QUÉ*, no el *CÓMO*.

## Lección 3: The Ancient Scrolls (Reading Skills)

Vamos a abrir la carpeta `.agent/skills/skills` y leer una skill al azar.
Son las instrucciones internas de tus agentes.
Aprender a leerlas te da superpoderes para controlarlos.

**Challenge:** Lee `agent-tool-builder` y explícame en 3 líneas qué hace.

## Glosario Automático
Updates: Debugging, Root Cause, Refactor, Documentation, Stack Trace.
