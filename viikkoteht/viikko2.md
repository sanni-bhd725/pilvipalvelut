## GitHub Actions

GitHub Actions tarjoaa automatisoidun Jekyll-sivuston rakentamisen ja julkaiseminen GitHub Pagesiin. Sitä käyttämällä kehitystyö tehostuu ja sen avulla varmistetaan myös jatkossa sivuston nopea päivittäminen aina, kun koodia muutetaan. Sivusto päivittyy repositoryn tietystä haarasta, joten muita haaroja voi hyödyntää kehitystyöhön, jota ei ole vielä tarkoitus julkaista.

## CI/CD-putkiston rakentaminen web-sovellukselle

Continuous Integration / Continuous Deployment tarkoittaa sivuston tai sovelluksen jatkuvaa, katkeamatonta integrointia sekä toimitusta/julkaisua. CI/CD-putkisto voi sisältää useita vaiheita ja työkaluja, joilla saadaan automatisoitua kehitys, testaus ja julkaisu. Näiden rakentaminen vähentää manuaalisten työvaiheiden myöhempää tarvetta.

Versionhallintaan voisi käyttää esimerkiksi laajalti käytössä olevaa Git-versionhallintaa. Dockeria voisi käyttää eriyttämään sovelluksen osat toisistaan sekä toistettavien kehitysympäristöjen luontiin. Esim. Jenkinsilla, GitHub Actionsilla, CircleCI:llä voisi määrittää automaattisia testejä, jotka ajetaan jokaisen koodiin tehtävän muutoksen yhteydessä. Sovelluksen voi rakentaa käyttäen esim. Webpackia, jolla sovelluksen saa paketoitua. GitHub Actionsilla voi määrittää automatisoidun julkaisuprosessin, joka siirtää sovelluksen tuotantoon heti onnistuneen testauksen jälkeen. Integroitujen monitorointi- ja lokipalveluiden avulla voi seurata web-sovelluksen suorituskykyä, havaita ongelmia sekä reagoida niihin nopeasti.
