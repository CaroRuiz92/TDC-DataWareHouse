# Data Warehouse para The Drinking Company (TDC)

Este proyecto consiste en la construcción de un mini data warehouse para la empresa ficticia The Drinking Company (TDC), desarrollado como trabajo final para la materia Base de Datos II de la Tecnicatura Universitaria en Inteligencia Artificial (TUIA).

## Descripción del Proyecto

El objetivo principal de este proyecto es diseñar e implementar un data warehouse que permita a TDC consolidar y analizar información relevante para la toma de decisiones. Esto incluye la integración de datos provenientes de diversas fuentes internas y externas, su transformación y carga en un esquema optimizado para consultas analíticas.

## Estructura del Repositorio

- **ETL (Extract, Transform, Load)**:
  - `Package.dtsx`: Paquete SSIS que contiene los procesos de extracción, transformación y carga de datos hacia el data warehouse.

- **Proyecto de Visual Studio**:
  - `TP-Final-BaseDeDatos2-TUIA.dtproj`: Archivo del proyecto de Visual Studio que incluye la configuración y componentes utilizados en el desarrollo del data warehouse.

- **Base de Datos**:
  - `TP-Final-BaseDeDatos2-TUIA.database`: Archivo que representa la estructura de la base de datos del data warehouse.

## Herramientas Utilizadas

- **Visual Studio con SQL Server Integration Services (SSIS)**: Para el desarrollo de los procesos ETL y la gestión del proyecto.
- **Microsoft SQL Server Management Studio (SSMS)**: Para la administración y consulta de la base de datos.

## Cómo Ejecutar el Proyecto

1. **Clonar el Repositorio**:

   ```bash
   git clone https://github.com/CaroRuiz92/TDC-DataWareHouse.git
   cd TDC-DataWareHouse
