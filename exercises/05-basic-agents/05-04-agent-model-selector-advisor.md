# 05-04 model selector advisor

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [05-04 model selector advisor](#05-04-model-selector-advisor)
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
# ***Nivel 1 - Modelo pequeño***
Quiero clasificar textos cortos en categorías predefinidas (spam, soporte, ventas). ¿Qué tipo de modelo necesito?

Necesito extraer campos estructurados (nombre, email, teléfono) de textos simples. ¿Qué modelo mínimo es suficiente?

Quiero transformar texto en JSON con un formato fijo

# ***Nivel 2 - Modelo medio***
Necesito generar resúmenes ejecutivos de documentos de 2-3 páginas

Quiero redactar emails profesionales a partir de instrucciones breves

Tengo que extraer información de textos algo ambiguos (contratos, incidencias)

# ***Nivel 3 - Modelo avanzado***
Necesito analizar varios documentos técnicos y detectar inconsistencias entre ellos. ¿Qué tipo de modelo es necesario?

Quiero generar código complejo a partir de requisitos ambiguos y validar distintas opciones. ¿Qué modelo debería usar?

# ***Nivel 4 - Routing y fallback***
Tengo un sistema que procesa consultas de usuarios: algunas son simples (FAQ) y otras complejas (análisis). ¿Cómo debería seleccionar modelos para optimizar coste?

Quiero diseñar un sistema con distintos tipos de tareas (clasificación, resumen, generación). ¿Debo usar un único modelo o routing?

# AYUDA EXTRA

Tengo un flujo con ingestión de datos, clasificación, análisis y generación. ¿Qué modelo debería usar en cada fase?

Para esta tarea, compárame modelo pequeño, medio y avanzado en términos de coste, calidad y reintentos.

```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**