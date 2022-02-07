# CTR 10k REGIONE LAZIO

CARTA TECNICA REGIONALE 1:10.000

## Cosa c'è in questo repository
Questo è l'archivio dei dati aperti cartografici delle della Regione Lazio, non più disponibili a causa attacco hacker, in formato GeoTIFF e disponibili con la stessa licenza originaria.

### Quadro unione 10k
Lo shapefile `qu_lazio10k_gb.shp` è il quadro di unione, ogni quadrante ha un attributo "SEZ" che
corrisponde al nome dei file `GTiff` presenti nella cartella "CTR".

## Storia del dataset
Vecchio archivio `tif + tiw` della CTR 10k regione lazio usato da un programma obsoleto. Le CTR 10k presenti in questo repositori sono stati convertiti da `tif + tiw` in `GTiff` con `EPSG:3004` (dopo aver cambiato estensione al `world file` da `tiw` a `tfw`):

```
gdal_translate -a_srs EPSG:3004 -of GTiff -co COMPRESS=LZW input.tif output.tif
```

## Ringraziamenti
Si ringrazia per l'aiuto Salvatore Fiandaca e il gruppo Telegram "QGIS.it, il GIS libero" t.me/qgis_it
