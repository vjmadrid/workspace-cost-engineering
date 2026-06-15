# 06-01 agent automation first advisor

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [06-01 agent automation first advisor](#06-01-agent-automation-first-advisor)
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
# ***Nivel 1 - Reglas (ANTI-IA)***
Quiero validar si un email es correcto y si un número de teléfono tiene formato válido. ¿Necesito IA o puedo hacerlo con reglas?

Tengo que aprobar o rechazar solicitudes en base a condiciones fijas (importe, país, tipo de cliente). ¿Tiene sentido usar IA?

Quiero filtrar registros en función de valores específicos en columnas. ¿Qué solución es más simple?

# ***Nivel 2 - SCRIPT o SQL***
Necesito transformar datos de Excel y generar un informe diario. ¿Lo hago con IA o con SQL/script?

Tengo que cruzar datos entre dos tablas y calcular métricas. ¿Es necesario usar IA?

Quiero limpiar y normalizar datos antes de cargarlos en un sistema. ¿Qué solución recomiendas?

# ***Nivel 3 - Workflow o RPA***
Quiero automatizar el proceso de recepción de pedidos, validación y registro en el ERP. ¿Necesito IA o un workflow?

Necesito mover datos entre sistemas (CRM, ERP, base de datos) con validaciones. ¿Qué arquitectura mínima usar?

Quiero automatizar la gestión de incidencias repetitivas. ¿IA o RPA?

# ***Nivel 4 - IA parcial (uso correcto de IA)***
Quiero clasificar emails de clientes. Algunos son muy claros, otros ambiguos. ¿Cómo diseño la solución sin usar IA de más?

Necesito procesar facturas: la mayoría tienen formato estable, pero hay excepciones. ¿Cómo repartir automatización vs IA?


# AYUDA EXTRA
Para este caso de uso, identifica qué porcentaje del flujo puede resolverse sin IA

Diseña una solución donde la IA solo intervenga cuando las reglas no puedan resolver el problema

Evalúa si este caso de uso está sobredimensionado con IA y propón una alternativa más simple
```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**