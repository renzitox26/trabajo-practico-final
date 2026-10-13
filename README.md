# TP2 - Análisis de Precios de Combustibles en Argentina

## Integrantes

- Renzo Beribe

## Tema

Análisis de los precios de combustibles en Argentina utilizando datos abiertos.

## Descripción

El proyecto busca analizar la variación de precios de los distintos tipos de combustibles en Argentina según la provincia, localidad, empresa proveedora y fecha de relevamiento.

Se desarrollará una aplicación en Python que permita cargar, validar y procesar datos para obtener estadísticas y realizar comparaciones entre diferentes regiones del país.

## Objetivo

Brindar herramientas para consultar y analizar información relacionada con los precios de combustibles, facilitando la identificación de tendencias y diferencias entre provincias y localidades.

## Fuente de Datos

Datos abiertos sobre precios de combustibles en estaciones de servicio de Argentina.

## Funcionalidades

- Carga de datos desde archivos CSV y JSON.
- Validación de registros.
- Limpieza de datos incorrectos o incompletos.
- Consulta de precios por provincia y localidad.
- Cálculo de precios promedio.
- Comparación de precios entre regiones.
- Generación de estadísticas básicas.

## Estructura Principal

### Clase Combustible

Representa un registro de combustible con los siguientes atributos:

- Provincia
- Localidad
- Tipo de combustible
- Precio
- Fecha

### Herencia

Se implementará una clase base para la carga de datos y clases derivadas para:

- Lectura de archivos CSV.
- Lectura de archivos JSON.

## Validaciones

Se utilizarán expresiones regulares para validar formatos de fecha y otros campos necesarios.

## Resultado Esperado

Obtener una aplicación capaz de analizar los precios de combustibles en Argentina y generar información útil a partir de los datos procesados.
