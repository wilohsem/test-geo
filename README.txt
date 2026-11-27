DISTINTEC GEO v5 - Prospección geográfica automática

Novedades:
- Consulta automática de establecimientos cercanos al obtener la ubicación GPS.
- Búsqueda en OpenStreetMap mediante Overpass API dentro del radio elegido (1 a 50 km).
- Categorías generales: comercio, oficinas y servicios, industria y talleres, alimentos y servicios, salud, turismo y hospedaje y otros establecimientos.
- Pines de resultados con ficha emergente y enlace al registro de OpenStreetMap.
- Filtro por categoría y estado comercial.
- Exportación de resultados a CSV.
- Se conservan las funciones previas: mapa CARTO, GPS, radio, registro manual e importación CSV.

Cómo actualizar GitHub:
1. Abre el repositorio test-geo.
2. Abre index.html y selecciona el lápiz (Edit this file), o usa Add file > Upload files.
3. Reemplaza el index.html existente por el de esta versión.
4. Commit changes.
5. GitHub Pages actualizará el sitio en unos minutos.

Cómo usar:
1. Abre el sitio publicado por HTTPS.
2. Autoriza ubicación y presiona Usar mi ubicación.
3. La aplicación consulta automáticamente OpenStreetMap para el radio seleccionado.
4. Cambia el radio y vuelve a presionar Buscar prospectos cercanos.
5. Usa Exportar resultados para descargar CSV.

Limitaciones y transparencia:
- Los resultados son únicamente los establecimientos y puntos de interés que estén mapeados y etiquetados en OpenStreetMap. No es un catastro oficial ni garantiza todos los negocios existentes.
- La búsqueda es local alrededor del GPS actual, no descarga Chile completo.
- OpenStreetMap puede tener datos incompletos, nombres o direcciones faltantes, y categorías heterogéneas.
- La consulta depende de Overpass API; puede tener demoras, límites de uso o indisponibilidad temporal.
- Respeta la atribución de OpenStreetMap. No hagas consultas repetitivas o masivas; para operación empresarial de alto volumen se recomienda un proveedor de datos/servicio dedicado o instancia propia.
- Los registros descargados no se sincronizan todavía entre vendedores. No hay backend central ni login.
- La clave CARTO se almacena en el navegador local; no la publiques en el repositorio.
