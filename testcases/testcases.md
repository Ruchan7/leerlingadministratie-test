Requirements 
ID | Omschrijving                                                                                                                    | Bron
-- | ------------------------------------------------------------------------------------------------------------------------------- | --------- 
R1.| Rechts wordt een overzicht van alle leerlingen getoond met voor- en achternaam.                                                 | Casus
R2.| Klik op een leerling in de lijst opent een popup met gedetailleerde informatie in een tabel.                                    | Casus
R3.| Popup kan gesloten worden via kruisje of door buiten de popup te klikken.                                                       | Casus
R4.| Toevoegen leerling: via het formulier worden leerlinggegevens opgeslagen en zichtbaar in de lijst.                              | UI
R5.| Aanwezigheid: status aanwezig/afwezig kan per leerling geregistreerd worden en wordt getoond in het aanwezigheids-overzicht.    | UI


Test
ID  | Req.| Omschrijving                              | Stappen                                      | Verwacht resultaat                  | Resul. | Bewijs
--- | ----|-------------------------------------------| -------------------------------------------- | ----------------------------------- | ------ | ---
T01 | R1. | Leerlingenlijst toont voor- en achternaam | Open de applicatie en bekijk de lijst rechts | Namen worden correct weergegeven    | Pass   | B01
T02 | R4. | Toevoegen leerling verschijnt in lijst    | Vul formulier in en klik op Toevoegen        | Nieuwe leerling verschijnt in lijst | Pass   | B02
T03 | R2. | Klik op leerling opent popup              | Klik op naam in lijst                        | Popup met details verschijnt        | Pass   | B03
T04 | R3. | Popup sluit via kruisje                   | Klik op X in popup                           | Popup sluit                         | Pass   | B04
T05 | R3. | Popup sluit door buiten popup te klikken  | Klik buiten popup                            | Popup sluit                         | Fail   | B05
T06 | R2. | Gegevens wordt correct getoond            | Voeg leerling toe, open popup, check gegevens| Waardes exact zoals ingevoerd       | Fail   | B06
T07 | R5. | Aanwezigheidsstatus wordt opgeslagen      | Kies leerling + status → Bijwerken           | Status verschijnt in overzicht      | Pass   | B07

Opmerking
ID  | Omschrijving     
--- | -----------------------------                         
T05 | Popup blijft open ondanks er buiten de popup wordt geklikt 
T06 | Aan de huisnummer wordt er een extra 1 toegevoegd (10 -> 101) 
