

# Äänestyssovellus

### Käyttötapaus 1: Äänestysten selaaminen

-   **Käyttötapauksen nimi**: Äänestysten selaaminen
-   **Käyttäjät**: Tavalliset käyttäjät, ylläpitäjät
-   **Laukaisija**: Käyttäjä saapuu sovelluksen etusivulle.
-   **Esiehto**: Käyttäjän on oltava kirjautunut sisään.
-   **Jälkiehto**: Käyttäjä näkee listan aktiivisista äänestyksistä.
-   **Käyttötapauksen kulku**:
    1.  Käyttäjä avaa sovelluksen etusivun.
    2.  Sovellus näyttää listan aktiivisista äänestyksistä.
-   **Poikkeuksellinen toiminta**:
    -   Jos äänestyksiä ei ole saatavilla, näytetään viesti "Ei aktiivisia äänestyksiä."

### Käyttötapaus 2: Äänestystilanteen tarkastelu

-   **Käyttötapauksen nimi**: Äänestystilanteen tarkastelu
-   **Käyttäjät**: Tavalliset käyttäjät
-   **Laukaisija**: Käyttäjä valitsee äänestyksen.
-   **Esiehto**: Äänestyksen on oltava aktiivinen.
-   **Jälkiehto**: Käyttäjä näkee valitun äänestyksen nykyisen tilanteen.
-   **Käyttötapauksen kulku**:
    1.  Käyttäjä valitsee äänestyksen etusivulta.
    2.  Sovellus näyttää valitun äänestyksen nykyisen tilanteen, mukaan lukien äänten jakautumisen.
-   **Poikkeuksellinen toiminta**:
    -   Jos äänestystä ei löydy, näytetään virheilmoitus "Äänestystä ei löydy."

### Käyttötapaus 3: Äänestäminen

-   **Käyttötapauksen nimi**: Äänestäminen
-   **Käyttäjät**: Tavalliset käyttäjät
-   **Laukaisija**: Käyttäjä päättää äänestää valitsemassaan äänestyksessä.
-   **Esiehto**: Käyttäjän on oltava kirjautunut sisään ja äänestyksen on oltava aktiivinen.
-   **Jälkiehto**: Käyttäjän ääni on rekisteröity.
-   **Käyttötapauksen kulku**:
    1.  Käyttäjä valitsee äänestyksen.
    2.  Käyttäjä valitsee vaihtoehdon ja äänestää.
    3.  Sovellus vahvistaa, että ääni on rekisteröity.
-   **Poikkeuksellinen toiminta**:
    -   Jos äänestys on päättynyt, näytetään viesti "Äänestys on päättynyt."

### Käyttötapaus 4: Uuden äänestyksen luominen

-   **Käyttötapauksen nimi**: Uuden äänestyksen luominen
-   **Käyttäjät**: Ylläpitäjät
-   **Laukaisija**: Ylläpitäjä haluaa luoda uuden äänestyksen.
-   **Esiehto**: Käyttäjän on oltava kirjautunut sisään ylläpitäjänä.
-   **Jälkiehto**: Uusi äänestys on luotu ja saatavilla äänestettäväksi.
-   **Käyttötapauksen kulku**:
    1.  Ylläpitäjä valitsee "Luo uusi äänestys" -toiminnon.
    2.  Ylläpitäjä syöttää tarvittavat tiedot uudesta äänestyksestä (esim. äänestyksen nimi, vaihtoehdot).
    3.  Äänestys tallennetaan ja julkaistaan sovelluksessa.
-   **Poikkeuksellinen toiminta**:
    -   Jos tiedot ovat puutteelliset, näytetään virheilmoitus ja pyydetään täydentämään puuttuvat tiedot.

### Käyttötapaus 5: Äänestyksen poistaminen

-   **Käyttötapauksen nimi**: Äänestyksen poistaminen
-   **Käyttäjät**: Ylläpitäjät
-   **Laukaisija**: Ylläpitäjä päättää poistaa äänestyksen.
-   **Esiehto**: Käyttäjän on oltava kirjautunut sisään ylläpitäjänä.
-   **Jälkiehto**: Valittu äänestys on poistettu järjestelmästä.
-   **Käyttötapauksen kulku**:
    1.  Ylläpitäjä valitsee poistettavan äänestyksen.
    2.  Ylläpitäjä vahvistaa halunsa poistaa äänestys.
    3.  Sovellus poistaa äänestyksen ja ilmoittaa onnistuneesta toimenpiteestä.
-   **Poikkeuksellinen toiminta**:
    -   Jos äänestystä ei löydy, näytetään virheilmoitus "Äänestystä ei löydy."
