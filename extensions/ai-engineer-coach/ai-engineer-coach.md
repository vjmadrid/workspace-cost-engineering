# ai-engineer-coach

## Objetivo

Extensión para Visual Studio Code con el objetivo de facilitar metainformación, análisis del uso y  descubrimiento de buenas prácticas a la hora de utilizar GitHub Copilot (olores de uso, salud contextual, etc.)

Para ello, realiza un seguimiento del progreso de uso a nivel local (analiza las local session logs)

[Repositorio en GitHub](https://github.com/microsoft/AI-Engineering-Coach)

## Índice

- [ai-engineer-coach](#ai-engineer-coach)
  - [Objetivo](#objetivo)
  - [Índice](#índice)
  - [Requisitos previos](#requisitos-previos)
  - [Estimación de tiempo](#estimación-de-tiempo)
  - [Instrucciones](#instrucciones)
    - [Paso 1: Descargar la extensión proporcionada del repositorio a local](#paso-1-descargar-la-extensión-proporcionada-del-repositorio-a-local)
    - [Paso 2: Instalar la extensión en Visual Studio Code](#paso-2-instalar-la-extensión-en-visual-studio-code)
  - [Versionado](#versionado)
  - [Autores](#autores)

## Requisitos previos

* Disponer de node.js y npm instalados en el sistema si se quiere construir la extensión a partir del código fuente
* Disponer de Visual Studio Code instalado para poder instalar la extensión y utilizarla

## Estimación de tiempo

Tiempo estimado en complentarse: 5-10 minutos

## Instrucciones

### Paso 1: Descargar la extensión proporcionada del repositorio a local

Clonar el repositorio a local o bien descargar la extensión proporcionada en una ruta local que este localizada

El fichero se encuentra en el directorio `extensions/ai-engineer-coach` con el nombre `ai-engineer-coach.vsix`

### Paso 2: Instalar la extensión en Visual Studio Code

Para la versión Linux/macOS ejecutar el siguiente comando en la terminal:

```bash
# Para la ruta especificada
code --install-extension /path/to/ai-engineer-coach-0.1.0.vsix

# Para el fichero en la ruta donde nos encontramos
code --install-extension ai-engineer-coach-0.1.0.vsix
```

**IMPORTANTE**
Si se quiere tambine se puede realizar uan construcción de la extensión en local a partir del código fuente



## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**