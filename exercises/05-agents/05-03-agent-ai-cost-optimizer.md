# 05-03 ai cost optimizer

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [05-03 ai cost optimizer](#05-03-ai-cost-optimizer)
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
# ***Nivel 1 - Solucion determinista (ANTI-IA)***
Tengo un CSV con datos de ventas y quiero calcular métricas agregadas y rankings

Tengo un CSV con datos de ventas y quiero calcular métricas agregadas y rankings. ¿Necesito usar IA o basta con SQL o scripting?

Quiero validar emails y teléfonos en un formulario

Quiero validar emails y teléfonos en un formulario. ¿Me conviene usar IA o reglas y expresiones regulares?

Necesito renombrar miles de archivos siguiendo un patrón

# ***Nivel 2 - Automatización integrada***
Tengo que mover datos entre varios sistemas (CRM, ERP y Excel) con validaciones. ¿Qué arquitectura mínima me recomiendas?

Necesito generar reportes diarios a partir de datos estructurados. ¿Es mejor usar SQL + job programado o IA?

# ***Nivel 3 - Modelo pequeñio o IA Controlada***
Quiero clasificar tickets de soporte por temática (facturación, técnico, incidencias). ¿Qué solución mínima viable recomiendas?

Necesito extraer información clave (nombre, empresa, importe) de PDFs semi-estructurados. ¿Uso regex, parser o IA?

Tengo comentarios de usuarios y quiero detectar sentimiento y temas principales. ¿Qué nivel de IA necesito realmente?

# ***Nivel 4 - LLM avanzado vs overengineering***
Quiero usar un agente autónomo para analizar todos los documentos de un proyecto y generar decisiones estratégicas. ¿Es necesario o hay alternativas más simples?

Estoy pensando en usar un LLM avanzado para generar documentación técnica a partir de código. ¿Hay opciones más baratas o controlables?

# ***Nivel 4+ - Casos complejos***
Tengo que diseñar un sistema que procese miles de documentos al día y genere insights. Evalúa qué partes necesitan IA y cuáles deberían resolverse con procesamiento determinista

Quiero diseñar un pipeline con ingestión, procesamiento, análisis y generación de contenido. Dame la arquitectura mínima viable optimizada en coste
```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**