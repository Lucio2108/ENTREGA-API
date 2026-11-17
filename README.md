# Pre-entrega: Extracción y Almacenamiento Seguro de Datos vía API

Script de extracción de datos en Python que realiza peticiones HTTP `GET` a la API pública **OpenF1**, gestionando la configuración de entorno mediante `python-dotenv`, validando códigos de estado HTTP (`try/except`) y almacenando los datos limpios en formato estructurado (`CSV` y `JSON`).

## Estructura del Repositorio
* `extraccion_api.ipynb`: Script principal con la carga de variables de entorno, petición `GET`, manejo de excepciones, limpieza y exportación.
* `data_extracted.csv`: Dataset estructurado resultante en formato CSV.
* `data_extracted.json`: Dataset estructurado resultante en formato JSON.
* `.gitignore`: Archivo de seguridad que excluye el archivo `.env` con credenciales sensibles para evitar exponerlas en el repositorio.

## Configuración e Instalación
1. Clonar este repositorio:
   ```bash
   git clone <URL_DE_TU_REPOSITORIO>
