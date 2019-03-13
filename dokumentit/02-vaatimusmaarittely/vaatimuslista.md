# Vaatimukset listana

# Liiketoiminta/Asiakkaat/Rajoitteet

**Asiakasvaatimukset**


| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| CUSTOMER-REQ-0001 | Customer Requirement | Käyttäjän pitää kokea olonsa turvalliseksi  | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) | 
| CUSTOMER-REQ-0002 | Customer Requirement | Pitää olla hellppokäyttöinen | [Käyttötuki](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 1.md) |
| CUSTOMER-REQ-0003 | Customer Requirement | Laitteen pitää pystyä näyttämään eri kieliä | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |
| CUSTOMER-REQ-0004 | Customer Requirement | Laitteen pitää pystyä näyttämään eri kieliä| [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |


**Liiketoiminnan vaatimukset**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| BUSINESS-REQ-0001 | Business Requirement | Laite ei vahingoita potilaita, ei siis tule lakihaasteita potilasturvallisuuden vaarantamisesta | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) | 
| BUSINESS-REQ-0002 | Business Requirement | Laitteen ohjelmiston ylläpito ei ole liian raskasta taloudellisesti, vakaa ohjelma | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |
| BUSINESS-REQ-0003 | Business Requirement | Laite antaa potilaista tietoa, tämä parantaa työntekijöiden tehokkuutta ja tuottavuutta | [Datan keruu](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| BUSINESS-REQ-0004 | Business Requirement | Ohjelmisto on tietoturvallinen. Näin vältetään tietoturvauhkien lakikanteet | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| BUSINESS-REQ-0005 | Business Requirement | Kävelykuntoutusrobotin huolto ei ole liian kallista ja yleistä. Laite on kestävä | [Käyttötuki](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 1.md)|

**Rajoitukset / Standardit**

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| CONSTRAINT-REQ-S00000 | Constrain | Tuote on ergonominen.  | Kävelykuntoutusterapeutti/Kehittäjä |
| CONSTRAINT-REQ-S00001 | Constrain | Tuote on skaalautuva. | Projektivastaava/Kehittäjä |
| CONSTRAINT-REQ-S00002 | Constrain | Tuotteen on helppokäyttöinen. | Kävelykuntoutusterapeutti/Projektivastaava/Tekniikko/Kehittäjä  |
| CONSTRAINT-REQ-S00003 | Constrain | Tuote on asiakasturvallinen. | Tekniikko/Kehittäjä |
| CONSTRAINT-REQ-S00004 | Constrain | Tuote on tietoturvallinen. | Kehittäjä |
| CONSTRAINT-REQ-S00005 | Constrain | Tuote on siirrettävissä. | Tekniikko |
| CONSTRAINT-REQ-S00006 | Constrain | Tuote on ketterä. | Kävelykuntoutusterapeutti/Kehittäjä |


# Järjestelmätason /Ohjelmiston vaatimukset

**SYSTEM REQUIREMENTS**

Tähän kerätään järjestelmän/palvelun vaatimuksia korkealla tasolla. 



**Tekniset vaatimukset**

Tekniset vaatimukset esitetään yleensä erillään ohjelmiston vaatimuksista. Ne liittyvät oleellisen osana
järjestelmävaatimuksiin. Teknisiä vaatimuksia voivat olla esim:

* OS: Linux, Windows.
* Muisti: Ei tarkennusta, kuitenkin siedettävä koko.
* Suoritin: Ei tarkennusta, toiminnallisesti kuitenkin realistinen.
* Tietokanta: Ei tarkennettu, MySQL todettu hyväksi.
* Ajoalustan ratkaisut: Ei tarkennettu, mahdollisesti XML ja C#.
 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SYSTEM-REQ-0001 | System Requirement | Laitteen tulee soveltua neurologisesti vaikeavammaiselle, erityisesti kävelykuntoutuksen akuuttivaiheeseen. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0002 | System Requirement | Laitteen tulee olla robottiavusteinen, varustettuna mekaanisesti säädettävillä ortooseilla. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0003 | System Requirement | Kävelyrobotin tulee sisältää muun muassa ortoosit, juoksumaton ja painonkevennysjärjestelmän. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0004 | System Requirement | Tarjottavien laitteiden on täytettävä lain terveydenhuollon laitteista ja tarvikkeista ja siihen tehtyjen muutosten sekä viranomaisten asettamat vaatimukset sairaanhoitotarvikkeille ja laitteille.| [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0005 | System Requirement | Tarjottujen tuotteiden tulee täyttää Suomessa voimassaolevat työ- ja käyttöturvallisuusvaatimukset. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0006 | System Requirement | Tarjottujen tuotteiden tulee olla CE-merkittyjä. | [Tekninen huolto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 4.md) |
| SYSTEM-REQ-0007 | System Requirement | Laitteessa on oltava dynaaminen painonkevennysjärjestelmä, jota on voitava käyttää kaukosäätimellä. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |
| SYSTEM-REQ-0008 | System Requirement | Laitteen mukana tulee toimittaa 4 kappaletta valjaita erikokoisille kuntoutujille, kokojen tulee olla S, M, L ja XL tai vastaavat.| [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0019 | System Requirement | Laitteen juoksumatolle on päästävä helposti pyörätuolilla ramppia pitkin. | [Käyttötuki](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 1.md) |
| SYSTEM-REQ-0010 | System Requirement | Laitteen tulee soveltua 130 kg painoiselle henkilölle ja mahdollistaa 200 cm pituisen potilaan painokevennetyn kävelyn. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0011 | System Requirement | Laitteen täytyy soveltua painokevennettyyn kävelymattokuntoutukseen robottiavusteisesti, mutta myös ilman robottia painekevennetyn kävelyn harjoitteluun. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| SYSTEM-REQ-0012 | System Requirement | Laitteessa täytyy olla virtuaalinen biofeedback-ohjelmisto sekä näyttötaulu tai muu vastaava tekninen ratkaisu. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |
| SYSTEM-REQ-0013 | System Requirement | Ohjelmistojen tulee soveltua toimintakyvyltään eritasoisille kuntoutujille. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |
| SYSTEM-REQ-0014 | System Requirement | Laitteella tulee pystyä mittaamaan vähintään seuraavat: kävelymatka, lihasten aktiivisuus, lihasten jäykkyys/vastus, alaraajanivelten liikelaajuudet ja isometriset liikevoimat. | [Datan keruu](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| SYSTEM-REQ-0015 | System Requirement | Laitteessa tulee olla mahdollisuus tallentaa vähintään 10 kuntoutujan mittaustulokset ja harjoitushistoria myöhempää dokumentointia varten (tallenteet tulee saada myös tulostettua). | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) ||
| SYSTEM-REQ-0016 | System Requirement | Laitteella tai lisälaitteella on pystyttävä ohjaamaan mekaanisesti lantion sivusuuntaista liikettä painonsiirron simuloimiseksi sekä lantion kiertoa.| [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| SYSTEM-REQ-0017 | System Requirement | Laitteessa on oltava tietokoneyhteydellä ja voimasensoreilla varustetut alaraajaortoosit. | [Datan keruu](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |



### Toiminnalliset vaatimukset

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| FUNCTIONAL-REQ-C0001 | Functional Requirement | Potilas kokee käytön vaivattomaksi. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md)  |
| FUNCTIONAL-REQ-C0002 | Functional Requirement | Tuote ei vahingoita potilaita. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| FUNCTIONAL-REQ-C0003 | Functional Requirement | Tuote tukee potilaiden raajoja. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| FUNCTIONAL-REQ-C0004 | Functional Requirement | Laite on ketterä. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| FUNCTIONAL-REQ-C0005 | Functional Requirement | Laitetta voidaan säätää ja se skaalautuu. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| FUNCTIONAL-REQ-C0006 | Functional Requirement | Laite pystyy esittämään kuntoutusohjelman selkeästi monelle eri aistille. | [Datan keruu](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| FUNCTIONAL-REQ-C0007 | Functional Requirement | Potilas kokee olonsa turvalliseksi laitteen käytön aikana. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| FUNCTIONAL-REQ-C0008 | Functional Requirement | Kuntouttaja pystyy helposti ymmärtämään miten laite toimii. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |
| FUNCTIONAL-REQ-C0009 | Functional Requirement | Laite ei ole liian kiristävä, raskas tai kömpelö aiheuttaakseen vaaratilanteita. | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) |
| FUNCTIONAL-REQ-C0010 | Functional Requirement | Käyttöä voidaan soveltaa tarvittaessa. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 3.md) |


### Ei-Toiminnalliset vaatimukset


**Tietoturva**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SECURITY-REQ-0001 | Non-Functional Security | Henkilokohtainen tieto tulee turvata instituutin tietoturvastandardien mukaisesti. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |								
| SECURITY-REQ-0002 | Non-Functional Security | Tiedon tulee epäsuorasti viitata henkilöihin potilastunnuksilla, ei henkilötiedoilla. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0003 | Non-Functional Security | Tieto tulee olla kirjoitettavissa, ylikirjoitettavissa ja poistettavissa milloin vain. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0004 | Non-Functional Security | Tiedosta tehdään automaattisesti varmuuskopio muualle kaiken varalta. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0005 | Non-Functional Security | Laitteessa tulee olla sisäänkirjautumisvaatimus käyttöä varten. | [Kijrautuminen](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 6.md)|
| SECURITY-REQ-0006 | Non-Functional Security | Tieto tallentuu tietokantaan, mistä ohjelma hakee sitä kutsusta. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0007 | Non-Functional Security | Tuotteessa tulee olla teollisuustason virustentorjuntaohjelma ja tietoturvaa ylläpitävä ohjelma. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |


**Suorituskyky**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| PERFORMANCE-REQ-0000 | Non-Functional Performance | Logit käyttäjän sessiosta. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |								
| PERFORMANCE-REQ-0001 | Non-Functional Performance | Käyttäjätunnukset vähintään 10 potilaasta. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| PERFORMANCE-REQ-0002 | Non-Functional Performance | Käyttäjätietoa vähintään 10 potilaasta. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| PERFORMANCE-REQ-0003 | Non-Functional Performance | Näyttöruudun presentaatio on selkeää. | [Kirjautuminen](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 6.md) |


**Käytettävyys**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| USABILITY-REQ-0000 | Non-Functional Usability | Käyttöliittymän on toimittava myös ääniohjattuna, koska käyttäjillä saattaa olla näkövammoja. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |	
| USABILITY-REQ-0001 | Non-Functional Usability | Käyttöliittymän on selkeästi esitettävä tieto käyttäjille. Käyttäjä voi olla kuuro. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| USABILITY-REQ-0002 | Non-Functional Usability | Käyttöliittymän tulee pystyä vaihtamaan käytettyä kieltä tarvittaessa. Kaikki eivät ole samankielisiä. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| USABILITY-REQ-0003 | Non-Functional Usability | Käyttöliittymän tulee pystyä vaihtamaan esityksen väriteemaa, jos käyttäjä on värisokea. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |



**Palautuminen**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| RECOVERY-REQ-00100 | Non-Functional Recovery | Tiedoista varmuuskopiot palvelimella | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |							
| RECOVERY-REQ-00100 | Non-Functional Recovery | Tunnukset voidaan palauttaa tai uudelleenkirjoittaa tarvittaessa | [Kirjautuminen](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 6.md) |
| RECOVERY-REQ-00100 | Non-Functional Recovery | Tietoturvan uhatessa tieto voidaan saada palautettua toisesta sijainnista | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |


**Testattavuus**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| TESTABILITY-REQ-0000 | Non-Functional Testability | Käyttäjärekisteri on kyettävä palauttamaan alkutilaan ennen testien ajoa.  | [Kirjautuminen](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 6.md) |	
| TESTABILITY-REQ-0001 | Non-Functional Testability | Laite tulee pystyä käynnistämään ja pysäyttämään tarpeen mukaan testien tekemiseksi. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |	
| TESTABILITY-REQ-0002 | Non-Functional Testability | Laitteen toimivuutta tulee pystyä mittaamaan eri mittareilla, kuten nopeus, vakaus ja perofrmanssi. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |	
| TESTABILITY-REQ-0003 | Non-Functional Testability | Asetukset tulee pystyä nollaamaan ja palauttamaan tarvittaessa. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| TESTABILITY-REQ-0004 | Non-Functional Testability | Laitteen tulee kyetä komplekseihinkin harjoituksiin. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |
| TESTABILITY-REQ-0005 | Non-Functional Testability | Ohjelmiston tulee olla selkeä ja helposti ymmärrettävä. | [Ohjelmisto](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) |	


**Turvallisuus**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SECURITY-REQ-0001 | Non-Functional Security | Henkilokohtainen tieto tulee turvata instituutin tietoturvastandardien mukaisesti. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |								
| SECURITY-REQ-0002 | Non-Functional Security | Tiedon tulee epäsuorasti viitata henkilöihin potilastunnuksilla, ei henkilötiedoilla. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0003 | Non-Functional Security | Tieto tulee olla kirjoitettavissa, ylikirjoitettavissa ja poistettavissa milloin vain. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0004 | Non-Functional Security | Tiedosta tehdään automaattisesti varmuuskopio muualle kaiken varalta. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0005 | Non-Functional Security | Laitteessa tulee olla sisäänkirjautumisvaatimus käyttöä varten. | [Kijrautuminen](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 6.md)|
| SECURITY-REQ-0006 | Non-Functional Security | Tieto tallentuu tietokantaan, mistä ohjelma hakee sitä kutsusta. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |
| SECURITY-REQ-0007 | Non-Functional Security | Tuotteessa tulee olla teollisuustason virustentorjuntaohjelma ja tietoturvaa ylläpitävä ohjelma. | [Tietoturva](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 8.md) |	


# Mekaaniikka vaatimukset 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| MECHANICAL-REQ-000 | Mechanical Requirement | Kävelykuntoutusrobotti antaa sopivasti tukea potilaalle | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) | 	
| MECHANICAL-REQ-001 | Mechanical Requirement | Kävelykuntoutusrobotti on ketterä ja ei vaaranna potilasta käytön aikana | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) | 	
| MECHANICAL-REQ-002 | Mechanical Requirement | Sensorit tai muut osat eivät ole potilaan tiellä tai roiku kävelykuntoutusrobotista | [Asiakasturvallisuus](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 7.md) | 	
| MECHANICAL-REQ-003 | Mechanical Requirement | Sensorit ovat sijoiteltu hyvin vakaasiin ja turvallisiin paikkoihin | [Datan keruu](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 2.md) | 	
| MECHANICAL-REQ-004 | Mechanical Requirement | Laite kestää käytön ja huolto on vaivatonta | [Käyttötuki](dokumentit/02-vaatimusmaarittely/Ominaisuudet/Ominaisuus - 1.md) | 	