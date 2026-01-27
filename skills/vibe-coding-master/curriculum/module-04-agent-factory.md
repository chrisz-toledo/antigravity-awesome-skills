# Module 04: The Agent Factory (Fábrica de Agentes)

## Objetivos
-   Entender qué es un "Agente" realmente.
-   Uso de `agent-tool-builder` y `agent-manager-skill`.
-   Introducción a RAG (Retrieval Augmented Generation).

## Conceptos Clave (Technical English Protocol)

| Español | Inglés (Bridge) | Immersion Context |
| :--- | :--- | :--- |
| Esquema | **Schema** | "Define the JSON **schema** for the tool..." |
| Carga Útil | **Payload** | "Check the request **payload**..." |
| Recuperación | **Retrieval** | "Optimize the RAG **retrieval**..." |
| Alucinación | **Hallucination** | "The agent had a **hallucination**..." |

## Lección 1: Agents are just Loops with Tools

Un agente no es magia. Es un bucle:
1.  Observa (Input).
2.  Piensa (LLM).
3.  Actúa (Tool).
4.  Repite.

## Lección 2: Building a Tool (Agent Tool Builder)

Vamos a crear una "Skill" real para Antigravity.
*Sabiduría de `agent-tool-builder`:*
-   La descripción de la herramienta es más importante que el código.
-   Si la IA no sabe cuándo usarla, la herramienta es inútil.

**Project:** Un agente simple que busca en Wikipedia y resume (usando una skill de búsqueda o scraping).

## Lección 3: Intro to RAG (Smarter Agents)

¿Cómo hacemos que el agente sepa cosas que no están en su entrenamiento?
Le damos documentos.
-   **RAG (Retrieval Augmented Generation):** Buscamos la info relevante y se la pegamos al agente antes de que responda.

**Challenge:** Diseña (en papel/texto) un agente que responda dudas sobre tu serie favorita usando RAG.

## Glosario Automático
Updates: Schema, Payload, Retrieval, Hallucination, RAG.
