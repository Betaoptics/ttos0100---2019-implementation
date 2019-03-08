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
| [Profiili - 1](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-1.md) | Potilas |
| [Profiili - 2](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-2.md) | Kävelykuntoutusterapeutti |
| [Profiili - 6](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-6.md) | Hakkeri |
| [Profiili - 7](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-7.md) | Kehittäjä |
| CONSTRAINT-REQ-S00003 | Tuote on asiakasturvallinen | 
| CONSTRAINT-REQ-S00004 | Tuote on tietoturvallinen | 
| SECURITY-REQ-0001 | Henkilokohtainen tieto tulee turvata instituutin tietoturvastandardien mukaisesti. |
| SECURITY-REQ-0002 | Tiedon tulee epäsuorasti viitata henkilöihin potilastunnuksilla, ei henkilötiedoilla. | 
| SECURITY-REQ-0003 | Tieto tulee olla kirjoitettavissa, ylikirjoitettavissa ja poistettavissa milloin vain | 
| SECURITY-REQ-0004 | Tiedosta tehdään automaattisesti varmuuskopio muualle kaiken varalta. | 
| SECURITY-REQ-0005 | Laitteessa tulee olla sisäänkirjautumisvaatimus käyttöä varten. | 
| SECURITY-REQ-0006 | Tieto tallentuu tietokantaan, mistä ohjelma hakee sitä kutsusta. | 
| SECURITY-REQ-0007 | Tuotteessa tulee olla teollisuustason virustentorjuntaohjelma ja tietoturvaa ylläpitävä ohjelma. | 

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