# Depth First ajaline keerukus:

Sügavuse esimese otsimise ajaline keerukus sõltub suuresti sellest, kui sügavale ja laiale algoritm peab minema, et leida sihtpunkt (9).

Kõige halvemal juhul, kui algoritm peab läbima kogu labürindi, on selle ajaline keerukus O(n), kus n on labürindi ruutude arv.

Labürindi läbimisel võib lahenduse leidmiseks kuluda mõttetult aega sellele, et käiakse läbi ruut, mis ei ole mõttekas, see tähendab, et valitakse selline teekond, mis pole lühim vaid lihtsalt minnakse võimalikult sügavale. Kui pole võimalik minna alla, siis vaadtakse kas saab minna üles ja kui saab minnakse üles kuigi võimalik, et mõtekam on hoopis paremale või vasakule.

# Depth First ruumiline keerukus:

Sügavuse esimese otsimise ruumiline keerukus on seotud pöördumisega ja vahemälu kasutamisega.

Iga rekursiivne kutse lisab elemendi teekonna listi ja iga sammuga salvestatakse selle hetkeseisund.

Kuna teed lisatakse tagurpidi (hiljem pööratakse), on vajalik ruum elementide hoidmiseks kahekordne. Seega, ruumiline keerukus on O(n), kus n on labürindi ruutude arv.

Üldiselt on sügavuse esimese otsimise algoritm lihtne ja efektiivne labürindi lahendamisel, kuid see võib olla aeglane suurte labürintide korral. Algoritmi tõhusus sõltub labürindi struktuurist ja suurusest.






