# VisitKaunas-Tourism

Duomenys iš KaunasIN - http://visit.kaunas.lt svetainės API (2018 05 30)

raw masyve (kaunas.csv) galima rasti tokius duomenų rinkinius(lokacijos, kontaktiniai duom., aprašai):

Apgyvendinimo įstaigos - viešbučiai, moteliai, kempingai, svečių namai
Kavinės, barai, restoranai, užkandinės
Renginiai, konferencijų salių vietos
Medicinos turizmas
Lankytinos vietos
Muziejai, kultūros įstaigos
Architektūros objektai
etc.


Nuorodos į API (XML): 
GET - http://visit.kaunas.lt/api/v1/ProductCategory
GET - http://visit.kaunas.lt/api/v1/TicProduct

XML transformacija į .csv daryta naudojant XSLT su Saxon XSLT and XQuery processor(saxonb9-1-0-8j).

(JSON):
GET - http://visit.kaunas.lt/api/v1/ProductCategory.json
GET - http://visit.kaunas.lt/api/v1/TicProduct.json
