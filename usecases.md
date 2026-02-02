## 1. Ylläpitäjä: Luo äänestys

- **Käyttäjät:** Ylläpitäjä  
- **Laukaisija:** Ylläpitäjä valitsee "Luo äänestys"  
- **Esiehto:** Ylläpitäjä on kirjautunut järjestelmään  
- **Jälkiehto:** Uusi äänestys on tallennettu ja näkyy käyttäjille  
- **Käyttötapauksen kulku:** 
    1. Ylläpitäjä valitsee "Luo äänestys"   
    2. Syöttää äänestyksen tiedot: kysymys, vaihtoehdot, aikaraja   
    3. Vahvistaa luomisen  
- **Poikkeuksellinen toiminta:**
  - Jos tiedot puuttuvat tai ovat virheellisiä, järjestelmä näyttää virheilmoituksen

## 2. Ylläpitäjä: Poista äänestys

- **Käyttäjät:** Ylläpitäjä  
- **Laukaisija:** Ylläpitäjä valitsee "Poista äänestys"  
- **Esiehto:** Äänestys on olemassa järjestelmässä  
- **Jälkiehto:** Äänestys poistetaan pysyvästi  
- **Käyttötapauksen kulku:**
  1. Ylläpitäjä valitsee poistettavan äänestyksen listasta  
  2. Vahvistaa poiston  
- **Poikkeuksellinen toiminta:**
  - Jos äänestystä ei löydy, järjestelmä näyttää virheilmoituksen

## 3. Käyttäjä: Selaa äänestyksiä

- **Käyttäjät:** Käyttäjä  
- **Laukaisija:** Käyttäjä avaa "Selaa äänestyksiä"  
- **Esiehto:** Käyttäjä on kirjautunut tai pääsee julkiseen listaan  
- **Jälkiehto:** Käyttäjä näkee kaikkien äänestysten listan  
- **Käyttötapauksen kulku:**
  1. Käyttäjä valitsee "Selaa äänestyksiä"  
  2. Järjestelmä näyttää äänestysten listan  
- **Poikkeuksellinen toiminta:**
  - Jos äänestyksiä ei ole, järjestelmä näyttää ilmoituksen "Ei äänestyksiä saatavilla"


## 4. Käyttäjä: Katso äänestystilanne

- **Käyttäjät:** Käyttäjä  
- **Laukaisija:** Käyttäjä valitsee tietyn äänestyksen  
- **Esiehto:** Äänestys on olemassa  
- **Jälkiehto:** Käyttäjä näkee äänestyksen tulokset tai tilastot  
- **Käyttötapauksen kulku:**
  1. Käyttäjä valitsee äänestyksen listasta  
  2. Järjestelmä näyttää tulokset tai prosenttiosuudet  
- **Poikkeuksellinen toiminta:**
  - Jos tuloksia ei vielä ole, näytetään viesti "Tuloksia ei saatavilla"


## 5. Käyttäjä: Äänestä

- **Käyttäjät:** Käyttäjä  
- **Laukaisija:** Käyttäjä valitsee "Äänestä" äänestyksessä  
- **Esiehto:** Käyttäjä ei ole vielä äänestänyt kyseisessä äänestyksessä  
- **Jälkiehto:** Käyttäjän ääni tallennetaan ja näkyy tuloksissa  
- **Käyttötapauksen kulku:**
  1. Käyttäjä valitsee vaihtoehdon (radio-nappi)  
  2. Vahvistaa valinnan painamalla "Vahvista"  
  3. Järjestelmä tallentaa äänen ja näyttää kiitos-viestin  
- **Poikkeuksellinen toiminta:**
  - Jos käyttäjä yrittää äänestää uudelleen, järjestelmä estää sen ja näyttää ilmoituksen "Olet jo äänestänyt"
