# Datos

Tres datasets del Portal de Datos Abiertos de la Provincia de Buenos Aires. El notebook los lee desde esta carpeta con esta estructura:

```text
datos/
├── establecimientos_salud_publicos/
│   ├── Establecimientos_salud_publicos_alta_al20220721.shp
│   ├── Establecimientos_salud_publicos_alta_al20220721.shx
│   ├── Establecimientos_salud_publicos_alta_al20220721.dbf
│   ├── Establecimientos_salud_publicos_alta_al20220721.prj
│   └── Establecimientos_salud_publicos_alta_al20220721.cpg
├── limites-partidos/
│   └── partidos.geojson
└── proyecciones-poblacion-2010_2025.csv
```

| Dataset | Archivo | Registros | Uso |
|---|---|---:|---|
| [Establecimientos públicos de salud](https://catalogo.datos.gba.gob.ar/dataset/establecimientos-salud) (altas al 21/07/2022) | Shapefile de puntos | 2.840 | Ubicación de cada establecimiento |
| [Límites de partidos](https://catalogo.datos.gba.gob.ar/dataset/partidos) | `partidos.geojson` | 143 | Base territorial (polígonos) |
| [Población, censos 2010 y 2022, y proyecciones 2010-2025](https://catalogo.datos.gba.gob.ar/dataset/poblacion) | `proyecciones-poblacion-2010_2025.csv` | 135 partidos | Población estimada 2025 |

Las dos capas geográficas usan el sistema de referencia EPSG:4326 (WGS 84).

Un shapefile está formado por varios archivos con el mismo nombre; `.shp`, `.shx`, `.dbf` y `.prj` son necesarios para leerlo.

Los datos pertenecen al Gobierno de la Provincia de Buenos Aires y se usan según los términos de su Portal de Datos Abiertos. No contienen información personal.
