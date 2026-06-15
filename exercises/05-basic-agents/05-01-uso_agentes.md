# 05-01 uso agentes

## Objetivo

El ejercicio esta pensado para ayudar a enseñar diferentes formas de cargar "agentes" en diferentes plataformas y cómo pueden ser utilizados para mejorar la productividad y eficiencia en el desarrollo de proyectos de inteligencia artificial.

## Índice

- [05-01 uso agentes](#05-01-uso-agentes)
  - [Objetivo](#objetivo)
  - [Índice](#índice)
  - [Requisitos previos](#requisitos-previos)
  - [Estimación de tiempo](#estimación-de-tiempo)
  - [Instrucciones](#instrucciones)
    - [Paso 1: Uso desde GitHub Copilot](#paso-1-uso-desde-github-copilot)
    - [Paso 2: Uso desde un chat en una IA conversacional](#paso-2-uso-desde-un-chat-en-una-ia-conversacional)
    - [Paso 3: Uso desde el modo agente de una IA conversacional](#paso-3-uso-desde-el-modo-agente-de-una-ia-conversacional)
  - [Versionado](#versionado)
  - [Autores](#autores)

## Requisitos previos

* Visual Studio Code instalado en el equipo
* Extensión de "AI Engineer Coach" instalada en Visual Studio Code

## Estimación de tiempo

Tiempo estimado en complentarse: 10-15 minutos

## Instrucciones

### Paso 1: Uso desde GitHub Copilot

El agente es cargado automáticamente desde el directorio `.github/agents` al utilizar GitHub Copilot, por lo que no es necesario realizar ninguna acción adicional para cargar el agente. Sin embargo, es importante tener en cuenta que si el agente se quiere utilizar en un proyecto específico, es necesario asegurarse de que el agente esté configurado correctamente, que se estén utilizando las herramientas adecuadas para interactuar con él y que se encuentra activo

Ayuda: Revisar los emoticonos del nombre y el orden de la familia de agentes a la que pertenece

### Paso 2: Uso desde un chat en una IA conversacional

Cargar el system prompt desde una nueva conversación en una IA conversacional, como por ejemplo ChatGPT, para poder interactuar con el agente y así poder obtener recomendaciones personalizadas basadas en el historial de sesiones y proyectos del usuario

Normalmente, ante esta situación de carga del prompt el LLM entiende que esta aplicando una estrategia de role prompting, por lo que se asigna un rol al agente y se le proporcionan instrucciones para que pueda interactuar con el usuario de la mejor manera posible.

Truco: Cambiar el nombre y poner el nombre de la cabecera ténica. Ahora la conversación será facilmente identificable y el agente se podrá cargar de forma rápida en futuras ocasiones buscando por el nombre de la conversación

### Paso 3: Uso desde el modo agente de una IA conversacional

Similar al anterior pero cargado desde esta opción proporcionada por la IA Conversacional. Mejora enormemente la identificación y el uso.

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**