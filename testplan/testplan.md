Testplan – Leerlingadministratiesysteem (EduTech Solutions)
    1. Doel

        Het doel van dit testplan is het verifiëren van de nieuwe functionaliteit waarbij een overzicht van leerlingen rechts in beeld wordt getoond en waarbij gebruikers via een popup de details van een leerling kunnen bekijken.

    2. Scope

        In scope:

            Leerlingenoverzicht rechts in beeld
            Weergave voor- en achternaam
            Popup met leerlingdetails
            Sluiten van popup (kruisje + buiten klikken)
            Toevoegen van leerlingen
            Aanwezigheidsregistratie

        Buiten scope:

            Autorisaties en rollen
            Beveiliging
            Performance en load
            Backend/databases

    3. Testbasis

        Casusbeschrijving
        UI (Home.html)
        Code-inspectie van script.js

    4. Teststrategie

        De teststrategie is gebaseerd op een risico-gebaseerde aanpak.
        Hieronder zijn de belangrijkste risico’s geïdentificeerd.

            | Risico                                       | Impact     
            | ----------------------------------           | ---------   
            | Popup sluit niet (via x of buiten popup)     | Gemiddeld      
            | Leerling niet zichtbaar in lijst             | Hoog     
            | Verkeerde leerlingdetails (lijst & popup)    | Hoog      
            | Geen/verkeerde aanwezigheidsregistratie      | Hoog 

    5. Testomgeving

        Besturingssysteem: Chrome OS (Linux Crostini)
        Browser: Google Chrome
        Applicatie: Lokale HTML/JS applicatie
