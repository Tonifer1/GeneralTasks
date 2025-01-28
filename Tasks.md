### 1. Suunnittelu 
Tavoite: Määritellä projektin rakenne, tietokanta, käyttöliittymä, sisältö ja käyttäjäpolut.

## Tasks:
1.1 ER-mallinnus
-Luo tietokannan ER-kaavio.-->Suunnittelukuvasto
-Luo Luokkamalli (Class Diagram)-->Suunnittelukuvasto

1.2 Use Case -Flow
-Luo käyttöliittymän hahmotelma (Power Point).-->Määrittelykuvasto Done
-Luo hahmotelma komponenttien hierarkiasta.(Power Point)-->Suunnittelukuvasto Toni?


1.3 Käyttöliittymän Prototyyppi 
-Määritä tärkeimmät käyttäjäpolut.(Content Map).-->Suunnittelukuvasto Valter? 
-Dokumentoi käyttäjäroolit ja niiden oikeudet.

1.4 Teknologioiden valinta
-Valittu Back-end (Django REST Framework) Done
-Valittu Front-end (React Vite) Done
-Valittu tietokanta  (Microsoft SQL) Done

1.5 Projektin dokumentointi
-Luo kansiorakenne dokumentaatiolle. Done
-Määritä dokumentoinnin standardit. Done

1.6 Ohjelmistot ja Alustat
-Sisällön kerääminen.-->Määrittelykuvasto Done

1.7 Ohjelmointi
-Sisällön kerääminen.-->Määrittelykuvasto Done



### 🖥️ 2. Back-end Ohjelmointi (Vastuuhenkilö: Jani )
Tavoite: Rakentaa palvelinpuolen toiminnot ja API-rajapinnat.

## Tasks:
2.1 Perusta Django-projekti
-Luo perusprojekti ja konfiguroi tietokantayhteys.

2.2 Luo CRUD-toiminnot
-Luo tietokantataulut ja CRUD-rajapinnat.

2.3 Toteuta Autentikointi (JWT)
-Käyttäjätunnistus ja salasanan hashays (MD5 → SHA-256).

2.4 Luo testit palvelimelle
-Perustestit API-endpointeille.

2.5 Dokumentointi
Päivitä README.md back-endin ohjeilla.-->Sprint Back-log
-Kuinka projekti käynnistetään paikallisesti?
-Riippuvuudet ja niiden asentaminen (esim. pip install requirements.txt).
-Tietokannan asetukset.
-Testien suorittaminen.

Luo tekninen dokumentaatio API:sta (esim. Swagger).-->Määrittelykuvasto
-API:n päätepisteet (endpoints).
-HTTP-metodit (GET, POST, PUT, DELETE).
-Pyynnön ja vastauksen mallit (esim. JSON).
-Tarvittavat autentikointimenetelmät.

### 💻 3. Front-end Ohjelmointi (Vastuuhenkilöt: Toni & Valter)
Tavoite: Rakentaa käyttöliittymä, joka kommunikoi Back-endin kanssa.

## Tasks:
3.1 Perusta React Vite -projekti
-Luo perusprojekti ja määritä kansiorakenne.

3.2 Luo pääkomponentti
-Toteuta käyttöliittymän pohja ja navigointi.

3.3 Yhdistä Back-endiin
-Axios-yhteydet API:in.

3.4 Toteuta CRUD-toiminnot käyttöliittymässä
-Tuotteiden hallinta
-Käyttäjien hallinta

3.5 Autentikointi käyttöliittymässä
-Kirjautuminen ja käyttäjänhallinta.

3.6 Dokumentointi
Päivitä README.md front-endin ohjeilla.-->Sprint Back-log
-Kuinka käynnistää React-sovellus paikallisesti.
-Riippuvuuksien asentaminen (esim. npm install).
-Sovelluksen rakennuskomennot (esim. npm run build).
-Ympäristömuuttujien määrittäminen (esim. .env-tiedosto).

Käyttöliittymän dokumentaatio.-->Suunnittelukuvasto
-Front-end-komponenttien hierarkia.
-Navigaatiorakenne (esim. sivut ja niiden väliset yhteydet).
-Keskeiset käyttöliittymäelementit ja niiden käyttötarkoitus.
-Käyttäjäpolut (miten käyttäjä liikkuu sovelluksessa).


### 🔌 4. Integrointi ja Testaus (Vastuuhenkilöt: Toni, Valter, Jani)
Tavoite: Varmistaa, että Back-end ja Front-end toimivat yhdessä saumattomasti.

## Tasks:
4.1 Yhdistä Front-end ja Back-end

Testaa API-kutsut ja tietokantayhteydet.
4.2 Testaa sovellus

4.3 Yksikkötestit
-End-to-end (E2E) testit
-Virheenkorjaus ja optimointi
-Korjaa löydetyt virheet.
-Optimoi suorituskyky.

4.4 Automatisointi
-CI/CD putket

4.5 Dokumentointi
Testausraportit-->Sprint Back-log
-Mitä testattiin (testitapaukset).
-Millaisia tuloksia saatiin (läpäisy/epäonnistuminen).
-Testauksen kattavuus (mitä osia sovelluksesta testattiin).
-Huomioita ja mahdollisia löydettyjä virheitä.

Yhdistetyn sovelluksen dokumentaatio-->Suunnittelukuvasto
-Yleiskatsaus järjestelmän toiminnallisuuksiin (back-end + front-end).
-Sovelluksen tekninen arkkitehtuuri (kuvaa, miten osat, kuten front-end, back-end ja tietokanta, ovat yhteydessä toisiinsa).
-Sovelluksen asentaminen ja käynnistäminen kokonaisuutena.
-Tietoturvaan liittyvät tiedot (esim. autentikointi ja käyttäjän roolien hallinta).


🚀 5. Julkaisu ja Käyttöönotto
Tavoite: Julkaista sovellus ja varmistaa sen toimivuus tuotantoympäristössä.

## Tasks:
5.1 Julkaise Back-end (Azure)

5.2 Julkaise Front-end (Azure)

5.3 Varmista turvallisuusasetukset
-HTTPS
-JWT-tokenit

5.4 Käyttöönotto-ohjeet
 Luo ohjeet ylläpitoon ja käyttöönottoon.-->Määrittelykuvasto
-Tuotantoon liittyviä erityisohjeita.
-Ympäristömuuttujat (esim. API-avaimet, tietokantayhteydet).
-Mitä palveluita Azuresta käytetään (esim. App Service, SQL Database).
-Ylläpito- ja päivitysprosessit.


### 📑 6. Dokumentointi ja Loppuraportti
Tavoite: Koota koko projektin dokumentaatio ja luoda loppuraportti.

## Tasks:
6.1 Kokoa kaikki dokumentit yhteen

6.2 Luo loppuraportti
Projektin eteneminen
Tuntiseuranta
Ongelmat ja ratkaisut

6.3 Arviointi
Tiimin arviointi
Tekninen arviointi


### 🧠 7. Retrospektiivi
Tavoite: Arvioida projektin onnistumista ja tunnistaa kehityskohteet.

## Tasks:
7.1 Pidä retrospektiivipalaveri

Käy läpi, mikä toimi hyvin ja mitä voidaan parantaa.
7.2 Dokumentoi opit
Kirjaa tärkeimmät opit ja vinkit tulevia projekteja varten.

