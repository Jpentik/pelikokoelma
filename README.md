# Pelikokoelma

- Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen.
- Käyttäjä pystyy lisäämään, muokkaamaan ja poistamaan pelejä.
- Käyttäjä näkee sovellukseen lisätyt pelit.
- Käyttäjä pystyy etsimään pelejä hakusanalla.
- Sovelluksessa on käyttäjäsivut, jotka näyttävät jokaisesta käyttäjästä tilastoja ja käyttäjän lisäämät pelit.
- Käyttäjä pystyy valitsemaan pelille yhden tai useamman lisätiedon/luokittelun (esim. pelikonsoli, kunto, tuotekoodi, fyysinen/digitaalinen, halutaan ostaa/myydä)
- Käyttäjä pystyy lähettämään viestejä toisille käyttäjille.
- Käyttäjä pystyy lukemaan saamansa viestit ja vastaamaan viesteihin.

# Asennus- ja käyttöohjeet 3.8.2025

- Juurihakemistossa virtuaaliympäristön luonti ja käynnistys:
`python3 -m venv venv`
`source venv/bin/activate`
- Flask-kirjaston asennus:
`pip install flask`
- Sovelluksen käynnistys:
`flask run`
- Sovelluksen sulkeminen:
`Control+C`
- Virtuaaliympäristöstä poistuminen:
`deactivate`

Sovelluksen toiminnot:
- Kirjautumissivu:
`http://127.0.0.1:5000/`
- Rekisteröitymissivu:
- `http://127.0.0.1:5000/register` 