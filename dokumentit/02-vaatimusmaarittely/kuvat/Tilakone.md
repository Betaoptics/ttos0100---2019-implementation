# Tilakone

```mermaid
graph TD
    Aloitus-->|Resurssit|Sunnittelu
    Sunnittelu-->|Analyysi|Dokumentaatio
    Dokumentaatio-->|Arkistointi|Työskentely
    Työskentely-->|Pyydetään palautetta|Palautekeskustelu
    Palautekeskustelu-->|Jatketaan työskentelyä palautteen pohjalta|Työskentely
    Työskentely-->|Homma valmis?|Tarkistus
    Tarkistus-->|Hyväksytään|Luovutus
    Luovutus-->|Tuote valmist!|Julkaisu
    Julkaisu-->|Olet vapaa!!|Kotia-kohti
    Palautekeskustelu-->|Jatketaan työskentelyä palautteen pohjalta|Kotia-kohti
    Kotia-kohti-->|Jatkokehitys|Suunnittelu
    Tarkistus-->|Vaatii työstämistä|Työskentely

```