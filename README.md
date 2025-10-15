# Repte 3: Consum d’Aigua i Pressió Hídrica a l’Àrea Metropolitana de Barcelona

## Tòpic: Medi ambient i sostenibilitat

## Agenda 2030: ODS 6 – Aigua neta i sanejament | ODS 13 – Acció pel clima

Descripció: L’aigua és un recurs natural fonamental per al benestar de la població, el funcionament de l’economia i la sostenibilitat ambiental. Tot i això, a les ciutats, el consum d’aigua s’ha mantingut elevat o fins i tot creixent, malgrat la major conscienciació ciutadana i les campanyes d’estalvi. En un context de canvi climàtic, amb períodes més llargs de sequera, temperatures més altes i precipitacions més irregulars, aquesta situació genera una pressió cada vegada més intensa sobre el sistema hídric.

L’Àrea Metropolitana de Barcelona és un exemple clar d’aquesta tensió: alta densitat de població, activitat econòmica intensa i un ús extensiu del recurs hídric en tots els sectors. Els patrons de consum varien molt segons el moment del dia, l’estació de l’any, l’ús (domèstic, comercial o industrial) i el context climàtic. Això dificulta identificar amb claredat on i quan es produeixen usos excessius o ineficients que podrien ser corregits amb mesures específiques.

## Objectiu i lliurament dades:

Com es distribueix el consum d’aigua a l’Àrea Metropolitana de Barcelona en funció del tipus d’ús, l’estació de l’any, el moment del dia i les condicions ambientals? A partir de les dades disponibles, identifica zones i períodes amb consums elevats o ineficients, construeix indicadors clau per fer-ne seguiment, i proposa recomanacions per una millor gestió del recurs hídric.


## Bases de dades suggerides:
1. Dades de consum d’aigua a la ciutat de Barcelona proporcionades per Aigües de Barcelona (cal registre per obtenir les dades).
2. Aquest enllaç dirigeix al Catàleg de Dades Obertes de l’Agència catalana de l’Aigua (ACA), on es poden consultar i descarregar diversos conjunts de dades relacionats amb la gestió de l’aigua a Catalunya.
3. Dades climatològiques de AEMET.

------------------------------

Hemos descargado el dataset de la opción 1. Sólo traía los datos del municipio de Barcelona y no de todo el Área metropolitana.

Lo hemos cargado en python a un dataframe de pandas y lo hemos exportado a un csv para poderlo analizar en Power BI.

## Campos del dataset:

Secció censal/Sección censal/Census section

Districte/Distrito/District

Municipi/Municipio/Municipality

Data/Fecha/Date

Ús/Uso/Use

Nombre de comptadors/Número de contadores/Number of meters

Consum acumulat (L/dia)/Consumo acumulado (L/día)/Accumulated consumption (L/day)

## Conclusiones datos analizados:

Observamos una caída muy importante del consumo doméstico hacia abril de 2023. Justo coincide con la sequía y con la activación de excepcionalidad de marzo 2023:

https://www.totbarcelona.cat/es/sociedad/los-hogares-de-barcelona-reducen-el-consumo-agua-en-plena-sequia-438255/#:~:text=Cuando%20el%20marzo%20del%202023,litro%20menos%20que%20en%20marzo

01/11/2023 10:20
"Cuando el marzo del 2023 se activó la fase de excepcionalidad, que actualmente todavía está en vigor, los hogares de Barcelona tenían un consumo acumulado de 103 litros por persona y día. Este consumo solo contabiliza el consumo doméstico de agua sin tener en cuenta el agua que usan la industria, los comercios y los servicios municipales. Si se suman estos otros usos, según los mismos datos del consistorio, a septiembre del 2023 lo consumo de agua total en Barcelona es de 173 litros por persona y día, un litro menos que en marzo."



