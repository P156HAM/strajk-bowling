# strajk-bowling

## Acceptanskriterier

### User Story 1: Boka Datum och Tid

**Positivt Scenario:**
- Som användare vill jag kunna välja datum och tid för min bowlingbokning.
- Systemet bör tillåta mig att välja antalet spelare för bokningen (1 eller fler).
- Efter valet bör systemet visa det valda datumet, tiden och antalet spelare.

**Negativt Scenario:**
- Om inget datum eller tid väljs bör systemet visa ett felmeddelande.
- Systemet bör inte tillåta en bokning utan spelare.

### User Story 2: Välj Skostorlek

**Positivt Scenario:**
- Som användare vill jag kunna välja skostorlek för varje spelare i min bokning.
- Systemet bör visa den valda skostorleken för varje spelare.

**Negativt Scenario:**
- Om ingen skostorlek väljs för en spelare bör systemet visa en standardstorlek.

### User Story 3: Ta Bort Skostorleksfält

**Positivt Scenario:**
- Som användare vill jag kunna ta bort ett skostorleksfält om jag råkar välja ett för många.
- Systemet bör uppdatera visningen för att återspegla det korrekta antalet skostorlekar.

**Negativt Scenario:**
- Systemet bör inte tillåta att ta bort alla skostorleksfält för att säkerställa att minst en spelare har valt en storlek.

### User Story 4: Skicka Bokning och Få Bokningsinformation

**Positivt Scenario:**
- Som användare vill jag kunna skicka min bokning och få en bokningsnummer.
- Systemet bör beräkna och visa det totala beloppet att betala (120 kr/person + 100 kr/bana).

**Negativt Scenario:**
- Om bokningen inte kan behandlas bör systemet visa ett felmeddelande.

### User Story 5: Navigera Mellan Boknings- och Bekräftelsevyn

**Positivt Scenario:**
- Som användare vill jag kunna smidigt navigera mellan boknings- och bekräftelsevyerna.
- Systemet bör uppdatera gränssnittet för att återspegla den aktuella vyn.

**Negativt Scenario:**
- Om det uppstår problem med att navigera mellan vyerna bör systemet visa ett felmeddelande.
