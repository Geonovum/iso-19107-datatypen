# Informele beschrijving

Informatiemodellen bevatten voor het specificeren van waardetypen van attributen onder andere referenties naar zogenaamde primitieve datatypen. Voorbeelden hiervan zijn: 'CharacterString', 'Integer', 'Date', 'GM_Point', 'Boolean'.

Een primitief datatype wordt primitief genoemd omdat het atomair is dat wil zeggen dat het binnen de context van een informatiemodel niet verder opgesplits kan worden in kleinere datatypes. Deze primitieve datatypen zijn buiten een informatiemodel gespecificeerd. Meestal in internationale standaarden. Implementaties in een digitale omgeving en implementatie formaten maken dan gebruik van deze internationaal geldende specificaties.

Meestal zijn primitieve datatypen enkelvoudig, het kan echter voorkomen dat een primitief datatype een structuur heeft en dus tevens een complex datatype is.

Primitieve datatype worden meestal alleen gebruikt voor het specificeren van waardetypen.

Voor Geonovum willen we afpraken maken over het gebruik van primitieve datatypen, welke het zijn, en wat hun definitie is. We doen dit in de vorm van een handreiking omdat we dit relateren aan internationale standaarden. Deze handreikingen plaatsen die datatypen in de context van de informatiemodellering van Geonovum.

Er wordt een opdeling gemaakt op basis van een aantal onderdelen van het raamwerk van Geostandaarden: de MIM standaard, het ISO 19107 geometrie model en een derde groep 'overig':

- [Metamodel voor Informatiemodellering (MIM)](https://geonovum.github.io/mim-datatypen/);

- Geometrische primitieven conform het geometriemodel van ISO 19107 (deze handreiking);

- [Geonovum datatypen](https://geonovum.github.io/geonovum-datatypen/). Overige primitieven die niet in bovenstaande groepen vallen.

In deze handreikingen worden de primitieve datatypen in een MIM 1.2 conform conceptueel informatiemodel gespecificeerd. Tevens wordt er een [[NL-SBB-20241010]] conform begrippenmodel gepubliceerd.


## ISO 19107 Geographic Information - Spatial schema.

De ISO standaard Geographic Information - Spatial schema \[\[ISO19107]] beschrijft het conceptuele model van geometrien. Voorbeelden hiervan zijn punt, lijn, vlak, 3D volumes en ook combinaties hiervan. Onderdeel van de specificaties is onder andere ook de wis- en meetkundige definities hiervan, orientatie in relatie tot onder- en bovenkant, richting van coordinaatreeksen. Al deze specificaties zijn nodig om een eenduidig begrip te hebben en interoperable implementaties te krijgen in technische formaten.

De ISO 19109 is er in verschillende versies, een 2003 versie een een 2019 versie. De 2019 versie is een uitbreiding en op onderdelen een verbeterde versie van de 2003 versie. Ze maakt ook een beter onderscheid tussen een conceptueel niveau met interfaces een toepassing daarvan in datatypen. Toch wordt er voor de handreiking gewerkt met de 2003 versie omdat deze in de toepassing wijder verbreidt is, in zichzelf een toepassing van de 2019 versie is en eenvoudiger inj gebruik is. De 2019 versie is backwards compatible met de 2003 versie.

"Dit document specificeert conceptuele modellen voor het beschrijven van de ruimtelijke kenmerken van geografische entiteiten, en een reeks ruimtelijke bewerkingen die consistent zijn met deze modellen. Het behandelt "vector"-geometrie en -topologie. Het definieert standaard ruimtelijke bewerkingen voor gebruik bij toegang tot, opvraging, beheer, verwerking en gegevensuitwisseling van geografische informatie voor ruimtelijke (geometrische en topologische) objecten. Vanwege de aard van geografische informatie zullen deze geometrische coördinatenstelsels normaal gesproken maximaal drie ruimtelijke dimensies, één temporele dimensie en een willekeurig aantal andere ruimtelijk afhankelijke parameters hebben, afhankelijk van de behoeften van de toepassingen. Over het algemeen zal de topologische dimensie van de ruimtelijke projecties van de geometrische objecten maximaal drie zijn. "



Dit informatiemodel bevat  primitieve datatypen die intern bij Geonovum worden gebruikt.
