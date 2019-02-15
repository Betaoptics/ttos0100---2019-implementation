# Tilakone

```mermaid
graph TD
    Aloitus-->|Resurssit|Sunnittelu
    Sunnittelu-->|Analyysi|Dokumentaatio
    Sunnittelu-->|Arkistointi|Työskentely
    Työskentely-->|Pyydetään palautetta|Palautekeskustelu
    Palautekeskustelu-->|Jatketaan työskentelyä palautteen pohjalta|Työskentely
    Työskentely-->|Homma valmis?|Tarkistus
    Tarkistus-->|Hyväksytään|Luovutus
    Luovutus-->|Olet vapaa!!|Kotia-kohti
    Tarkistus-->|Vaatii työstämistä|Työskentely

```