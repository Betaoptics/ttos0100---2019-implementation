# Ominaisuus - 5


| | |
|:-:|:-:|
| Ominaisuus ID | FT05.1 |
| Sensorit | Ohjelmisto/laitteisto |
| Kehiittäjä | Projektivastaava/kehittäjä |
| Status | Process |

### Kuvaus

Sensorien tulee pystyä keräämään käyttäjästään dataa. Tuote on siis suunniteltava sillä tavalla, että sensorit eivät ole liian kaukana saadakseen tarkkaa dataa käyttäjästä käytön aikana
Sensorit eivät toisaalta saa olla turvallisuusuhkia, liian riskialtiitta asiakkaille tai rikkoutumiselle, eivätkä ne saa muulla tavoin haitata käyttäjhää käytön aikana. 
Datan pitää päästä tietokantaan, jossta kävelykuntoutusterapeutin kutsumana ohjelmisto pystyy tulostamaan käännettyä dataa ymmärrettävään formaattiin.


### Ominaisuuteen liittyvät rajaukset, vaatimukset käyttötapaukset

| | |
|:-:|:-:|
| [Use Case - 3](dokumentit/02-vaatimusmaarittely/Usecases/Usecase - 3.md) | |
| [Use Case - 4](dokumentit/02-vaatimusmaarittely/Usecases/Usecase - 4.md) | |
| [Profiili - 7](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-7.md) | Kehittäjä |
| [Profiili - 8](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-8.md) | Tekniikko |
| [Asiakaspolku - 1](dokumentit/02-vaatimusmaarittely/kuvat/CustomerPath1.PNG) |  | 
| SYSTEM-REQ-0014 | Laitteella tulee pystyä mittaamaan vähintään seuraavat: kävelymatka, lihasten aktiivisuus, lihasten jäykkyys/vastus, alaraajanivelten liikelaajuudet ja isometriset liikevoimat. | 
| SYSTEM-REQ-0017 | Laitteessa on oltava tietokoneyhteydellä ja voimasensoreilla varustetut alaraajaortoosit. | 
| FUNCTIONAL-REQ-C0006 | Laite pystyy esittämään kuntoutusohjelman selkeästi monelle eri aistille. | 

### Alustavat käyttäjätarinat (User Storys)
* Kehittäjänä tavoite on luoda hyvää jälekä. Sensoreiden käyttö vaatii tarkoin suunniteltua rakennetaa laitteen sisällä ja pinnalla.
* Ei ole hyvä asia jos elintärkeät sensorit eivät kerää dataa käytöstä, antavat harhaanjohtavaa dataa, rikkoutuvat liian helposti tai ovat riskialtiita kävelykunotutusrobotin käyttähjille.
* Sensorien pitää myös pystyä erottamaan millaisesta datasta on kyse.

### Käyttöliittymänäkymä/mock 

![](dokumentit/02-vaatimusmaarittely/kuvat/ReplaceParts.PNG)
![](dokumentit/02-vaatimusmaarittely/kuvat/Sessio.png)

### Testaus / mahdolliset hyväksyntä kriteerit 

| Testitapaus  | Testin lähde  | Kuka vastaa  |
|:-: | :-:|:-:|
| [Testitapaus 1](dokumentit/02-vaatimusmaarittely/Hyväksyntätestit/Hyväksyntätesti-1.md)  | SYSTEM-REQ-0001 | Kehittäjä/Projektivastaava |
| [Testitapaus 2](dokumentit/02-vaatimusmaarittely/Hyväksyntätestit/Hyväksyntätesti-2.md)  | USABILITY-REQ-0001/SYSTEM-REQ-0013 | Kehittäjä/Projektivastaava |