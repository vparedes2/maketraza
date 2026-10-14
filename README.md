# Diseñador de traza · Water Transfer

Herramienta web para ubicar rebombeos y tanque sobre una traza real de manguera layflat.

**Autor:** Lic. Víctor Javier Paredes · criterios del manual *Water Transfer en Vaca Muerta* (cap. 4).

- Carga KMZ, KML, GPX o CSV (lat, lon, cota) o CSV (km, cota).
- Cotas reales desde internet: SRTM 30 m (OpenTopoData) o Copernicus 90 m (Open-Meteo), automático si el KMZ no trae altura; o desde un CSV de relevamiento.
- Parámetros: caudal, diámetro 12/14/16", C de Hazen-Williams, presión de trabajo, impulsión máxima, succión objetivo, mínimo en crestas, llegada al tanque.
- Modelo 3D de la traza con relieve exagerado, manguera coloreada por presión y estaciones.
- Resultado: estaciones (km, cota, coordenadas, succión, impulsión, potencia, gasoil), perfil piezométrico, planta coloreada por presión, ventosas y desagotes sugeridos, verificaciones, exportación KML y CSV.

Valores estimados de diseño: verificar con la ficha técnica del fabricante y lecturas de campo.

Publicar: Vercel → New Project → Framework *Other*, sin comando de build.
