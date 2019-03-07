# Ominaisuus - 8


| | |
|:-:|:-:|
| Ominaisuus ID | FT08.1 |
| Tietoturva | Ohjelmisto |
| Kehiittäjä | Kehittäjä |
| Status | Process |

### Kuvaus

Ohjelmiston tulee olla tietoturvallinen. Tiedon tulee tallentua tietokantaan, se ei saa suoraan viitata potilaaseen, työntekijään tai henkilokuntaan ja sen täytyy tehdä varmuuskopiot tallennetuista tiedoista.

### Ominaisuuteen liittyvät rajaukset, vaatimukset käyttötapaukset

| | |
|:-:|:-:|
| [Profiili - 1](https://gitlab.labranet.jamk.fi/m3268---vuosi-2019/ttos0100---2019-toteutus/blob/master/dokumentit/02-vaatimusmaarittely/Profiilit%20ja%20sidosryhm%C3%A4t/Profiili-1.md) | Potilas |
| [Profiili - 2](https://gitlab.labranet.jamk.fi/m3268---vuosi-2019/ttos0100---2019-toteutus/blob/master/dokumentit/02-vaatimusmaarittely/Profiilit%20ja%20sidosryhm%C3%A4t/Profiili-2.md) | Kävelykuntoutusterapeutti |
| [Profiili - 6](https://gitlab.labranet.jamk.fi/m3268---vuosi-2019/ttos0100---2019-toteutus/blob/master/dokumentit/02-vaatimusmaarittely/Profiilit%20ja%20sidosryhm%C3%A4t/Profiili-6.md) | Hakkeri |
| [Profiili - 7](https://gitlab.labranet.jamk.fi/m3268---vuosi-2019/ttos0100---2019-toteutus/blob/master/dokumentit/02-vaatimusmaarittely/Profiilit%20ja%20sidosryhm%C3%A4t/Profiili-7.md) | Kehittäjä |
| [Vaatimus ReqID](CONSTRAINT-REQ-S00003) | Tuote on asiakasturvallinen | 
| [Vaatimus ReqID](CONSTRAINT-REQ-S00004) | Tuote on tietoturvallinen | 
| [Vaatimus ReqID](SECURITY-REQ-0001 ) | Henkilokohtainen tieto tulee turvata instituutin tietoturvastandardien mukaisesti. |
| [Vaatimus ReqID](SECURITY-REQ-0002 ) | Tiedon tulee epäsuorasti viitata henkilöihin potilastunnuksilla, ei henkilötiedoilla. | 
| [Vaatimus ReqID](SECURITY-REQ-0003 ) | Tieto tulee olla kirjoitettavissa, ylikirjoitettavissa ja poistettavissa milloin vain | 
| [Vaatimus ReqID](SECURITY-REQ-0004 ) | Tiedosta tehdään automaattisesti varmuuskopio muualle kaiken varalta. | 
| [Vaatimus ReqID](SECURITY-REQ-0005 ) | Laitteessa tulee olla sisäänkirjautumisvaatimus käyttöä varten. | 
| [Vaatimus ReqID](SECURITY-REQ-0006 ) | Tieto tallentuu tietokantaan, mistä ohjelma hakee sitä kutsusta. | 
| [Vaatimus ReqID](SECURITY-REQ-0007 ) | Tuotteessa tulee olla teollisuustason virustentorjuntaohjelma ja tietoturvaa ylläpitävä ohjelma. | 

### Alustavat käyttäjätarinat (User Storys)
* Ortoosien pitää pystyä tukemaan potilaita tarpeiden mukaan.
* Niiden skaalautuvuus täytyy olla mahdollista.
* Ortooseja pitää pystyä säätämään, muutoin se voi vaarantaa potilaan terveyttä ja turvallisuutta.

### Käyttöliittymänäkymä/mock 

![](dokumentit/02-vaatimusmaarittely/kuvat/ReplaceParts.PNG)


### Testaus / mahdolliset hyväksyntä kriteerit 

| Testitapaus  | Testin lähde  | Kuka vastaa  |
|:-: | :-:|:-:|
| [Testitapaus 2](dokumentit/02-vaatimusmaarittely/Hyväksyntätestit/Hyväksyntätesti-2.md)  | USABILITY-REQ-0001/SYSTEM-REQ-0013 | Kehittäjä/Projektivastaava |