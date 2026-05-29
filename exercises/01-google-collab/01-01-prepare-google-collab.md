# 01-01-prepare-google-collab

## Objetivo

Preparar el entorno de Google Collab para poder ejecutar los ejercicios de este curso

## Índice

- [01-01-prepare-google-collab](#01-01-prepare-google-collab)
  - [Objetivo](#objetivo)
  - [Índice](#índice)
  - [Requisitos previos](#requisitos-previos)
  - [Estimación de tiempo](#estimación-de-tiempo)
  - [Instrucciones](#instrucciones)
    - [Paso 1: Establecer el API Key de OpenAI](#paso-1-establecer-el-api-key-de-openai)
    - [Paso 2: Establecer el API Key de Anthropic](#paso-2-establecer-el-api-key-de-anthropic)
  - [Versionado](#versionado)
  - [Autores](#autores)

## Requisitos previos

* Leer la documentación indicada: [Documentación Google Collab](https://github.com/vjmadrid/workspace-cost-engineering/blob/main/docs/google-collab.md)

* Cuenta activa en OpenAI Platform, con créditos y con un API Key generada
* Cuenta activa en Anthropic Console, con créditos y con un API Key generada
* Cuenta activa de Google Personal o Corporativa

## Estimación de tiempo

Tiempo estimado en complentarse: 5-10 minutos

## Instrucciones

### Paso 1: Establecer el API Key de OpenAI

Pasos a seguir:

* Acceder a la plataforma de Google Collab: [Google Collab](https://colab.research.google.com/)
* Acceder a la sección de "Secrets" o "Secretos" del entorno de Google Collab
* Crear un nuevo secreto con el nombre que se quiera y con el valor del API Key generado en OpenAI Platform anteriormente
  * Por ejemplo:**OPENAI_API_KEY_LAB** o **OPENAI_API_KEY** (si se quiere usar el mismo nombre que en local) o cualquier otro nombre que se quiera usar para identificar el secreto
* Verificar que el secreto se ha creado correctamente y que el valor es correcto (suele empezar por "sk-")

### Paso 2: Establecer el API Key de Anthropic

Pasos a seguir:

* Similar al paso 1, pero esta vez creando un nuevo secreto con el valor del API Key generado en Anthropic Console anteriormente
  * Por ejemplo: **ANTHROPIC_API_KEY_LAB** o **ANTHROPIC_API_KEY** (si se quiere usar el mismo nombre que en local) o cualquier otro nombre que se quiera usar para identificar el secreto
* Verificar que el secreto se ha creado correctamente y que el valor es correcto (suele empezar por "sk-ant-")

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**