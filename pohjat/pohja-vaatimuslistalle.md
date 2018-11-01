# Vaatimukset listana

Tämä malli on varsin käyttökelpoinen, jos lista ei veny kovin pitkäksi


# Liiketoiminta/Asiakkaat/Rajoitteet

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


# Järjestelmätason /Ohjelmiston vaatimukset

**SYSTEM REQUIREMENTS**

Tähän kerätään järjestelmän/palvelun vaatimuksia korkealla tasolla. 



**Tekniset vaatimukset**

Tekniset vaatimukset esitetään yleensä erillään ohjelmiston vaatimuksista. Ne liittyvät oleellisen osana
järjestelmävaatimuksiin. Teknisiä vaatimuksia voivat olla esim:

* Suoritusympäristö (Linux, Windows, Pilvi etc)
* Muisti (4GB, 16GB ?)
* Suoritin (Intel/AMD/ARM ?)
* Tietokanta (MySQL, DynamoDB, Orient etc?)
* Ajoalustan ratkaisut JAVA VM, Docker Container ?
 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQ0001 | System Requirement | Kirjatumispalvelulla on oltava itsenäinen kolmannen osapuolen toimittama varmistusjärjestelmä | |
| REQ0002 | System Requirement | Palvelun tärkeimpien palvelujen on oltava vähintään kahdennettu N+1 | |
| REQ0003 | System Requirement | | |
| REQ0004 | System Requirement | | |
| REQ0005 | System Requirement | | |



### Toiminnalliset vaatimukset**

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


### Ei-Toiminnalliset vaatimukset


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
| REQPERF0000 | Non-Functional Performance  | Kirjautuminen on mahdollista yhtäaikaa 100 käyttäjällä (100 request/s) | |								
| REQPERF0001 | Non-Functional Performance  |  | |
| REQPERF0002 | Non-Functional Performance  |  | |
| REQPERF0003 | Non-Functional Performance  |  | |
| REQPERF0004 | Non-Functional Performance  |  | |
| REQPERF0005 | Non-Functional Performance  |  | |


**Käytettävyys**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQUSA0000 | Non-Functional Usability | Käyttöliittymän on toimittava myös ääniohjattuna, koska käyttäjillä saattaa olla näkövammoja |  [Kirjatutuminen ft1](esimerkki-ft1-ominaisuus.md) | |	
| REQUSA0001 | Non-Functional Usability | | | |
| REQUSA0002 | Non-Functional Usability | | | |
| REQUSA0003 | Non-Functional Usability | | | |
| REQUSA0004 | Non-Functional Usability | | | |
| REQUSA0005 | Non-Functional Usability | | | |



**Palautuminen**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQ00100 | Non-Functional Recovery | Kirjautumis-palvelun on käynnistyttävä ensimmäisen palvelun ylösajon aikana |	 |							
| REQ00100 | Non-Functional Recovery | |	 |							


**Testattavuus**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQTEST0000 | Non-Functional Testability | Käyttäjärekisteri on kyettävä palauttamaan alkutilaan ennen testien ajoa  |	 |	
| REQTEST0001 | Non-Functional Testability |  |	 |	
| REQTEST0002 | Non-Functional Testability |  |	 |	
| REQTEST0003 | Non-Functional Testability |  |	 |	
| REQTEST0004 | Non-Functional Testability |  |	 |	
| REQTEST0005 | Non-Functional Testability |  |	 |	


**Turvallisuus**

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQSAFETY0000 | Non-Functional Safety |  Tähän tuotteesen ei voida osoittaa turvallisuus vaatimuksia  |	|	
| REQSAFETY0001 | Non-Functional Safety |   |	|	
| REQSAFETY0002 | Non-Functional Safety |   |	|	
| REQSAFETY0003 | Non-Functional Safety |   |	|	


# Mekaaniikka vaatimukset 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| HWREQ000 | Mechanical Requirement |  |		-	| 	
| VA5001 | Mechanical Requirements | Ohjaamon lukitusmekanisimin on oltava mekaaninen, koska tuote on tarkoitettu arktiseen käyttöön | | 								
| VA3009 | Production Requirement | Asiakas voi valita osalle maalipinnoista eri värit |	|
| VA3015 | Production Requirement | Asiakas ei voi vaihtaa konepeiton väriä ei voi vaihtaa, se on aina musta	|			|				

