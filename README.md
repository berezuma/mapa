Euskarazko WikiMapa

Deskribapena

- Aplikazio hau euskarazko Wikipediako artikulu geolokalizatuak bistaratzen dituen mapa interaktibo bat da. Erabiltzaileei aukera ematen die edukia modu bisual eta geografikoan esploratzeko, Euskal Herrian zein mundu osoan. Proiektua bezero-aldean exekutatzen da osorik, kanpoko API publikoetan kontsultak eginez.

Funtzionalitate nagusiak

- Mapa interaktiboa: Mapa guztiz interaktiboa, Leaflet.js bidez eraikia eta OpenStreetMap-eko datuekin hornitua.
- Artikuluen bilaketa: Bilaketa-barra integratua, idatzi ahala iradokizunak eskaintzen dituena artikuluak erraz aurkitzeko.
- Informazio dinamikoa: Markatzaileetan klik egitean, artikuluaren irudi nagusia eta sarrerako testua kargatzen dira Wikipediaren APIa erabiliz.
- Kategoria bidezko iragazketa: Wikidata-ren SPARQL APIaren aurkako kontsulten bidez, mapako artikuluak kategoriaren arabera (museoak, gazteluak, mendiak, etab.) iragazteko aukera ematen du.
- Kokapen adimenduna: Koordenatu propiorik gabeko artikuluen kasuan, sistemak erlazionatutako entitate geografiko bat bilatzen du Wikidatan (adibidez, udalerria edo jaioterria) eta mapan kokatzen du, erreferentzia gisa.
- Erabiltzailearen kokapena: Geolokalizazio funtzioa, erabiltzailearen uneko kokapena mapan zentratzeko.
- URL partekagarriak: Uneko maparen ikuspegia (zentroa eta zooma) gordetzen duen esteka sortzeko funtzioa.
- Testuinguru geografikoa: Euskal Herriko mugen geruza bat erakusten du mapan, erreferentzia gisa.

Teknologiak

Aplikazioa bezero-aldeko teknologia estandarrak erabiliz eraikita dago, eta ez du zerbitzari-aldeko menpekotasunik.

- Frontend: HTML5, Tailwind CSS, JavaScript (ES6+).
- Mapak: Leaflet.js.

Datu-iturriak eta APIak:

- OpenStreetMap (mapa-basea).
- Euskarazko Wikipedia APIa (geobilaketa, artikuluen laburpenak).
- Wikidata APIa (SPARQL kontsultak).

Erabilera

- Aplikazioa exekutatzeko, fitxategiak web zerbitzari batean ostatatzea eta index.html fitxategia nabigatzaile batetik irekitzea baino ez da beharrezkoa.
- Mapan nabigatu: Mugitu eta zooma egin intereseko guneak aurkitzeko. Markatzaileak automatikoki kargatuko dira mapan mugitzen zaren heinean.
- Informazioa kontsultatu: Egin klik markatzaile batean artikuluaren laburpena ikusteko edo artikulu osora eramango zaituen estekan sakatzeko.
- Artikuluak bilatu: Erabili goiko bilaketa-barra artikulu zehatz bat aurkitzeko.
- Emaitzak iragazi: Erabili iragazki-botoia kategoriak hautatzeko. Kontuan izan iragazkiek zoom maila minimo batetik aurrera funtzionatzen dutela errendimendua optimizatzeko.

Garapena eta Lizentzia

- Garatzailea: Beñat Erezuma
- Laguntzailea: Gemini AA sortzailea.

Datu-iturriak:

- Wikipedia
- OpenStreetMap

Euskal Herriko mugen datuak:

- CodeSyntax eta Ahotsak.eus-en EHmapa proiektua.

Lizentzia:

- Proiektu hau Creative Commons Aitortu-PartekatuBerdin 4.0 lizentziapean argitaratuta dago.
