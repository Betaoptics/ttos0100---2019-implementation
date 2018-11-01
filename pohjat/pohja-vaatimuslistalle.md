# Vaatimukset listana

Tämä malli on varsin käyttökelpoinen, jos lista ei veny kovin pitkäksi


**Asiakasvaatimukset**


| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQCUST0001 | Customer Requirement | Käyttäjänä haluan kirjautua käyttäen Facebook-tunnuksia, ettei tarvise häslätä | [Kirjautuminen ft1](ft1-ominaisuus.md) | 
| REQCUST0002 | Customer Requirement |  | |
| REQCUST0003 | Customer Requirement |  | |
| REQCUST0004 | Customer Requirement |  | |
| REQCUST0005 | Customer Requirement |  | |


**Liiketoiminnan vaatimukset**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQBUS0001 | Business Requirement | Palvelun kirjautuminen tulee olla helppoa, että voimme saavuttaa laajan käyttäjäkunnan = 35% kohderyhmästä | [Kirjautuminen ft1](ft1-ominaisuus.md) | 
| REQBUS0002 | Business Requirement |  | |
| REQBUS0003 | Business Requirement |  | |
| REQBUS0004 | Business Requirement |  | |
| REQBUS0005 | Business Requirement |  | |

**Rajoitukset / Standardit**

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQCONS00000 | Constrain | Palvelun kirjautumisprosessin on noudatettava AC5-2009-käytäntöä  |  |
| REQCONS00001 | Constrain |  |  |
| REQCONS00002 | Constrain |  |  |
| REQCONS00003 | Constrain |  |  |
| REQCONS00004 | Constrain |  |  |
| REQCONS00005 | Constrain |  |  |
| REQCONS00006 | Constrain |  |  |


## Toiminnalliset vaatimukset

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQFUNC0001 | Functional Requirement | Käyttäjänä (Asiakas Profiilit 1-4) voin kirjautua käyttäen Facebook-tunnuksia | [ft1](ft1-ominaisuus.md) | |
| REQFUNC0002 | Functional Requirement | |
| REQFUNC0003 | Functional Requirement | |
| REQFUNC0004 | Functional Requirement | |
| REQFUNC0005 | Functional Requirement | |
| REQFUNC0006 | Functional Requirement | |
| REQFUNC0007 | Functional Requirement | |
| REQFUNC0008 | Functional Requirement | |
| REQFUNC0009 | Functional Requirement | |
| REQFUNC0010 | Functional Requirement | |


## Ei-Toiminnalliset vaatimukset


**Tietoturva**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQSEC0001 | Non-Functional Security | Salasanassa on käytettävä vähintään MD5-tason salausta, koska standardi XY112 sitä edellyttää | [Kirjatutuminen ft1](esimerkki-ft1-ominaisuus.md) |								
| REQSEC0002 | Non-Functional Security | ||
| REQSEC0003 | Non-Functional Security | ||
| REQSEC0004 | Non-Functional Security | ||
| REQSEC0005 | Non-Functional Security | ||
| REQSEC0006 | Non-Functional Security | ||
| REQSEC0007 | Non-Functional Security | ||
| REQSEC0008 | Non-Functional Security | ||
| REQSEC0009 | Non-Functional Security | ||
| REQSEC0010 | Non-Functional Security | ||


**Suorituskyky**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQPERF0000 | Non-Functional Performance | Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (3) sekuntia |  [Kirjatutuminen ft1](esimerkki-ft1-ominaisuus.md) | |	
| REQPERF0001 | Non-Functional Performance | | | |
| REQPERF0002 | Non-Functional Performance | | | |
| REQPERF0003 | Non-Functional Performance | | | |
| REQPERF0004 | Non-Functional Performance | | | |
| REQPERF0005 | Non-Functional Performance | | | |



**Palautuminen**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQ00100 | Non-Functional Recovery |	vesipumppaamon ohjausjärjestelmän käynnistyminen saa kestää max 5 minuuttia, koska viivästys voi pysäyttää ylemmän pumppaamon |	 |							




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