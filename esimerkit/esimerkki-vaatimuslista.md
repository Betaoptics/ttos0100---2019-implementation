## Vaatimukset yhtenä listana

* Tämä malli on varsin käyttökelpoinen, jos lista ei veny kovin pitkäksi

| Vaatimustyyppi | 	Vaatimus ID | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| Asiakasvaatimus| 	REQ-00001 |	Käyttäjän on mahdollista kirjautua palveluun käyttäen Facebook-tunnusta, koska se on suurelle osalle asiakkaistamme tuttu |	 Koko systeemi |							
| Palautuminen | REQ-00100 |	vesipumppaamon ohjausjärjestelmän käynnistyminen saa kestää max 5 minuuttia, koska viivästys voi pysäyttää ylemmän pumppaamon |								
| Tietoturva | 	REQ-00120 |	Salasanassa on käytettävä vähintään MD5-tason salausta | [Kirjatutuminen FT1](esimerkki-FT1-ominaisuus.md) |								
| Suorituskyky | REQ-01000 |	 Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (3) sekuntia |  [Kirjatutuminen FT1](esimerkki-FT1-ominaisuus.md) |	
| Toiminnallinen | VA0001 |	Traktori toimitetaan oletuksena aina neljällä pyörällä | [FT1](FT1-ominaisuus.md) |
| Asiakasvaatimus | VA0042 | Kokoluokan LX mallit varustetaan oletuksena vetokoukulla |			
| Rakennevaatimus | VA0053 | Kokoluokan LX mallien etuakselin leveys on minimissään 2 m 5 cm |				
| Rakennevaatimus | VA0054 | Kokoluokan LX-mallin taka-akselin leveys on 2 m 15 cm |		
| Rakennevaatimus | VA0004 | Vetokoukun varaan voidaan kiinnittää maksimissaan 4 kertaa traktorin omaa painoa vastaava kuorma |								
| Suorituskyky | VA9010 | Kokoluokan LX-mallit saavuttavat max 60 km/h nopeuden |								
| Turvallisuus | VA5000 | Laitteen käynnistäminen on mahdollista vain XZ011-mallin virta-avaimella | |					 
| Rakennevaatimus | VA5001 | Ohjaamon lukitusmekanisimin on oltava mekaaninen, koska tuote on tarkoitettu arktiseen käyttöön | | 								
| Asiakasvaatimus | VA3007 | Asiakkaalla on mahdollisuus valita tuotteelle mieleisensä väri | |
| Asiakasvaatimus | VA3008 | Asiakas voi halutessaan valita maalauksen käyttämällä apuna verkkosivuille integroitua virtuaalista “pienoismallia”. |								
| Tuotantovaatimus | VA3009 | Asiakas voi valita osalle maalipinnoista eri värit |	|
| Tuotantovaatimus | VA 3015 | Asiakas ei voi vaihtaa konepeiton väriä ei voi vaihtaa, se on aina musta	|			|				
| Liiketoimitavaatimus | VA9900 | Mallin “X” tuotantokustannuksien on jäätävä alle 45000 €				|			|	
| Toiminnallinen | VA9901 Ajonäytön on näytettävä nopeus 1 km tarkkudella								|  Ajonäyttö |
| Toiminnallinen vaatimus | VA9902	Ajonäytön on vaihduttava peruutustilaan ajosuunnan muuttuessa		|	Ajonäyttö UI |	[FT1](FT3-ominaisuus.md) |				
| Toiminnallinen vaatimus | VA9903	Ajonäytön käyttöliittymä on vikatilanteessa siirryttävä vikamoodiin |	Ajonäyttö UI |					
										