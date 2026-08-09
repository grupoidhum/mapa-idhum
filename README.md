# Mapa de investigaciones IDHUM

Visor interactivo de los trabajos de grado y proyectos de investigación del Grupo de
Investigación en Diversidad [más que] Humana (IDHUM), Universidad del Magdalena.

Publicado en: https://USUARIO.github.io/mapa-idhum/

## Contenido del repositorio

- `index.html`: el visor completo. Es un archivo autocontenido: incluye la biblioteca de
  mapas, la base cartográfica vectorial y los datos de los registros. No hace peticiones a
  servidores externos, salvo que se elija una de las capas de teselas del conmutador.

## Cómo actualizar los registros

1. En el visor, pulsar **Exportar CSV** y editar la tabla en una hoja de cálculo.
2. Volver al visor y pulsar **Cargar CSV** para comprobar el resultado sobre el mapa.
3. Pulsar **Guardar JSON** y pegar el contenido descargado dentro del bloque
   `<script type="application/json" id="registros"> … </script>` de `index.html`.
4. Subir el archivo actualizado a este repositorio. El sitio se republica en uno o dos minutos.

## Créditos

- Cartografía original: Johnier Felipe Perafán Ledezma, *Mapa de investigaciones*, en
  *Más que Humanos*, No. 1 (2022), pp. 8-11.
- Base vectorial: Natural Earth 1:10 m (dominio público).
- Biblioteca de mapas: Leaflet 1.9.4 (licencia BSD-2-Clause).
- Capas de teselas opcionales: OpenStreetMap, CARTO, OpenTopoMap.
