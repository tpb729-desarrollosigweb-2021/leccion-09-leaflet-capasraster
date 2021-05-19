# Leaflet - capas raster
[Leaflet](https://leafletjs.com/) puede desplegar capas raster en un mapa mediante la clase ImageOverlay.

## Clases del API de Leaflet

### Clase ImageOverlay
La clase [ImageOverlay](https://leafletjs.com/reference-1.7.1.html#imageoverlay) despliega una imagen raster en un mapa.

Ejemplo de uso:

```javascript
// Agregar capa raster
var capa_temperatura = L.imageOverlay("https://raw.githubusercontent.com/tpb729-desarrollosigweb-2021/datos/main/worldclim/bio1_cr.png", 
	[[11.2174518619451575, -87.0981414346102696], 
	[5.4997120253547189, -82.5543713734725770]], 
	{opacity:0.8}
).addTo(mapa);
```

Puede ver un mapa completo con capas raster en [https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-leaflet-capas-raster/](https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-leaflet-capas-raster/).

**Ejercicios**  
1. Agregue una capa raster adicional al mapa del ejemplo. Puede utiilizar las capas disponibles en [https://github.com/tpb729-desarrollosigweb-2021/datos/tree/main/worldclim](https://github.com/tpb729-desarrollosigweb-2021/datos/tree/main/worldclim).
