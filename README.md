# CTR10K_LAZIO
CTR 10k LAZIO CARTA TECNICA REGIONALE 1:10.000

Dall'ultimo attacco hacker non è più disponibile la carta tecnica regionale 10k della REGIONE LAZIO.

Avendo un vecchio archivio TIFF della CTR 10k regione lazio usato da un programma obsoleto.
Usando QGIS ho riproiettato la CTR grazie ai file word disponibili rinominandoli con la giusta estensione. 

La proiezione non è precisa. Per ridurre l'errore di proiezione è necessario riproiettare tutti i TIFF con il tool "Georeferenziatore" di QGIS. 
Con tale tool è possibile proiettare la CTR sullo shape qu_lazio10k_gb.shp. Bisogna zoommare al massimo i 4 angoli del raster di origine e puntare 
sempre con il massimo zoom possibile i rispettivi angoli del quadro di unione (qu_lazio10k_gb.shp). 
Lo shape appena menzionato qu_lazio10k_gb.shp nel progetto viene mostrato come reticolo ogni quadrante ha un attributo "SEZ" che
corrisponde ai file TIFF presenti nella cartella compressa "CTR".

Riproiettando i TIFF nei rispettivi quadranti del quadro di unione (qu_lazio10k_gb.shp) si riduce l'errore (±0,75mt) adesso è di ± 2,5mt

Si ringrazia per l'aiuto Salvatore Fiandaca e il gruppo Telegram "QGIS.it, il GIS libero" t.me/qgis_it
