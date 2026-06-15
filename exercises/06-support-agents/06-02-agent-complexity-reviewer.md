# 06-02 agent complexity reviewer

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [06-02 agent complexity reviewer](#06-02-agent-complexity-reviewer)
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
# ***Nivel 1/2 - Cuando probablemente no se necesita un agente***
Quiero usar un agente para generar resúmenes de documentos. ¿Es necesario o basta con un prompt simple?

Estoy pensando en crear un agente que valide datos de entrada y los formatee. ¿Tiene sentido o debería usar otra solución?

Quiero montar un sistema con tools para transformar texto en JSON. ¿Necesito un agente o basta con una función?

# ***Nivel 3 - Workflow vs RPA***
Tengo un flujo con varios pasos: recibir datos, validarlos, transformarlos y almacenarlos. Estoy planteando usar un agente. ¿Es adecuado?

Quiero automatizar un proceso con varias llamadas a APIs y validaciones. ¿Necesito un agente o un workflow determinista?

# ***Nivel 4 - RAG + herramientas***
Quiero montar un sistema que consulte documentos y genere respuestas usando herramientas externas. ¿Necesito un agente o basta con RAG?

Tengo que recuperar información de una base documental y ejecutar acciones según el resultado. ¿Qué nivel de complejidad es adecuado?

# ***Nivel 5 - Agentes con Planificación***
Quiero crear un agente que analice un problema, planifique pasos y ejecute acciones en sistemas externos. ¿Está justificado este nivel de autonomía?

Mi sistema usa loops con múltiples tool calls para resolver tareas. Analiza si este enfoque es excesivamente complejo

# ***Nivel 6 - Multiagente***
Estoy diseñando un sistema multiagente con roles de planner, executor y reviewer. ¿Está justificado o es sobreingeniería?

Quiero dividir el sistema en varios agentes especializados. ¿Qué condiciones deberían cumplirse para que tenga sentido?

# AYUDA EXTRA
Analiza esta solución basada en agentes y determina si está sobredimensionada

Para este caso de uso, justifica si realmente se necesita un agente o no

Compara esta arquitectura basada en agente con una alternativa más simple
```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**