# Google Collab

Herramienta de Google que permite ejecutar código Python en la nube, facilitando el acceso a recursos computacionales, el desarrollo de pequeñas pruebas de concepto y la colaboración en proyectos de ciencia de datos y aprendizaje automático.

Se trata de un entorno de notebooks basados en Jupyter

Características principales:

* Tiene Python preinstalado
* Incluye muchas librerías populares de ciencia de datos y aprendizaje automático ya preinstaladas
* Permite ejecutar código en la nube de Google, lo que significa que no es necesario configurar un entorno local
* Integración con Google Drive, lo que facilita el almacenamiento y acceso a archivos
* Colaboración en tiempo real, lo que permite a varios usuarios trabajar en el mismo notebook

## Índice

- [Google Collab](#google-collab)
  - [Índice](#índice)
  - [Pre-Requisitos](#pre-requisitos)
  - [Instalación](#instalación)
  - [Configuración](#configuración)
  - [Uso](#uso)
    - [Acceder a la plataforma de Google Collab](#acceder-a-la-plataforma-de-google-collab)
    - [Crear un notebook nuevo](#crear-un-notebook-nuevo)
    - [Abrir un notebook existente](#abrir-un-notebook-existente)
      - [Abrir un notebook existente desde archivo local](#abrir-un-notebook-existente-desde-archivo-local)
      - [Abrir un notebook existente desde Google Drive](#abrir-un-notebook-existente-desde-google-drive)
      - [Abrir un notebook existente desde un repositorio de GitHub](#abrir-un-notebook-existente-desde-un-repositorio-de-github)
    - [Instalar librerías adicionales](#instalar-librerías-adicionales)
    - [Gestionar de secretos](#gestionar-de-secretos)
    - [Usar secretos en el notebook](#usar-secretos-en-el-notebook)
  - [Versionado](#versionado)
  - [Autores](#autores)

## Pre-Requisitos

* Cuenta de Google Personal o Corporativa

## Instalación

N/A

## Configuración

N/A

## Uso

### Acceder a la plataforma de Google Collab

Pasos a seguir:

* Acceder a la URL: [https://colab.research.google.com/](https://colab.research.google.com/)
* Autenticarse con la cuenta de Google
* Verificar que nos encontramos dentro y se muestra un mensaje de "Bienvenida"

### Crear un notebook nuevo

Pasos a seguir:

* Acceder a la plataforma de Google Collab
* Hacer click en "Archivo" -> "Nuevo cuaderno"

Nota: El notebook se guardará automáticamente en tu Google Drive, dentro de una carpeta llamada "Colab Notebooks"

### Abrir un notebook existente

Existen varias formas de abrir un notebook existente

#### Abrir un notebook existente desde archivo local

Pasos a seguir:

* Descargar el fichero ".ipynb" en tu ordenador
* Acceder a la plataforma de Google Collab
* Hacer click en "Archivo" -> "Abrir cuaderno" -> "Subir"
* Seleccionar el fichero descargado
* Verificar que se ha cargado correctamente

#### Abrir un notebook existente desde Google Drive

Pasos a seguir:

* Acceder a la plataforma de Google Collab
* Hacer click en "Archivo" -> "Abrir cuaderno" -> "Google Drive"
* Seleccionar el notebook que se desea abrir
* Verificar que se ha cargado correctamente

#### Abrir un notebook existente desde un repositorio de GitHub

Pasos a seguir:

* Acceder a la URL del fichero ".ipynb" en el repositorio de GitHub
* Reemplazar "github.com" por "colab.research.google.com/github"
* Acceder a la URL modificada
* Verificar que se ha cargado correctamente

### Instalar librerías adicionales

* Disponer del notebook abierto en Google Collab
* Crear una celda de código nueva
* Escribir el comando de instalación de la librería utilizando el prefijo "!" (por ejemplo, "!pip install numpy")

```bash
# Ejemplo de instalación de la librería "openai"
!pip install openai
```

### Gestionar de secretos

Pasos a seguir:

* Acceder a la plataforma de Google Collab
* Acceder a la funcionalidad de "Secretos" a través del menú lateral izquierdo
* Acceder a la opción de "Añadir un nuevo secreto"
* Seleccionar un nombre adecuado para el secreto (por ejemplo, "OPENAI_API_KEY")
* Introducir el valor del secreto (por ejemplo, la clave de API de OpenAI)
* Guardar el secreto
* Verificar que se encuentra disponible para su uso en el notebook
* Habilitar si se quiere tener un acceso desde el notebook

La gestión de secretos es un punto muy importante del uso de esta herramienta y hay que tener varias consideraciones:

* El nombre del secreto NO se puede cambiar una vez creado (solución: borrar y volver a crear con el nuevo nombre)
* Nunca escribir secretos directamente en el código del notebook
* Si se comparte o bien se sube el código a un repositorio público se estaría exponiendo el secreto a todo el mundo, lo que puede suponer un riesgo de seguridad importante
* Los secretos se guardan en la cuenta de Google y NO en el notebook, por lo que no se exponen aunque se comparta el notebook con otras personas

### Usar secretos en el notebook

Pasos a seguir:

* El secreto debe estar creado y habilitado para su uso en el notebook seleccionado
* Incorporar en la sección de código que se vaya a utilizar una estructura similar a la siguiente:

```python
from google.colab import userdata

userdata.get('SECRET_NAME')
```

Para ello se incopora una librería de Google Collab llamada "userdata" que permite acceder a los secretos creados en la cuenta de Google

Posteriormente, se accedería a través del nombre del secreto mediante el método "get" y se podría utilizar su valor para lo que se necesite (por ejemplo, para autenticarse en una API)

## Versionado

**Nota :** [SemVer](http://semver.org/) es utilizado por el versionado

Para ver las versiones disponibles ver los tags del repositorio

## Autores

* **Víctor Madrid**