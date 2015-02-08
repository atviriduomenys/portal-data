Šioje repozitorijoje laikomi atviriduomenys.lt portalo duomenys.

Visi duomenys saugomi ``data`` kataloge. ``data`` katalogo struktūra:

``datasets/{dcat:publisher}/{dcat:Dataset}``
    Šį šabloną atitinkančiuose kataloguose saugomos duomenų rinkmenų
    (``dcat:Dataset``) meta duomenys, sugrupuotos pagal duomenų tiekėjus
    (``dcat:publisher``).

``publishers/{foaf:Agent}``
    Šį šabloną atitinkančiuose kataloguose saugomi duomenų tiekėjų
    (``{foaf:Agent)``) meta duomenys.

``projects/{dc:creator}/{foaf:Project}``
    Šį šabloną atitinkančiuose kataloguose saugomi projektų (``foaf:Project``),
    naudojančių atvirus duomenis, meta duomenys ir aprašymai. Projektai
    sugrupuotos pagal projekto kūrėjus (``dc:creator``).


Kiekviename iš šių katalogų meta duomenys aprašomi ``metadata.yaml`` faile.
``metadata.yaml`` faile pateikti duomenys turi atitikti ``schema.yaml`` faile
aprašytą JSON schemą.

``context.jsonld`` failas naudojamas ``metadata.yaml`` turinio transformavimui
į susietų duomenų formatus.
