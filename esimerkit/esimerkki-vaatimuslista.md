## Vaatimukset yhtenä listana

* Tämä malli on varsin käyttökelpoinen, jos lista ei veny kovin pitkäksi

| Vaatimustyyppi | 	Vaatimus ID | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQ00001| Customer Requirement |	Käyttäjän on mahdollista kirjautua palveluun käyttäen Facebook-tunnusta, koska se on suurelle osalle asiakkaistamme tuttu |	 Koko systeemi |							
| REQ00100 | Non-Functional Recovery |	vesipumppaamon ohjausjärjestelmän käynnistyminen saa kestää max 5 minuuttia, koska viivästys voi pysäyttää ylemmän pumppaamon |								
| REQ00120 | Non-Functional Security |	Salasanassa on käytettävä vähintään MD5-tason salausta | [Kirjatutuminen ft1](esimerkki-ft1-ominaisuus.md) |								
| REQ01000 | Non-Functional Performance |	 Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (3) sekuntia |  [Kirjatutuminen ft1](esimerkki-ft1-ominaisuus.md) |	
| VA0001 | Functional Requirement |	Traktori toimitetaan oletuksena aina neljällä pyörällä | [ft1](ft1-ominaisuus.md) |
| VA0042 | Customer Requirement | Kokoluokan LX mallit varustetaan oletuksena vetokoukulla |	Ei käsitellä ohjelmistopuolella, ellei kyse toiminnanohjauksen koodauksesta :) |		
| VA0053 | Mechanical Requirement | Kokoluokan LX mallien etuakselin leveys on minimissään 2 m 5 cm |		-	| 	
| VA0054 | Mechanical Requirement | Kokoluokan LX-mallin taka-akselin leveys on 2 m 15 cm | - |		
| VA0004 | Mechanical Requirement| Vetokoukun varaan voidaan kiinnittää maksimissaan 4 kertaa traktorin omaa painoa vastaava kuorma |								
| VA9010 | Non-Functional Performance  | Kokoluokan LX-mallit saavuttavat max 60 km/h nopeuden |								
| VA5000 | Non-Functional Safety | Laitteen käynnistäminen on mahdollista vain XZ011-mallin virta-avaimella | |					 
| VA5001 | Mechanical Requirements | Ohjaamon lukitusmekanisimin on oltava mekaaninen, koska tuote on tarkoitettu arktiseen käyttöön | | 								
| VA3007 | Customer Requirement | Asiakkaalla on mahdollisuus valita tuotteelle mieleisensä väri | |
| VA3008 | Customer Requirement | Asiakas voi halutessaan valita maalauksen käyttämällä apuna verkkosivuille integroitua virtuaalista “pienoismallia”. |								
| VA3009 | Production Requirement | Asiakas voi valita osalle maalipinnoista eri värit |	|
| VA3015 | Production Requirement | Asiakas ei voi vaihtaa konepeiton väriä ei voi vaihtaa, se on aina musta	|			|				
| VA9900 | Business Goal | Mallin “X” tuotantokustannuksien on jäätävä alle 45000 €				|			|	
| VA9901 | Functional Requirement  |  Ajonäytön on näytettävä nopeus 1 km tarkkudella								|  Ajonäyttö |
| VA9902 | Functional Requirement | Ajonäytön on vaihduttava peruutustilaan ajosuunnan muuttuessa		|	Ajonäyttö UI |	[ft1](FT3-ominaisuus.md) |				
| VA9903 | Functional Requirement | Ajonäytön käyttöliittymä on vikatilanteessa siirryttävä vikamoodiin |	Ajonäyttö UI |					

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|


# Vaatimustyypit:

Asiakasvaat
* Customer Requirement
* 

**Toiminnalliset vaatimukset**

* Functional Requirement 

**Ei-toiminnalliset vaatimukset**

* Non-Functional Security
* Non-Functional Performance
* Non-Functional Safety
* 