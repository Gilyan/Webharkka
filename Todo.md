# TODO

| Mitä pitää tehdä | Kuka tekee |
|:--|:--|
| Ruokalistat | Joona |
| Käyttäjätunnuksen luontiin tarkistuksia, ääkköset pois regexpillä, duplikaattien tarkistus selainpäähän | Minttu |
| Salasanan / emailin vaihtoon vielä salasanakysely? | Minttu |
| Kirjoituskentän piilotus, jos ei ole kirjauduttu sisälle? | Minttu |
| Käyttäjien ja viestien poistoon hakukentät. | Minttu |

## Mitäs sitä on tullut tehtyä?

### Minttu

| Milloin teki | Mitä teki | Kauanko kesti |
|:--|:--|:--|
| 24.10.2017 | Git-sivusto | 1 h |
| 31.10.2017 | Sivustolle rakennetta | 2 h |
| 7.11.2017 | Sivuston ulkoasu tehty. Tietokanta käyttäjille ja kommenteille tehty. Testikäyttäjiä ja -dataa luotu. comment-core/CommentDb.php, comment-config.php, add_message.php, get_all_users.php, get_messages.php, get_user.php --> Nämä kaikki modifioitu uudelle tietokannalle. | 3 h |
| 8.11.2017 | Sivuston ulkoasun parantelua (.css, div-rakenne) | 1 h |
| 10.11.2017 | login.php saatu kuntoon, kirjautuminen toimii. Eng-vaihtoehto lisätty, tunnistaa kielen selaimen asetuksista. Switch-rakenne luotu, jotta pysytään samalla etusivulla. Mobiilinäkyvyyttä paranneltu. | 4 h |
| 12.11.2017 | Login rikottu. Switch-rakennetta otettu käyttöön. Uuden käyttäjän luominen ja käyttäjän poistaminen saatu valmiiksi. | 8 h |
| 13.11.2017 | Login ja logout saatu toimivaksi. Tehty restaurants.php, jonne Joonalta tulee sisältöä. | 1 h |
| 20.11.2017 | Sääosio saatu toimivaksi. | 3 h |
| 21.11.2017 | Käyttäjätietojen muokkaus  (modify_user.php) tehty. | 4 h |
| 22.11.2017 | Tietokantaan lisätty ravintoloille taulu, jotta jätetyt palautteet voidaan linkittää ravintolaan. Modifioitu get_messages.php ja add_messages.php toimiviksi. Tehty comments.js. Tehty delete_messages.php. | 7 h |
| 23.11.2017 | Poistoihin liittyviä varmistuksia ja korjauksia tehty. Aloitettu haku-kentän teko. Salasanat tähditetty. Salasanoille hashaukset tehty. | 0,5 h |
|  | YHTEENSÄ | 34,5 h |

### Joona

| Milloin teki | Mitä teki | Kauanko kesti |
|:--|:--|:--|
| 2.11.2017 | Layout ja rakenteen suunnittelua | 2 h |
| 7.11.2017 | Ruokalistat ja sääappia | 3 h |
| 7.11.2017 | Autofill weatherapille, muttei vielä toimiva | 3 h |
| 12.11.2017 | weatherapin kanssa painimista | 1 h |
| 13.11.2017 | Tapeltu weatherapin kanssa ilman ratkaisua | 2 h |
| 17.11.2017 | Tapeltu weatherapin kanssa ilman ratkaisua + monet foorumit käyty läpi | 1,5 h |
| 19.11.2017 | Tapeltu weatherapin kanssa ilman ratkaisua + monet foorumit käyty läpi | 1,5 h |
| 21.11.2017 | Ruokalistojen .js ja .php puolen käsittelyä, sodexon listojen haku onnistuu, pitää vielä viilata | 3 h |
| 22.11.2017 | Ruokalistojen haku .js paremmaksi, mutta vielä kömpelö | 2,5 h |
|  | YHTEENSÄ | 19,5 h |
