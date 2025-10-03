# Pruebas No Funcionales con Artillery

Este proyecto incluye pruebas **no funcionales** (carga, rendimiento y estrés) utilizando la herramienta Artillery.

##  Descripción
Artillery es una herramienta ligera para realizar **pruebas de carga y rendimiento** en APIs y servicios Node.js.  
Permite simular múltiples usuarios concurrentes y obtener métricas de:
- Tiempo de respuesta promedio (latencia).
- Cantidad de requests procesados.
- Throughput (requests por segundo).
- Errores bajo carga o estrés.

## Instalar Artillery de forma global:

npm install -g artillery

## Ejecución de pruebas
### Prueba de carga

artillery run carga.yml

### Prueba de estrés

artillery run estres.yml

### Prueba con POST
artillery run login.yml

