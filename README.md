# Proyecto de Base de Datos Orientada a Grafos para la Gestión de Aeropuertos en América

Este repositorio contiene el proyecto de investigación llamado: *Mejora en la Gestión de Aeropuertos en América mediante Base de Datos NoSQL*. El proyecto desarrolla una base de datos orientadas a grafos, además esta base de datos permite almacenar y consultar datos relacionados con aeropuertos, rutas, aerolíneas, servicios y compañías de seguridad en la industria de la aviación en América.

## Objetivo del Proyecto

El objetivo principal de este proyecto es proporcionar una solución eficiente para la gestión de información de aeropuertos, permitiendo consultas avanzadas basadas en relaciones y análisis de datos en un entorno de base de datos orientada a grafos.

## Características Destacadas

-   **Modelado de Datos en Grafo**: Representación de aeropuertos, rutas, aerolíneas, servicios y compañías de seguridad como nodos y relaciones en un grafo, lo que facilita la visualización de conexiones y relaciones complejas.

-   **Consultas Avanzadas**: Capacidades avanzadas de consulta que permiten realizar análisis en profundidad, como la identificación de patrones de rutas, servicios disponibles en aeropuertos y más.

-   **Plataforma de Base de Datos Orientada a Grafos**: Utilización de OrientDB y ArangoDB como plataformas de bases de datos orientada a grafos.

-   **Comparación de Rendimiento**: Evaluación comparativa de características y rendimiento con otros productos similares para determinar la eficacia de la base de datos en este contexto.

-   **Web Scraping con Python**: Para obtener información actualizada de aeropuertos, se utiliza Python para realizar web scraping y extraer datos de fuentes en línea.

## Estructura del Repositorio

El repositorio se organiza de la siguiente manera:

-   `src/`: Contiene el código fuente de la aplicación que interactúa con la base de datos y las herramientas de web scraping.
    -   `csv/`: Almacena los datos utilizados utilizados en el proyecto, se encuentran los documentos tanto de los vuelos, aerolinea y aeropuertos.
-   `docs/`: Contiene documentación adicional, instrucciones del trabajo.

## Integrantes del Grupo

A continuación se muestra la lista de los integrantes del grupo:

| Nombre del Estudiante  | Correo Electrónico         | Carnet |
|------------------------|----------------------------|--------|
| Manrique Camacho P.    | manrique.camacho@ucr.ac.cr | C01554 |
| Pamela Argueta D.      | pamela.argueta@ucr.ac.cr   | B70644 |
| Josué Flores J         | josue.flores@ucr.ac.cr     | C12912 | 
| Ashly Valerio S.       | ashly.valerio@ucr.ac.cr    | B98045 |
| Johnson Montero S.     | Johnson.Montero@ucr.ac.cr  | C05032 |

## Requisitos de Configuración

Para utilizar este proyecto se necesita:

-   OrientDB 3.1.20 instalado y configurado.
-   ArangoDB 3.11.3 instalado y configurado.
-   Python 3.10.13 instalado y configurado.

## Licencia

Este proyecto se encuentra bajo [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT). Consulté el archivo LICENSE para más detalles.

# Aviso sobre los Links en el Cuaderno de Web Scrapping (.ipynb)

**Nota Importante:**
Este cuaderno IPython (Notebook) ha sido creado con el propósito de demostrar las técnicas de web scraping implementadas en el proyecto "Mejora en la Gestión de Aeropuertos en América mediante Base de Datos NoSQL". Durante el desarrollo de la técnica de web scraping con Selenium, se accedió a sitios web que tenían términos y condiciones que prohibían la inclusión de enlaces directos a sus páginas.

Para cumplir con las políticas éticas y legales, se han eliminado los enlaces específicos de las fuentes de información utilizadas en este cuaderno. Sin embargo, es importante destacar que la omisión de los enlaces específicos puede afectar la funcionalidad del código relacionado con Selenium, ya que estaba diseñado específicamente para la estructura de la página web original.

En lugar de proporcionar enlaces directos, se ha conservado el código relacionado con Selenium para fines de demostración y entendimiento de las técnicas utilizadas. Aunque el código puede no funcionar directamente en un entorno diferente al original, su presencia sirve como un ejemplo educativo y muestra la metodología aplicada en el proyecto.

Agradecemos su comprensión y ética en el uso de este material.

## Mantenimiento de la Transparencia

Este repositorio busca mantener la transparencia en su enfoque metodológico y técnicas utilizadas. La decisión de no incluir enlaces específicos se basa en principios éticos y el respeto a las políticas de los sitios web consultados. Si tiene alguna pregunta o inquietud, no dude en ponerse en contacto con los integrantes del grupo a través de los correos electrónicos proporcionados.

Apreciamos su interés en nuestro proyecto y su compromiso con prácticas éticas en la investigación y el desarrollo.
