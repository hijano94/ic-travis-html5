# Integración continúa: Comprobación de html5 válido y Despliegue en surge.sh 

![](https://github.com/hijano94/ic-travis-html5/workflows/CI/badge.svg)

Integración continúa con travis que realiza dos operaciones:

* test: Comprueba que el html5 es válido. Para ello vamos a utilizar (https://github.com/svenkreiss/html5validator)
* deploy: Si la prueba ha sido exitosa se sube al servicio surge.sh (http://surge.sh/)


