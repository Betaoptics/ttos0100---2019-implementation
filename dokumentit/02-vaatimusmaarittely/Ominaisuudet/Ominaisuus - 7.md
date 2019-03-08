# Ominaisuus - 7


| | |
|:-:|:-:|
| Ominaisuus ID | FT07.1 |
| Säädettävät ortoosit | Laitteisto |
| Kehiittäjä | Projektivastaava/kehittäjä |
| Status | Process |

### Kuvaus

Jalan tuen pitää olla sopiva, ja jalkaa tukevien ortoosien tulee olla säädettävisää.

### Ominaisuuteen liittyvät rajaukset, vaatimukset käyttötapaukset

| | |
|:-:|:-:|
| [Profiili - 1](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-1.md) | Potilas |
| [Profiili - 3](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-1.md) | Kävelykuntoutusterapeutti |
| [Profiili - 7](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-1.md) | Kehittäjä |
| [Profiili - 8](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-1.md) | Tekniikko |
| SYSTEM-REQ-0002 | Laitteen tulee olla robottiavusteinen, varustettuna mekaanisesti säädettävillä ortooseilla. | 
| FUNCTIONAL-REQ-C0003 | Tuote ei vahingoita potilaita. | 
| FUNCTIONAL-REQ-C0005 | Laitetta voidaan säätää ja se skaalautuu. | 

### Alustavat käyttäjätarinat (User Storys)
* Ortoosien pitää pystyä tukemaan potilaita tarpeiden mukaan.
* Niiden skaalautuvuus täytyy olla mahdollista.
* Ortooseja pitää pystyä säätämään, muutoin se voi vaarantaa potilaan terveyttä ja turvallisuutta.

### Käyttöliittymänäkymä/mock 

![](dokumentit/02-vaatimusmaarittely/kuvat/ReplaceParts.PNG)


### Testaus / mahdolliset hyväksyntä kriteerit 

| Testitapaus  | Testin lähde  | Kuka vastaa  |
|:-: | :-:|:-:|
| [Testitapaus 1](dokumentit/02-vaatimusmaarittely/Hyväksyntätestit/Hyväksyntätesti-1.md) | SYSTEM-REQ-0001 | Kehittäjä/Projektivastaava |