# Composición de bandas satelitales en ArcGIS

Las imágenes Landsat/Sentinel se encuentran compuestas por diferentes bandas, cada una representada por una porción diferente del espectro electromagnético, para trabajar con la combinación bandas Landsat, primero es necesario comprender las especificaciones de cada banda (acorde al reporte de la [NASA](https://landsat.gsfc.nasa.gov/landsat-8/landsat-8-bands/)), en este caso se describe los valores para **Landsat 8**. 

- Banda 1 (Costera – Aerosoles 0.435 – 0.451 µm, resolución: 30 m).- detecta azules y violetas profundas. La luz azul es difícil de recoger del espacio porque se dispersa fácilmente por pequeños trozos de polvo y agua en el aire, e incluso por las propias moléculas de aire. Esta es una razón por la que las cosas muy distantes (como las montañas en el horizonte) aparecen azules, y por la que el cielo es azul.

- Banda 2 (Azul 0.452 – 0.512 µm, resolución: 30 m).- es muy útil para mapear cuerpos de agua, diferenciación entre suelo y vegetación, diferenciación entre la vegetación conífera y decidua, su desventaja es la susceptibilidad a la dispersión atmosférica, es la banda “más ruidosa”.

- Banda 3 (Verde 0.533 – 0.590 µm, resolución: 30 m).- diseñada para evaluar el vigor de la vegetación sana, diferenciar tipos de rocas y medir la calidad de agua.

- Banda 4 (Rojo 0.636 – 0.673 µm, resolución: 30 m).- permite determinar la absorción de clorofila, por ello muy útil para la clasificación de la cubierta vegetal, agricultura y uso del suelo.

- Banda 5 (Infrarrojo cercano (NIR) 0.851 – 0.879 µm, resolución: 30 m).- mide el infrarrojo cercano, o NIR. Esta parte del espectro es especialmente importante para la ecología porque las plantas saludables lo reflejan – el agua en sus hojas dispersa las longitudes de onda hacia el cielo.

- Banda 6 (Infrarrojo de onda corta 1 (SWIR 1) 1.566 – 1.651 µm, resolución: 30 m).- cubre diferentes cortes del infrarrojo de onda corta o SWIR. Es particularmente útil para diferenciar la tierra húmeda de la seca, y para la geología: rocas y suelos que parecen similares en otras franjas a menudo tienen fuertes contrastes en SWIR.

- Banda 7 (Infrarrojo de onda corta 2 (SWIR 2) 2.107 – 2.294 µm, resolución: 30 m).- tiene aplicaciones similares a la banda 6.

- Banda 8 (Pancromática 0.503 – 0.676 µm, resolución: 15 m).- es la pancromática – o simplemente panchromática – banda. Funciona como una película en blanco y negro: en vez de coleccionar colores visibles por separado, los combina en un solo canal.

- Banda 9 (Cirrus 1.363 – 1.384 µm, resolución: 30 m).- es la que muestra menos, pero es una de las características más interesantes de Landsat 8. Cubre una rebanada muy fina de longitudes de onda: sólo 1370 ± 10 nanómetros. Pocos instrumentos espaciales recogen esta parte del espectro, porque la atmósfera absorbe casi todo.

- Banda 10 ((TIR 1) 10.60 – 11.19 µm, resolución: 100 m).- está en el infrarrojo térmico, o TIR lo que le permite ver el calor. En lugar de medir la temperatura del aire, como lo hacen las estaciones meteorológicas, informan en el suelo mismo, que a menudo es mucho más caliente.

- Banda 11 ((TIR 2) 11.50 – 12.51 µm, resolución: 100 m).- cumple funciones similares a la banda 10.

**NOTA:** 
- Información sobre las misiones Sentinel pueden verse en la página oficial de la [ESA](https://sentinel.esa.int/web/sentinel/home)
- Información sobre las misiones Landsat pueden verse en la página oficial de la [NASA](https://landsat.gsfc.nasa.gov/).

