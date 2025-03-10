# base documental

## Columnas
A parte del significado evidente de las columnas   `title`  y  `url`, tenemos:

`date`: fecha de publicación del contenido registrado en formato mm/dd/aaaa.

 `knn_class_literal`: es la clase asignada por el clasificador automático (knn) en texto, entendible por humanos.

 `knn_result`: es la clase asignada por el clasificador automático (knn) como una de las 10 guerras de la extrema derecha. 

`knn_score`: es una puntuación que le asignamos a cada registro relacionada con la clase que se le ha asignado de tal manera que cuanto menor es la puntuación más confiable es la clasificación.

## Muestra 
Aunque puedes acceder a una muestra [aquí](https://github.com/pyubero/fr-observatory/blob/main/base_documental/sample_press.csv), la dejamos también por aquí:

 date | knn_class_literal | knn_result | knn_score | title | url 
---|---|---|---|---|---
 04/01/2022 | feminism | 4 | 0.77 | Feministas de Castilla y León se manifiestan este sábado en Valladolid con el lema 'Ni un paso atrás en nuestros derechos' | [url](https://www.eldiario.es/castilla-y-leon/sociedad/feministas-castilla-leon-manifiestan-sabado-valladolid-lema-paso-derechos_1_8882236.html) 
 04/01/2022 | politics | 3 | 0.84 | Tudanca llama a Feijóo a la ""última oportunidad"" para ""detener"" el ""pacto vergonzante"" de PP y Vox en Castilla y León | [url](https://www.eldiario.es/castilla-y-leon/politica/tudanca-llama-feijoo-ultima-oportunidad-detener-pacto-vergonzante-pp-vox-castilla-leon_1_8881714.html) 
 04/02/2022 | feminism | 4 | 0.79 | Feministas de Castilla y León se manifiestan este sábado con el lema 'Ni un paso atrás en nuestros derechos' | [url](https://www.eldiario.es/castilla-y-leon/feministas-castilla-leon-manifiestan-sabado-valladolid-lema-paso-derechos_1_8883554.html) 
 04/04/2022 | politics | 3 | 0.52 | Feijóo condiciona a la “actitud” de Sánchez la posibilidad de un pacto con el Gobierno | [url](https://elpais.com/espana/2022-04-04/feijoo-condiciona-a-la-actitud-de-sanchez-la-posibilidad-de-un-pacto-con-el-gobierno.html) 
 04/04/2022 | poor | 6 | 0.77 | El número de parados en Castilla y León cae en 497 personas en marzo y el número de desempleados baja a 130.153 | [url](https://www.eldiario.es/castilla-y-leon/numero-parados-castilla-leon-cae-497-personas-marzo-numero-desempleados-baja-130-153_1_8886837.html) 
 04/04/2022 | feminism | 4 | 0.93 | Vox considera que un taller de pintar vulvas para visibilizar la sexualidad femenina “pervierte” a las jóvenes | [url](https://elpais.com/sociedad/2022-04-04/vox-considera-que-un-taller-de-pintar-vulvas-para-visibilizar-la-sexualidad-femenina-pervierte-a-los-jovenes.html) 
 04/04/2022 | culture | 1 | 1.17 | El pórtico zamorano al que le sacaron los colores | [url](https://elpais.com/elpais/2022/04/04/paco_nadal/1649107153_537048.html)
 04/06/2022 | feminism | 4 | 0.45 | El PSOE acusa a la Junta de Castilla y León de tratar la violencia de género como una ""violencia de segunda"" | [url](https://www.eldiario.es/castilla-y-leon/politica/psoe-acusa-junta-castilla-leon-tratar-violencia-genero-violencia-segunda_1_8895790.html) 
 04/06/2022 | feminism | 4 | 0.65 | La exvicepresidenta de Castilla y León Rosa Valdeón tacha de ""barbaridad"" la ""concesión política"" del PP a Vox por cuestiones ideológicas ""muy detestables"" | [url](https://www.eldiario.es/castilla-y-leon/politica/exvicepresidenta-castilla-leon-rosa-valdeon-tacha-barbaridad-concesion-politica-pp-vox-cuestiones-ideologicas-detestables_1_8894074.html) 
 04/07/2022 | migrants | 2 | 0.56 | Castilla y León acoge ya a 1.750 refugiados ucranianos y escolariza a 485 niños | [url](https://www.eldiario.es/castilla-y-leon/castilla-leon-acoge-1-750-refugiados-ucranianos-escolariza-485-ninos_1_8898700.html) 
 04/07/2022 | feminism | 4 | 0.85 | Ayuso sugiere a Vox que dé competencias a su vicepresidente en Castilla y León | [url](https://www.eldiario.es/castilla-y-leon/politica/ayuso-sugiere-vox-competencias-vicepresidente-castilla-leon_1_8899091.html) 
 04/07/2022 | politics | 3 | 1.01 | Gallardo (Vox) pide a Ayuso que no ""enturbie"" el pacto en Castilla y León | [url](https://www.eldiario.es/politica/gallardo-vox-pide-ayuso-no-enturbie-pacto-castilla-leon_1_8899799.html) 
 04/08/2022 | politics | 3 | 0.85 | El constructor y empresario de medios en Castilla y León, José Luis Ulibarri, condenado a un año y medio de cárcel por la Gürtel Boadilla | [url](https://www.eldiario.es/castilla-y-leon/tribunales/constructor-empresario-medios-castilla-leon-jose-luis-ulibarri-condenado-ano-medio-carcel-gurtel-boadilla_1_8901060.html)


