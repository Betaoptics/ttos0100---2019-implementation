### Testitapaus ID  : TCID1234

  * Testitapauksen suunnittelija: XXXX
  * Testitapauksen hyväksyjä: XXX
  * Luontipvm : X.Y.ABCD

### Päivityshistoria

* versio 0.1 

### Testin kuvaus

**esim 2: Testataan kosteushälytyksen toiminta**

### Testin tavoite

esim 1: Tarkistetaan, että palvelun kuormitusaste ei vaikuta liiaksi kirjautumiseen käytettävään aikaan. Kirjatuminen testataan palvelun ollessa eri kuormitusasteilla. Mittaus tehdään käyttäjärajapinnasta.

esim2: Tarkistetaan, että järjestelmään voidaa asettaa hälytysraja kosteudelle ja että ko hälytysrajan ylittyessä hälytys lähetetään ennalta määriteltyyn numeroon.

### Linkit

  * Vaatimus: [REQID10202]() Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (3) sekuntia   
  * Käyttötapaus: [UC12345]()
  * Ominaisuus: [XXXXX]()

### Alkutilanne (Pre-state): 

esim 1: Palvelu saavutettavissa, Kuormitusgeneraattori asennettu, kirjautumistunnus luotu, ajanmittaus mahdollista

esim 2: Palvelu saavutettavissa, puhelinumero asetettu kosteushälytykseen

### Testiaskeleet (Test Steps)

esim 1:
Toista seuraavat testiaskeleet palvelun kuormitusasteilla 30%, 50% ja 80%

| Testiaskel | Odotettu tulos |
| ---------- | -------------- |
| 1. Aseta palvelun kuormitus | Kuormitus muuttuu asetetuksi |
| 2. Mittaa kirjaantumiseen kuluva aika | |
| 3. Kirjaudu ulos palvelusta | Palvelusta uloskirjautuminen onnistuu |

esim 2:

| Testiaskel | Odotettu tulos |
| ---------- | -------------- |
| 1. Aseta kosteuden hälytysraja 50%:iin | Hälytysraja muuttuu näytöllä |
| 2. Nosta kosteus yli 50%:in | Järjestelmä lähettää hälytyksen käyttäjälle |
| 3. Laske kosteus alle 50%:in | Järjesteläm lähettää hälytyksen peruutuksen |


### Huomioitava testin aikana

esim
 * *Huomioi:* esim. Kirjautumisen aikana näyttö ei välky
 * *Huomioi:* esim. Tervetuloviesti ilmestyy välittömästi (alle 1s)

### Testin lopputilanne (End-State)

esim 1:
 - Jokainen kirjaantuminen onnistui

esim 2:
 - Järjestelmässä ei ole päällä kosteushälytystä

### Testin "tuomio"/tulos (Pass/Fail Criteria):

esim 1:

PASS Kirjaantumiseen kului aikaa =< 3 sekuntia

FAIL Kirjaantumiseen kului aikaa  > 3 sekuntia

esim 2:

PASS: hälytysrajan pystyi asettamaan ja hälytys lähetettiin määriteltyyn numeroon rajan ylittyessä

FAIL: hälytystä ei lähetetty
