# Descripción del Proyecto

Este programa utiliza las APIs de Google Maps y TMDB (The Movie Database) para realizar búsquedas y análisis relacionados con negocios y cines. Además, incorpora el uso de coordenadas geográficas específicas para distintos distritos.

---
# Características Principales

## 1. Configuración de APIs
El programa utiliza claves y endpoints de las siguientes APIs:

### Google Maps API:

**Nearby Search:** Para buscar negocios cercanos.

**Distance Matrix:** Para calcular distancias.

**Geolocation:** Para determinar coordenadas.

### TMDB API: Para obtener información de películas y cines.

## 2. Traducción de Tipos de Negocios
Se define un diccionario para traducir tipos de negocios al formato requerido por la API de Google Maps. 

**Ejemplo:**

"restaurantes" → "restaurant"

"cines" → "movie_theater"

## 3. Coordenadas de Distritos

El programa asigna coordenadas específicas a varios distritos de Lima, Perú. 

**Ejemplo:**

La Molina: (-12.087703, -76.937397)

Cercado de Lima: (-12.046374, -77.042793)

# Aplicación del Programa

**Este programa puede utilizarse para:**

Análisis de negocios cercanos (restaurantes, cines, hoteles, etc.)

Cálculo de distancias entre ubicaciones.

Búsqueda de información de películas y cines en TMDB.

# Estructura del Código

**El programa se organiza en las siguientes secciones:**

1. Instalación de dependencias.
   
2. Configuración de APIs.

   
3. Definición de tipos de negocios y coordenadas.

   
4. Funciones para consumir las APIs y realizar análisis.