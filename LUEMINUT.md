[Kuvaus englanniksi / In English](README.md)

# Diplomityö

Diplomityöni LaTeX pohja. PDF version työstä löydät [Aaltodoc](https://aaltodoc.aalto.fi/) järjestelmästä tai  varmuuskopioituna [täältä](sci_2019_galkin_ossi.pdf) GitHubista.

## Tiivistelmä työstä ”Järjestelmäintegraation arkkitehtuurin palauttaminen”

Suurilla ja keskisuurilla organisaatioilla on useita liiketoimintaohjelmistoja, kuten asiakkuudenhallinta- ja toiminnanohjausohjelmistoja. Yritysohjelmistot tarvitsevat tietoja toisiltaan, mutta ne harvoin kommunikoivat keskenään käyttövalmiina. Järjestelmäintegraatioalustaa käytetään ohjelmistojen yhdistämiseksi. Liiketoimintaohjelmistojen välisen viestinnän automatisointia kutsutaan orkestroinniksi. Koska järjestelmäintegraatiota käytetään viestinnän toteuttamiseen liiketoimintaohjelmistojen välillä, sitä voidaan käyttää orkestrointikerroksen arkkitehtuurin kartoittamiseen. Yritysten kehittyessä myös niiden käyttämät ohjelmat kehittyvät. Usein niitä ei joko dokumentoida ollenkaan tai dokumentaatio jää päivittämättä. Kaiken kaikkiaan yleinen ongelma on se, että yritys menettää tiedon siitä, mitä ohjelmistoja sillä on ja miten niitä käytetään.

Tässä työssä tarkastellaan ohjelmiston toteuttamista, joka voi automaattisesti palauttaa orkestraatioarkkitehtuurin. Arkkitehtuuri esitetään verkostona, joka mahdollistaa lisäanalyysin ja visualisoinnin. Lisäksi selvitetään: Onko mahdollista käyttää tätä verkostoa yrityksen käyttämien liiketoimintasovellusten tunnistamiseksi. Onko tuotantoympäristö erillään testausympäristöstä. Näiden lisäksi määritetään mitkä järjestelmät yhdistävät kehitys-, testaus- ja tuotantoympäristöjä.

Tuloksista voidaan päätellä, että on mahdollista palauttaa orkestrointiarkkitehtuuri ohjelmallisesti. Orkestrointikerroksen toteutuksen ominaisuuksien vuoksi toteutettu malli suoriutui paremmin kuin yleiset arkkitehtuurin palautusmallit. Palautetun arkkitehtuurin avulla on mahdollista havaita, onko tuotantoympäristö erillinen testausympäristöstä ja tunnistaa liitäntäsolmut. Käytettyjä sovelluksia ei kuitenkaan löydetty modulaarisuuden optimoinnin avulla, joka oli työssä käytetty klusterointi menetelmä.
