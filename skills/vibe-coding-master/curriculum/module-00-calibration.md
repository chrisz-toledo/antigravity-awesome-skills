# Module 00: The Calibration (Perfil y Calibración)

## Objetivos (Objectives)
-   Crear tu **Perfil Psicológico de Aprendizaje** (`user_profile.json`).
-   Establecer tu **Línea Base en Inglés Técnico** (`English Baseline`).
-   Definir las **Métricas Clave** (`Metric Baseline`).

## Protocolo de Inicio (Startup Protocol)

El agente te hará una serie de preguntas. No hay respuestas incorrectas. Sé honesto.

### Fase 1: Entrevista de Estilo (Style Interview)

1.  **¿Visual vs. Abstracto?**
    -   *Pregunta:* "Cuando aprendes algo nuevo, ¿prefieres ver un diagrama/ejemplo visual primero, o leer la teoría detrás?"
    -   *Impacto:* Define el orden de las lecciones (UI primero vs. Schema primero).

2.  **¿Constructor vs. Analista?**
    -   *Pregunta:* "¿Prefieres romper cosas y arreglarlas (Trial & Error), o leer el manual antes de tocar nada?"
    -   *Impacto:* Define la cantidad de "Sandbox" vs. "Instrucciones paso a paso".

3.  **¿Tolerancia a la Frustración?**
    -   *Pregunta:* "¿Qué haces cuando el código falla 3 veces seguidas? A) Te frustras visualmente. B) Buscas en Google. C) Le preguntas a la IA inmediatamente."
    -   *Impacto:* Ajusta la frecuencia de las "pistas" y el soporte emocional del agente.

### Fase 2: Baseline de Inglés (English Baseline)

El agente presentará 5 términos técnicos. Tú debes decir si los conoces y qué significan.

*Ejemplo:*
-   "Loop"
-   "Array"
-   "Recursion"
-   "API Endpoint"
-   "Git Commit"

*Resultado:* El agente determinará si empezar con "Full Spanish" o "Rapid Bridge" (hacia el inglés).

### Fase 3: Configuración del Codex (Codex Setup)

El agente ejecutará los scripts para crear tu carpeta local:
```bash
~/Desktop/Vibe_Codex/
  ├── user_profile.json
  ├── symbiosis_log.md
  └── tech_glossary.md
```

## Salida (Output)

Al finalizar este módulo, tendrás un archivo `user_profile.json` que el agente leerá en cada sesión futura para personalizar tu experiencia.
