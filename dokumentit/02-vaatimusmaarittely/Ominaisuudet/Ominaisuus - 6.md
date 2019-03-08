# Ominaisuus - 6


| | |
|:-:|:-:|
| Ominaisuus ID | FT06.1 |
| Sisäänkirjautuminen | Ohjelmisto/laitteisto |
| Kehiittäjä | Projektivastaava/kehittäjä |
| Status | Process |

### Kuvaus

Sisäänkirjautumisen prosessin on oltava vaivatonta, selkeää, intuitiivista ja sen liikuvuus pitää olla osana suunnittelua.


### Ominaisuuteen liittyvät rajaukset, vaatimukset käyttötapaukset

| | |
|:-:|:-:|
| [Profiili - 7](dokumentit/02-vaatimusmaarittely/Profiilit ja sidosryhmät/Profiili-7.md) | Kehittäjä |
| FUNCTIONAL-REQ-C0008 | Kuntouttaja pystyy helposti ymmärtämään miten laite toimii. | 
| PERFORMANCE-REQ-0003 | Näyttöruudun presentaatio on selkeää. | 
| TESTABILITY-REQ-0005 | Ohjelmiston tulee olla selkeä ja helposti ymmärrettävä. | 

### Alustavat käyttäjätarinat (User Storys)
* Ohjelmistosuunnittelijan tavoite on luoda käyttäjäystävällinen käyttöjärjestelmä.
* Ohjelmiston tulee olla intuitiivinen käyttää ja kaikki toiminnot pitää olla sijoiteltu loogisesti.
* Visuaalinen presentaatio selkeää ja toiminnallisuus luotettavaa.
* Kirjautumisessa on tilin luonti, salasananpalautus, istunto ja sessio. Näiden sisällä on myös eri toiminnallisuuksia liikuvuuden takaamiseksi.0

### Käyttöliittymänäkymä/mock 

![](dokumentit/02-vaatimusmaarittely/kuvat/TunnustenLuonti.png)
![](dokumentit/02-vaatimusmaarittely/kuvat/Kirjautuminen.png)
![](dokumentit/02-vaatimusmaarittely/kuvat/PalautaSalasana-1.png)
![](dokumentit/02-vaatimusmaarittely/kuvat/Istunto.png)
![](dokumentit/02-vaatimusmaarittely/kuvat/Sessio.png)


### Testaus / mahdolliset hyväksyntä kriteerit 

| Testitapaus  | Testin lähde  | Kuka vastaa  |
|:-: | :-:|:-:|
| [Testitapaus 2](dokumentit/02-vaatimusmaarittely/Hyväksyntätestit/Hyväksyntätesti-2.md)  | USABILITY-REQ-0001/SYSTEM-REQ-0013 | Kehittäjä/Projektivastaava |