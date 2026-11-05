# ejemplo-opencode
Repositorio para la implementación de Open Code

## Descripción y alcance del repositorio
Utiliza este repositorio para crear cualquier aplicación con ayuda de los agentes de Open Code.

Vista el [sitio oficial](https://opencode.ai/) para leer la documentación correspondiente a su uso.

## Contenido del repositorio
A continuación se muestra el directorio raíz del repositorio:
```
  ejemplo-opencode/
  ├── containers/
  │   └── .gitkeep
  ├── volumes/
  │   └── .gitkeep
  ├── .gitignore
  ├── compose.yaml
  ├── LICENSE
  ├── README.md
  └── template-agents.txt
```
* Directorio `containers/`. Direcotrio base para la creación de contenedores `Docker`.
* Directorio `volumes/`. Directorio para contener los volumenes de los contenedores.
* Archivo `.gitignore`. Reglas de este repositorio.
* Archivo `compose.yaml`. Preparado para la declaración de los servicios de la aplicación.
* Archivo `LICENSE`. Licencia de uso del repositorio.
* Archivo `README.md`. Este documento.
* Archivo `template-agents-txt`. Documento de ejemplo con la redacción necesaria para un correcto archivo `AGENTS.md`.

## Primeros pasos
1. Iniciar la apliacación de Opencode dentro del directorio destinada al desarrollo de la aplicación:
```
$ opencode
```
2. Crear el archivo `AGENTS.md` desde la terminal de _*Open Code*_ 
```
/init <Breve descripción del proyecto>
```

El agente creara el archivo leyendo el contenido de este repositorio. Echale un ojo a [Agents.md](https://agents.md/) donde encontraras varias referencias para el uso de agentes.

## ¿Cómo usar este repositorio?
Considera que la branch `development` mantiene la estructura básica para la implementación de _*Open Code*_ en cualquier proyecto por lo que te recomiendo crear una nueva branch a partir de esta y ajusta los archivos de acuerdo al tipo de proyecto.

### Ejemplo:
```
$ git checkout -b php-app
```

## ChangeLog
