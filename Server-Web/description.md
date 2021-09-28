# Instalación de un servidor WEB Apache a través de ansible.
## Variable en la sección vars:
| Variable | Descripción |
| --- | --- |
| web_pkg | Paquete de servidor web para instalar. |
| firewall_pkg | Paquete de firewall para instalar. |
| web_service | Servicio web para administrar. |
| firewall_service | Servicio de firewall que se administrará. |
| python_pkg | Paquete requerido para el módulo uri. |
| rule | El nombre del servicio para abrir. |
