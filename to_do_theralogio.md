*Need to have*
----------------------------------------------------------------
**Client**


**Therapeut**
- Acceptatie client uitwerken met groene bevestigingsknop en ook toevoeging aan standaardmail(afspraakvoorstel van Mincht). In afspraakvoorstel ook zetten hoe lang het geldig blijft(default = 5 dagen).

- Client bevestigd afspraak per mail. Standaardmail met betalingsinformatie wanneer client datum bevestigd. Dus bij verschuiven van kolom datum voorgesteld naar kolom in afwachting betaling.
- Melding indien client 7 dagen op voorhand nog niet betaald heeft(dus tijd tot meeting  =< 7dagen).
- Standaardmail met betalingsherinnering sturen naar client via 1 klik.

- Afspraak kunnen annuleren binnen profiel van client door op de afspraak van client te klikken en annulatie. Annulatie mail(standaardmail) wordt automatisch geannuleerd.
- Reschedule van afspraken mogelijk maken door op de afspraak in kwestie te klikken en dan de knop reschedule te kiezen(oude annuleren en nieuwe maken). Standaardmail met reschedule gegevens naar client

- Mail bij verschuiving kolom 3 naar 4 dat de afspraak definitief is(standaardmail).

- 48 en 25 uur op voorhand remindermail(standaardmail) met afspraak herinnering.

- Meer dan dan drie afspraken tegelijk inplannen voor een client kan wel als therapeut(admin check ?)

- Als therapeut afspraak inplannen voor client stuurt een automatische mail met afspraakbevesting naar de client

- Documenten uploaden naar clientenprofiel
- Foto's toevoegen aan profiel?

- Doorklikken naar volgende weken in dashboard om afspraken te zien

**Developer**
- Check DMARC AND DKIM

*Nice to have*
----------------------------------------------------------------
**Client**
- Stripe melding als client x betaald heeft voor y(webhook).
- Automatische switch van kolom 3 naar kolom 4 als de betaling binnen is.
- No show bij klikken op afspraak client met mail naar client dat de gemaakte afspraak niet werd nageleefd met betalingsvoorstel om het consult te betalen in overeenkomst met de algemene voorwaarden.
- Geen afspraken cancellen die al voorbij zijn

**Therapeut**
- Mogelijkheid om extra emailadres toe te voegen aan client(optional_key?)
- Mogelijkheid om een cancellation mail te sturen voor alle afspraken op de huidige dag in geval van ziekte of dergelijke

----------------------------------------------------------------
----------------------------------------------------------------


*Done*
----------------------------------------------------------------
**Client**
- [x] Client kan niet meer dan drie afspraken tegelijk inplannen
- [x] Bij annulatie afspraak door client mail naar therapeut met de de annulatiegegevens(standaardmail)
- [x] Annulatie korter dan 24 uur onmogelijk maken.
- [x] Zelf Afspraak maken enkel mogelijk wanneer client in de kolom in therapie zit, anders niet.
- [x] Boeken voor client als therapeut moet twee knoppen na datumselectie: Reservatie(voor eerste consult, met token?) of boeking voor een client die het zelf niet kan

**Therapeut**
- [x] Archiveringsknop bij client permanent actief laten
- [x] Geen afspraken meer inboeken 48 uur op voorhand
- [x] Zoeken naar clienten op emailadres, telefoon, achternaam, voornaam
- [x] Weergeven hoe lang client al in kolom datum voorgesteld zit. Indien dit langer is dan afspraakvoorstel geldig, melding in knop of in venster rechtsboven

**Developer**
- [x] Notes working again
- [x] GDPR akkoord geven in het intake formulier
- [x] Algemene voorwaarden akkoord geven in intake formulier