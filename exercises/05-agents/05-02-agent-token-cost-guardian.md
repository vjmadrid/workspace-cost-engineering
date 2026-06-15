# 05-02 token cost guardian

## Objetivo

El ejercicio esta pensado para ayudar a usar este agente

## Índice

- [05-02 token cost guardian](#05-02-token-cost-guardian)
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
# ***Nivel Básico***
Quiero generar un resumen de este texto de 3 párrafos

Quiero generar un resumen de este texto de 3 párrafos. ¿Hay algún riesgo de consumo de tokens antes de ejecutar?

Voy a pedirle a un modelo que genere una lista de 10 ideas de negocio

Voy a pedirle a un modelo que genere una lista de 10 ideas de negocio. ¿Es necesario optimizar algo o puedo ejecutarlo directamente?

# ***Nivel Medio***
Necesito analizar este documento de 20 páginas y generar un resumen ejecutivo

Necesito analizar este documento de 20 páginas y generar un resumen ejecutivo. Antes de hacerlo, evalúa si hay riesgo de consumo de tokens y cómo puedo optimizar la solicitud.

Quiero una explicación detallada sobre microservicios con ejemplos y comparativas. ¿Debería limitar la salida o reformular la petición?

Voy a pasarle varios logs a un modelo para entender un error. ¿Qué debería recortar o ajustar para evitar gastar tokens innecesarios?

# ***Nivel Avanzado***
Voy a subir 5 PDFs técnicos de más de 50 páginas cada uno y pedir un informe consolidado.

Voy a subir 5 PDFs técnicos de más de 50 páginas cada uno y pedir un informe consolidado. Analiza el riesgo de consumo de tokens y dime cómo debería dividir o reformular la tarea.

Quiero que un modelo analice este repositorio completo  y genere documentación, tests y mejoras. 

Quiero que un modelo analice este repositorio completo  y genere documentación, tests y mejoras. Evalúa el coste y propón una estrategia más eficiente.
```

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**