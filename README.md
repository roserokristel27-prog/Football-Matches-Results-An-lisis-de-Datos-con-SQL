# ⚽ Football Matches & Results – Análisis de Datos con SQL

Proyecto de análisis de datos enfocado en competiciones y partidos de fútbol mediante el uso de bases de datos relacionales y consultas SQL.  
El proyecto consiste en diseñar una base de datos normalizada, crear su estructura en MySQL y realizar consultas que permitan analizar información sobre equipos, temporadas, árbitros y resultados de los partidos.

---

## 🎯 Objetivo del Proyecto

Diseñar y analizar una base de datos relacional basada en información de partidos de fútbol con el fin de:

- Modelar correctamente la información mediante un esquema normalizado.
- Almacenar datos sobre competiciones, temporadas, equipos, árbitros y partidos.
- Realizar consultas SQL para obtener información relevante sobre el desempeño de equipos y competiciones.
- Analizar patrones en resultados y rendimiento deportivo.

---

## 🛠️ Herramientas utilizadas

- MySQL
- SQL
- Excel (para visualización de resultados)
- Modelado de bases de datos

---

## 🔎 Proceso de análisis

El proyecto se desarrolló en tres etapas principales.

### 1. Modelado de la base de datos

Se analizó el dataset original para identificar las entidades necesarias y construir un modelo relacional normalizado.

Se aplicaron principios de normalización para organizar la información en diferentes tablas relacionadas mediante claves primarias y foráneas.

Las principales entidades identificadas fueron:

- Competitions
- Seasons
- Teams
- Referees
- Matches

Cada tabla fue diseñada con sus respectivos campos, claves primarias (PK) y claves foráneas (FK) para garantizar la integridad de los datos.

---

### 2. Creación de la base de datos

Se desarrolló un script SQL para:

- Crear la base de datos
- Crear las tablas normalizadas
- Definir claves primarias y foráneas
- Establecer restricciones de integridad

Esto permitió estructurar correctamente la información y preparar el sistema para la realización de consultas analíticas.

---

### 3. Consultas y análisis de datos

Una vez creada la estructura de la base de datos, se realizaron diversas consultas SQL para explorar la información almacenada.

Entre los análisis realizados se incluyen:

- Número total de competiciones registradas
- Cantidad de temporadas disponibles en la base de datos
- Número de equipos distintos
- Cantidad de árbitros que han dirigido partidos
- Equipos con mayor número de partidos como local
- Equipos con mayor número de victorias
- Temporada con mayor cantidad de goles anotados
- Árbitro con mayor número de partidos dirigidos
- Promedio de goles anotados por equipo en competiciones específicas

---

## 📊 Resultados obtenidos

A partir del análisis de las consultas SQL se pudieron identificar diversos patrones en los datos de los partidos de fútbol, entre ellos:

- Equipos con mayor participación en partidos como local.
- Equipos con mayor número de victorias en las competiciones analizadas.
- Temporadas con mayor volumen de goles anotados.
- Árbitros con mayor participación en partidos oficiales.
- Diferencias en el rendimiento ofensivo de los equipos según la competición.

Estos resultados permiten explorar tendencias deportivas y comprender mejor el comportamiento de los equipos a lo largo de diferentes temporadas.
