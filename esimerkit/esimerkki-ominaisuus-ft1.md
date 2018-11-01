# Ominaisuus KIRJAUTUMINEN - FT1

* Ominaisuuden vastuuhenkilö: Marko Polo

### Kuvaus

Sed non nisi id ligula interdum mattis. Fusce vel ullamcorper nunc. Nulla pharetra dui ut enim semper semper. Aenean ut leo tortor. Fusce felis nibh, malesuada vitae nibh at, rhoncus feugiat leo. Nam vehicula vitae ligula vitae condimentum. Ut maximus metus nec lorem ultrices elementum.


### Ominaisuuteen liittyvät käyttötapaukset (Use Cases)

Täitä käyttötapauksia voidaan tarvittaessa soveltaa osana ominaisuuteen liittyviä hyväksyntätestejä

* [Use Case 1](esimerkki-uc1-kayttotapaus.md)
* [Use Case 2]()
* [Use Case 3]()


### Alustavat käyttäjätarinat (User Storys)

Ominaisuutta voidaan määritellä käyttäen suoraan User Storyjen muodossa esim.

* #1 Käyttäjänä (Profiili 1-4) haluan voida kirjauta käyttäen Facebook-tunnuksia, koska en halua uusia tunnuksia palveluun
* #2 Näkövammaisena (Profiili 5) käyttäjänä haluan, että voin kirjautua palveluun äänituen avulla
* #3 Käyttäjän toivon, että palvelu kertoo kirjautumisen yhteydessä koska olen viimeksi ollut palvelussa


### Käyttöliittymänäkymä/mock

![](https://openclipart.org/image/300px/svg_to_png/178764/1370010418.png&disposition=attachment)

### Ominaisuuteen liittyvät vaatimukset


| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| REQBUS0001 | Business Requirement | Palvelun kirjautuminen tulee olla helppoa, että voimme saavuttaa laajan käyttäjäkunnan = 35% kohderyhmästä | [Kirjautuminen ft1](ft1-ominaisuus.md) | 
| REQCUST0001 | Customer Requirement | Käyttäjänä haluan kirjautua käyttäen Facebook-tunnuksia, ettei tarvise häslätä | [Kirjautuminen ft1](ft1-ominaisuus.md) | 
| REQ0001 | System Requirement | Kirjatumispalvelulla on oltava itsenäinen kolmannen osapuolen toimittama varmistusjärjestelmä | [Kirjautuminen ft1](ft1-ominaisuus.md) |
| REQCONS00000 | Constrain | Palvelun kirjautumisprosessin on noudatettava AC5-2009-käytäntöä  | [Kirjautuminen ft1](ft1-ominaisuus.md) |
| REQ00100 | Non-Functional Recovery | Kirjautumis-palvelun on käynnistyttävä ensimmäisen palvelun ylösajon aikana | [Kirjautuminen ft1](ft1-ominaisuus.md)	 |							
| REQTEST0000 | Non-Functional Testability | Käyttäjärekisteri on kyettävä palauttamaan alkutilaan ennen testien ajoa  | [Kirjautuminen ft1](ft1-ominaisuus.md)	 |	
| REQUSA0000 | Non-Functional Usability | Käyttöliittymän on toimittava myös ääniohjattuna, koska käyttäjillä saattaa olla näkövammoja |  [Kirjautuminen ft1](ft1-ominaisuus.md) | |	
| REQPERF0000 | Non-Functional Performance | Kirjautuminen on mahdollista yhtäaikaa 100 käyttäjällä (100 request/s) | [Kirjautuminen ft1](ft1-ominaisuus.md) |								
| REQSEC0001 | Non-Functional Security | Salasanassa on käytettävä vähintään MD5-tason salausta, koska standardi XY112 sitä edellyttää | [Kirjautuminen ft1](ft1-ominaisuus.md) |								
| REQFUNC0001 | Functional Requirement | Käyttäjänä (Asiakas Profiilit 1-4) voin kirjautua käyttäen Facebook-tunnuksia | [Kirjautuminen ft1](ft1-ominaisuus.md) |


### Testauksessa huomioitavaa:

| Testitapaus  | Testin peruste/lähde   | 
|:-:|:-:|:-:|
| [Testitapaus 1](esimerkki-ft1-testitapaus.md)  | [Use Case 1](esimerkki-uc1-kayttotapaus.md)  |  |
| [Testitapaus 2](esimerkki-ft1-testitapaus.md)  | [REQPERF0000]() |  |
| [Testitapaus 3](esimerkki-ft1-testitapaus.md)  | [REQTEST0000]() |  |
| [Testitapaus 4](esimerkki-ft1-testitapaus.md)  | [REQ00100]()]  |  |



### Status/Aikataulu/Roadmap

Milloin ominaisuus on tarkoitus julkaista?



