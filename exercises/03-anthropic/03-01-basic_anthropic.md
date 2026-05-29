# 03-01 basic anthropic

## Objetivo

Utilizar Google Collab para crear un código Python que conecte el API de un LLM y permite obtener una respuesta a una petición dada.

El ejercicio esta pensado para trabajar con la API de Anthropic

## Índice

- [03-01 basic anthropic](#03-01-basic-anthropic)
  - [Objetivo](#objetivo)
  - [Índice](#índice)
  - [Requisitos previos](#requisitos-previos)
  - [Estimación de tiempo](#estimación-de-tiempo)
  - [Instrucciones](#instrucciones)
    - [Paso 1: Cargar el notebook en Google Collab desde fichero o bien desde la URL del repositorio](#paso-1-cargar-el-notebook-en-google-collab-desde-fichero-o-bien-desde-la-url-del-repositorio)
      - [Desde el fichero](#desde-el-fichero)
      - [Desde la URL del repositorio](#desde-la-url-del-repositorio)
    - [Paso 2: Verificar que se ha cargado la API Key de Anthropic en el entorno de Google Collab](#paso-2-verificar-que-se-ha-cargado-la-api-key-de-anthropic-en-el-entorno-de-google-collab)
    - [Paso 3: Seguir la explicación del ejercicio desde el notebook](#paso-3-seguir-la-explicación-del-ejercicio-desde-el-notebook)
  - [Versionado](#versionado)
  - [Autores](#autores)

## Requisitos previos

* Cuenta de Google Personal o Corporativa
* Acceso a Google Collab
* Cuenta activa en Anthropic Platform, con créditos y con un API Key generada
* Configuración del secreto de la API Key de Anthropic en Google Collab
  * Se habrían realizado en el módulo 00-getting-started, pero si no se han realizado, se puede configurar en este ejercicio siguiendo las instrucciones del módulo 00-getting-started

## Estimación de tiempo

Tiempo estimado en complentarse: 30-60 minutos

## Instrucciones

### Paso 1: Cargar el notebook en Google Collab desde fichero o bien desde la URL del repositorio

#### Desde el fichero

Pasos a seguir:

* Localizar la ruta del fichero `03_01_basic_anthropic_v1_0.ipynb` dentro del repositorio
* Acceder a la plataforma de Google Collab
* Cargar el notebook en Google Collab desde la ruta del fichero localizada
* Verificar que el notebook se ha cargado correctamente y que se pueden ejecutar las celdas sin errores

#### Desde la URL del repositorio

Pasos a seguir:

* Acceder a la URL del fichero ".ipynb" en el repositorio de GitHub
  * https://github.com/vjmadrid/workspace-cost-engineering/blob/main/exercises/03-anthropic/03_01_basic_anthropic_v1_0.ipynb
* Reemplazar "github.com" por "colab.research.google.com/github"

```
https://github.com/vjmadrid/workspace-cost-engineering/blob/main/exercises/03-anthropic/03_01_basic_anthropic_v1_0.ipynb
```

* Acceder a la URL modificada
* Verificar que se ha cargado correctamente
* Verificar que el notebook se ha cargado correctamente y que se pueden ejecutar las celdas sin errores

### Paso 2: Verificar que se ha cargado la API Key de Anthropic en el entorno de Google Collab

Seguir los pasos indicados en la documentación facilitada en 'exercises/01-google-collab/01-01-prepare-google-collab.md'

### Paso 3: Seguir la explicación del ejercicio desde el notebook

Se irán alternando secciones de teoría en celdas de texto con celdas de código para ejecutar y probar lo explicado en cada sección. Se recomienda seguir el orden de las celdas para no perder el hilo de la explicación y para entender mejor el ejercicio.

Hay que tener en cuenta que se harán uso de las SDKs oficiales de Anthropic, por lo que se recomienda revisar la documentación oficial para entender mejor su funcionamiento y las posibilidades que ofrece.

Documentación de referencia sobre el funcionamiento de la API de Anthropic:

* Anthropic Messages API: https://docs.anthropic.com/en/api/messages


## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**