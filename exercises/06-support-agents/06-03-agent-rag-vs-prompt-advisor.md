# 06-03 agent rag vs prompt advisor

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [06-03 agent rag vs prompt advisor](#06-03-agent-rag-vs-prompt-advisor)
  - [Objetivo](#objetivo)
  - [Índice](#índice)
  - [Requisitos previos](#requisitos-previos)
  - [Estimación de tiempo](#estimación-de-tiempo)
  - [Instrucciones](#instrucciones)
    - [Paso 1: Verificar que se encuentra activo el agente](#paso-1-verificar-que-se-encuentra-activo-el-agente)
    - [Paso 2: Probar diferentes ejemplos de prompts de usuario](#paso-2-probar-diferentes-ejemplos-de-prompts-de-usuario)
  - [Versionado](#versionado)
  - [Autores](#autores)

## Requisitos previos

* Visual Studio Code instalado en el equipo
* Extensión de "AI Engineer Coach" instalada en Visual Studio Code

## Estimación de tiempo

Tiempo estimado en complentarse: 5-15 minutos

## Instrucciones

### Paso 1: Verificar que se encuentra activo el agente

Verficar que el agente se encuentra cargado y activo en alguno de los ambientes de trabajo mostrado (github copilot, chat IA conversacional o modo agente IA conversacional)

### Paso 2: Probar diferentes ejemplos de prompts de usuario

Algunos ejemplos de uso pueden ser los siguientes:

Nota: Recordar que se le puede "apretar" con el prompt o bien cambiar un poco el formato de respuesta

```bash
# ***Nivel 1 - Prompt Directo (NO RAG)***
Quiero analizar un documento corto (2 páginas) y hacer un resumen. ¿Necesito RAG o puedo usar prompt directo?

Tengo un conjunto pequeño de datos que puedo incluir directamente en el prompt. ¿Es mejor usar RAG o no?

# ***Nivel 2 - Búsqueda + fragmentos (sin RAG completo)***
Tengo un documento de 200 páginas pero solo necesito responder preguntas ocasionales. ¿Qué estrategia me recomiendas?

Quiero consultar manuales largos de forma puntual. ¿Uso RAG o hago selección de fragmentos bajo demanda?

# ***Nivel 3 - RAG (cuando sí tiene sentido)***
Tengo miles de documentos internos y quiero construir un sistema de preguntas y respuestas con trazabilidad. ¿Necesito RAG?

Quiero responder preguntas sobre documentación corporativa y mostrar fuentes. ¿Qué arquitectura es adecuada?

# ***Nivel 4 - SQL/API vs RAG (error tipico)***
Tengo una base de datos con información de clientes. ¿Debería usar RAG o consultas SQL?

Quiero responder preguntas sobre datos tabulares (ventas, KPIs). ¿Tiene sentido usar embeddings?

# ***Nivel 4 – Arquitectura híbrida (el caso real enterprise)***
Tengo datos estructurados y documentos no estructurados. ¿Cómo debería combinar SQL, APIs y RAG?

Quiero diseñar un sistema que combine datos de base de datos y documentación interna. ¿Qué estrategia de conocimiento recomiendas?


# AYUDA EXTRA
Para este caso de uso, compara prompt directo, RAG y SQL/API en términos de coste y precisión

¿En qué condiciones este caso justificaría construir un sistema RAG?

Evalúa si estoy sobredimensionando la solución usando RAG.
```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**