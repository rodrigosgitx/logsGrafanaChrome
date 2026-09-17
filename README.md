# logsGrafanaChrome

Extensión Chrome Manifest V3 para generar consultas LogQL con los datos de `logsGrafanaSGA` y abrir Grafana Explore en una pestaña nueva.

## Instalación local

1. Abre `chrome://extensions`.
2. Activa **Modo de desarrollador**.
3. Pulsa **Cargar descomprimida**.
4. Selecciona esta carpeta.

La extensión no consulta Loki ni Grafana y no guarda credenciales. Solo genera la URL localmente y usa la sesión que el usuario tenga abierta al abrir la pestaña.
