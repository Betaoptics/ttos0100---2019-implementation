### Testitapaus ID  : TCID1234

  * Testitapauksen suunnittelija: Tarhytti
  * Testitapauksen hyväksyjä: NarsuMan
  * Luontipvm : 26.06.2015

### Päivityshistoria

* versio 1.2 - 30.03.2016 - Tarhytti - testiaskeleet-kappale muutettu taulukkomuotoon & esimerkkejä lisätty
* versio 1.1 - 22.03.2016 - Tarhytti - pohjaan tehty kosmeettisia muutoksia
* versio 1.0 - 24.12.2015 - Tarhytti - testitapaus hyväksytty
* versio 0.1 - 26.06.2015 - Narsuman - testitapaus luotu

### Testin kuvaus

* esim 1: Tarkista että kirjautumiseen kuluva aika ei ylitä 3 sekunnin rajaa alle palvelun ollessa kuormitettu alle 80 % 

### Testin tavoite

* esim 1: Tarkistetaan, että palvelun kuormitusaste ei vaikuta liiaksi kirjautumiseen käytettävään aikaan. Kirjatuminen testataan palvelun ollessa eri kuormitusasteilla. Mittaus tehdään käyttäjärajapinnasta.

### Linkit

* Vaatimus: [REQ-01000](esimerkki-vaatimuslista.md) Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (3) sekuntia   
* Käyttötapaus: [UC12345](esimerkki-FT1-kayttotapaus.md)
* Ominaisuus: [Ominaisuus FT1](esimerkki-FT1-ominaisuus.md)

### Alkutilanne (Pre-state): 

esim 1: Palvelu saavutettavissa, Kuormitusgeneraattori asennettu, kirjautumistunnus luotu, ajanmittaus mahdollista

### Testiaskeleet (Test Steps)

esim 1:
Toista seuraavat testiaskeleet palvelun kuormitusasteilla 30%, 50% ja 80%

| Testiaskel | Odotettu tulos |
| ---------- | -------------- |
| 1. Aseta palvelun kuormitus | Kuormitus muuttuu asetetuksi |
| 2. Mittaa kirjaantumiseen kuluva aika | |
| 3. Kirjaudu ulos palvelusta | Palvelusta uloskirjautuminen onnistuu |



### Huomioitava testin aikana

esim
 * *Huomioi:* esim. Kirjautumisen aikana näyttö ei välky
 * *Huomioi:* esim. Tervetuloviesti ilmestyy välittömästi (alle 1s)

### Testin lopputilanne (End-State)

esim 1:
 - Jokainen kirjaantuminen onnistui

esim 2:

### Testin "tuomio"/tulos (Pass/Fail Criteria):

esim 1:

PASS Kirjaantumiseen kului aikaa =< 3 sekuntia

FAIL Kirjaantumiseen kului aikaa  > 3 sekuntia


