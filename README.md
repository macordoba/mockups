# Pruebas de mockUp Open Api

Pasos de las pureba realizadas de OpenApi

## Crear OpenAPI

1. Instalar VCS
2. installar puglins:
   1. OpenAPI (Swagger) Editor
   2. openapi-lint
   3. Swagger Viewer
3. Ver documentacion Swagger
4. Crear npm proyect _npm create_
5. Crear OpenAPI en formato YML

## Open-API-Mocker

Prueba de herramienta que presenta mockups de un archivo OpenAPI.

1. Installar open-api-maocker _npm i open-api-mocker_
2. Ejecutar _npx open-api-mocker -s XXX.yml -w_
3. Consumir con cliente HTTP los endpoints

## Snapstub

prueba de herramienta que guarda endpoint y los ejecuta en local.

1. Installar open-api-maocker _npm i snapstub_
2. Guardar los endpoint que se quieren con el comando _npx snapstub add http://localhost:5000/XXX --method=get_
3. Ejecutar _npx snapstub start_
4. Consumir con cliente HTTP los endpoints
