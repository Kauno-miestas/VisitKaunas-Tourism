# VisitKaunas-Tourism

Duomenys iš KaunasIN - http://visit.kaunas.lt svetainės API (2018 05 30)<br>

Raw masyve (kaunas.csv) galima rasti tokius duomenų rinkinius(lokacijos, kontaktiniai duom., aprašai):
<br><br>
Apgyvendinimo įstaigos - viešbučiai, moteliai, kempingai, svečių namai<br>
Kavinės, barai, restoranai, užkandinės<br>
Renginiai, konferencijų salių vietos<br>
Medicinos turizmas<br>
Lankytinos vietos<br>
Muziejai, kultūros įstaigos<br>
Architektūros objektai<br>
etc.<br>
<br>
Papildomi CSV failai suskirstyti pagal XML kategorijas
<br>
Nuorodos į API (XML): <br>
GET - http://visit.kaunas.lt/api/v1/ProductCategory<br>
GET - http://visit.kaunas.lt/api/v1/TicProduct<br>
XML transformacija į CSV daryta naudojant XSLT su Saxon XSLT and XQuery processor(saxonb9-1-0-8j).<br>
<br>
(JSON):
GET - http://visit.kaunas.lt/api/v1/ProductCategory.json<br>
GET - http://visit.kaunas.lt/api/v1/TicProduct.json
