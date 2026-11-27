DISTINTEC GEO v4 - corrección de conexión CARTO

Corrección:
- Se solucionó un error JavaScript: el helper de selección de elementos se declaraba después de ser utilizado.
- La integración CARTO usa el endpoint oficial de teselas raster Voyager con ?key=API_KEY.
- Se añadió aviso en consola ante errores de carga de teselas.

Pasos:
1. Descomprime el ZIP en una carpeta nueva.
2. Abre index.html.
3. Solicita una NUEVA clave CARTO; la clave mostrada en capturas anteriores debe revocarse.
4. Pega la nueva clave y pulsa Conectar mapa.
5. Si la clave tiene restricciones por dominio, recuerda que al abrir con file:// el referer puede no coincidir. Para producción usa HTTPS y restringe la clave al dominio publicado.

Nota:
- No se incluye ninguna clave API en el archivo.
- Este MVP no incluye un catastro nacional ni backend multiusuario.
- Mantén visible la atribución © OpenStreetMap contributors, © CARTO.
