# prometheus-deploy
Despliegue de Prometheus para monitorización de servicios

Prometheus (https://prometheus.io/) es una base de datos de time-series que se utiliza muy comunmente para monitorizar sistemas compuestos de varios componentes. 

Actualmente esta instancia de Prometheus monitoriza: 

- Los parámetros básicos de nuestro servidor / servidores
- Traefik (el proxy inverso que se encarga de la gestión de los subdominios y de la terminación de SSL)
- Minio (el servicio de datos de objeto que es el repositorio principal de datos abiertos de citygo.es)

Prometheus se complementará con Grafana para visualizar los datos. Para desplegarlo, ver el repositorio grafana-deploy cuando esté creado. 

Prometheus está configurado para una retención de datos de dos semanas. 
