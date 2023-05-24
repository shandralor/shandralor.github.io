

*Done*
----------------------------------------------------------------
**Client**
- [x] Client kan niet meer dan drie afspraken tegelijk inplannen
- [x] Bij annulatie afspraak door client mail naar therapeut met de de annulatiegegevens(standaardmail)
- [x] Annulatie korter dan 24 uur onmogelijk maken.
- [x] Zelf Afspraak maken enkel mogelijk wanneer client in de kolom in therapie zit, anders niet.
- [x] Boeken voor client als therapeut moet twee knoppen na datumselectie: Reservatie(voor eerste consult, met token?) of boeking voor een client die het zelf niet kan
- [x] Reverse date

**Therapeut**
- [x] Archiveringsknop bij client permanent actief laten
- [x] Geen afspraken meer inboeken 48 uur op voorhand
- [x] Zoeken naar clienten op emailadres, telefoon, achternaam, voornaam
- [x] Weergeven hoe lang client al in kolom datum voorgesteld zit. Indien dit langer is dan afspraakvoorstel geldig, melding in knop of in venster rechtsboven
- [x] Client bevestigd afspraak per mail. Standaardmail met betalingsinformatie wanneer client datum bevestigd. Dus bij verschuiven van kolom datum voorgesteld naar kolom in afwachting betaling.
- [x] Als therapeut afspraak inplannen voor client stuurt een automatische mail met afspraakbevesting naar de client
- [x] Meer dan dan drie afspraken tegelijk inplannen voor een client kan wel als therapeut(admin check ?)
- [x] Keuze voor vervolgafspraak tussen online en ter plekke
- [x] Acceptatie client uitwerken met groene bevestigingsknop en ook toevoeging aan standaardmail(afspraakvoorstel van Mincht). In afspraakvoorstel ook zetten hoe lang het geldig blijft(default = 5 dagen).
- [x] Boeken als admin kan niet meer in het verleden\
- [x] Bij clients clienten weergeven, gesorteerd op eerste letter voornaam of achternaam, laatste consult
- [x] Clienten bij clients ook een veld laatste afspraak en daar ook kunnen op sorteren
- [x] Reactiveer client bij heraanmelding, archiveerknop bovenaan wordt activeerknop
- [x] Index bij clienten die aangeeft hoeveel actieve clienten er momenteel zijn
- [x] Notities sorteren op nieuwste bovenaan
- [x] Aanmeldingsdatum toevoegen aan intake form als hidden field.
- [x] Kleurenschema voor afspraken huidige week per dag(montessori kleuren per dag)
- [x] Active clients naar excel export
- [x] Mail bij verschuiving kolom 3 naar 4 dat de afspraak definitief is(standaardmail).
- [x] Stripe melding als client x betaald heeft voor y(webhook).
- [x] Automatische switch van kolom 3 naar kolom 4 als de betaling binnen is.
- [x] Kleurenschema voor afspraken huidige week per dag(montessori kleuren per dag)
- [x] Meeting opruimen van intake proposal indien client niet binnen vijf dagen heeft geantwoord
- [x] Melding indien client 7 dagen op voorhand nog niet betaald heeft(dus tijd tot meeting  =< 7dagen).
- [x] Standaardmail met betalingsherinnering sturen naar client via 1 klik.
- [x] 2 dagen op voorhand indien afspraak niet betaald, afspraak opruimen, mail naar client dat afspraak geannuleerd is en afspraakslot kom terug vrij in agenda
- [x] 48 en 25 uur op voorhand remindermail(standaardmail) met afspraak herinnering.
- [x] Change appointment type in the edit modal van de afspraak + mail naar client indien afspraak type wordt veranderd
- [x] Afspraak kunnen annuleren binnen profiel van client door op de afspraak van client te klikken en annulatie. Annulatie mail(standaardmail) wordt automatisch geannuleerd.
- [x] Reschedule van afspraken mogelijk maken door op de afspraak in kwestie te klikken en dan de knop reschedule te kiezen(oude annuleren en nieuwe maken). Standaardmail met reschedule gegevens naar client met zowel gecancelde als nieuwe afspraak.
- [x] No show bij klikken op afspraak client met mail naar client dat de gemaakte afspraak niet werd nageleefd met betalingsvoorstel om het consult te betalen in overeenkomst met de algemene voorwaarden. Client kan niet meer boeken tot betaling gemist consult.

**Developer**
- [x] Notes working again
- [x] GDPR akkoord geven in het intake formulier
- [x] Algemene voorwaarden akkoord geven in intake formulier




*Need to have*
----------------------------------------------------------------
**Client**


**Therapeut**
- Edit client gegevens wanneer nodig

- Meldingen panel met nieuwste melding bovenaan en klikken op melding zet deze als gelezen en de melding verdwijnt uit de lijst

- Documenten uploaden naar clientenprofiel

- Foto's toevoegen aan profiel?

- Doorklikken naar volgende weken in dashboard om afspraken te zien

- Notities kunnen aanpassen na dat deze gemaakt is

- Berekenen op basis van bi-weekly of maandelijks en active hoeveel plaatsen er ingenomen zijn en hoeveel plaatsen er nog vrij zijn gebaseerd op maandelijkse vrije plaatsen

- Create consultation aanpassen met voornaam en naam client

- Betalingsmodule die alle betalingen registreert met prijzenkeuze, zoals excel huidig, inclusief betaalmethode

- Dubbelcheck waarom bij een meeting die niet online is er toch gewisseld wordt als er dezelfde mogelijkheid wordt gekozen


**Developer**
- Check DMARC AND DKIM
- Current events should not be shown if their date is already passed in the admin dashboard upperleft
- Change settings so that all days have possible slots. App iterates through all the days and if the list of slots is empty for that day, the day gets skipped.

*Nice to have*
----------------------------------------------------------------
**Client**



- Geen afspraken cancellen die al voorbij zijn

**Therapeut**
- Mogelijkheid om extra emailadres toe te voegen aan client(optional_key?)
- Mogelijkheid om een cancellation mail te sturen voor alle afspraken op de huidige dag in geval van ziekte of dergelijke

- Functie die in dashboard toont of een afspraak nog bezig is of niet en gemakkelijk toelaat nieuwe afspraak te boeken

