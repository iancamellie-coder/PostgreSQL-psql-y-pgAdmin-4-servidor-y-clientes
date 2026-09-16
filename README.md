# Práctica: Verificación del Ecosistema PostgreSQL y Modelo Cliente-Servidor

Este repositorio contiene la documentación y evidencias de la instalación y configuración del entorno de trabajo con PostgreSQL, abarcando tanto la interfaz gráfica como la de comandos.

---

## 1. Conexión vía pgAdmin 4 (GUI)
* **Descripción:** Se estableció conexión exitosa con el servidor local mediante la interfaz gráfica de pgAdmin 4, visualizando el árbol de navegación con la base de datos de trabajo y el dashboard de monitoreo.
* **Evidencia:**
![Evidencia pgAdmin](imagen1.png)

---

## 2. Conexión vía psql (CLI)
* **Descripción:** Se realizó la conexión directa a través de la terminal (SQL Shell - psql) ejecutando el comando `\conninfo` para validar los parámetros de la sesión activa del servidor.
* **Evidencia:**
![Evidencia psql](imagen2.png)

---

## 3. Conclusiones y Diferencias Operativas
* **Interfaz Gráfica (pgAdmin 4):** Facilita la administración visual mediante árboles jerárquicos, gráficos de rendimiento y herramientas interactivas ideales para el desarrollo diario.
* **Línea de Comandos (psql):** Proporciona un entorno ligero y directo, esencial para la gestión avanzada y la conexión eficiente con servidores remotos sin recursos gráficos.
