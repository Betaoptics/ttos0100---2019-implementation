# Ominaisuus - 4


| | |
|:-:|:-:|
| Ominaisuus ID | FT04.1 |
| Huolto | Laitteisto |
| Kehiittäjä/tekniikko | Kehittäjä/tekniikko |
| Status | Process |

### Kuvaus

Usein laitteita ei suunnitella ensisijaisesti fyysista huollettavuutta ajatellen.
Koska kyseessä on kuitenkin ns. kriittinen järjestelmä, eli laite on tekemisissä ihmisten kanssa, tulee myös fyysisen eli teknisen huollon olla helppoa ja vaivatonta.
Tuotteen eli kävelykuntoutusrobootin tulee olla sillä tavalla suunniteltu, että sen osat eivät ole liian riippuvaisia toisistaan.
Tämä saavutetaan siten, että kävelykuntoutusrobotti suunnitellaan niin, että vian määritys on helppoa, sekä osien korjaaminen, huolto ja vaihtaminen on vaivatonta.
Materiaalin tulee olla turvallista, kevyttä, ei liian kallista ja laitteen olisi hyvä olla helposti purettavissa,
ja eri osioiden pitäisi olla itsenäisiä, muista riippumattomia kokonaisuuksia. Lisäksi laitteen tulisi olla kestävä niin, että sitä ei tarvitse olla jatkuvasti huoltamassa.


### Ominaisuuteen liittyvät rajaukset, vaatimukset käyttötapaukset

| | |
|:-:|:-:|
| [Use Case - 4](dokumentit/02-vaatimusmaarittely/Usecases/Usecase - 1.md) | |
| [Profiili - 8](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-1.md) | |
| [Asiakaspolku - 2](dokumentit/02-vaatimusmaarittely/kuvat/CustomerPath2.PNG) |  | 
| FUNCTIONAL-REQ-C0002 |  | 
| FUNCTIONAL-REQ-C0003 |  | 
| FUNCTIONAL-REQ-C0007 |  | 

### Alustavat käyttäjätarinat (User Storys)

* Terapeutit tarvitsevat luotettavia laitteita, kestävyys on siis tärkeää.
* Olen tekniikko ja usein näitä laitteita huoltaessa saa tuskastella miten työläitä ne on. Toivottavasti se otetaan huomioon suunnittelussa.
* Materiaalit pitäisi ottaa huomioon, niin moni tuote ei toimi koska on säästelty väärissä paikoissa.
* Kävelykuntoutusrobotin huolto on vaikeaa puuhaa. Siksi onkin suotavaa, jos tämä osataan ottaa huomioon suunnittelivaiheessa.
* Sensorien kohdalla on hyvä, jos niitä ei tarvitse koko ajan olla vaihtamassa uusia tilalle.
* Osat on hyvä huoltaa säännöllisesti.
* Laitteet kuluu ja menee rikki, siksi osia joskus pitää korjata ja vaihtaa kokonaan uusiin.

### Käyttöliittymänäkymä/mock 

![](dokumentit/02-vaatimusmaarittely/kuvat/ReplaceParts.PNG)

### Testaus / mahdolliset hyväksyntä kriteerit 

| Testitapaus  | Testin lähde  | Kuka vastaa  |
|:-: | :-:|:-:|
| [Testitapaus 1](dokumentit/02-vaatimusmaarittely/Hyväksyntätestit/Hyväksyntätesti-1.md)  | USABILITY-REQ-0001/SYSTEM-REQ-0013  | Kehittäjä/Projektivastaava |
| | |