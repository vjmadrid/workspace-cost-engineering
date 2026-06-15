# 05-06 agent context optimizer

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [05-06 agent context optimizer](#05-06-agent-context-optimizer)
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
# ***Nivel 1 - Recorte directo***
Voy a enviar un documento de 50 páginas para que me haga un resumen. ¿Qué partes podría eliminar antes de enviarlo?

Tengo un historial de conversación muy largo y quiero hacer una pregunta puntual. ¿Qué contexto necesito mantener realmente?

Quiero analizar estos logs completos del sistema. ¿Qué debería filtrar antes de enviárselos al modelo?

# ***Nivel 2 - Filtrado por criterios***
Tengo un repositorio grande y quiero analizar un bug. ¿Qué archivos debería incluir y cuáles no?

Voy a procesar varios PDFs legales, pero solo necesito información sobre cláusulas económicas. ¿Cómo filtro el contenido?

# ***Nivel 3 - Selección semántica***
Tengo miles de documentos y quiero responder preguntas sobre ellos. ¿Cómo selecciono solo los fragmentos relevantes?

Voy a procesar tickets de soporte antiguos para encontrar patrones. ¿Cómo reduzco el volumen sin perder información relevante?

# ***Nivel 4 - Estrategia Recurrente***
Tengo un sistema que procesa documentos largos constantemente. ¿Qué estrategia debo usar para minimizar el contexto en cada petición?

Estoy enviando demasiado contexto a los modelos y el coste se dispara. Diseña una estrategia para reducirlo de forma recurrente

Este es mi flujo actual: envío todo el repositorio para cada petición. Analiza cómo reducir el contexto y propón una estrategia más eficiente

# AYUDA EXTRA
Identifica qué porcentaje de este contexto es realmente necesario para resolver la tarea

Optimiza este contexto para que sea lo más pequeño posible sin perder precisión: [CONTEXTO]

Diseña una estrategia de selección de contexto para este caso que sea eficiente en coste
```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**