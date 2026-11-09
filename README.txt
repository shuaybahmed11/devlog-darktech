GITHUB PAGES DEVLOG — HANDLEIDING
=================================

WAT ZIT ER IN DEZE MAP?
- index.html       De homepage met overzicht van de weken
- week-01.html    Pagina voor week 1
- week-02.html    Pagina voor week 2
- week-03.html    Pagina voor week 3
- week-04.html    Pagina voor week 4
- css/style.css   Alle vormgeving
- js/main.js      Klein script voor het mobiele menu

1. EERST JE DEVLOG AANPASSEN
Open de map in Visual Studio Code.
Open index.html en pas de titel, introductie en projectbeschrijving aan.
Open daarna week-01.html t/m week-04.html.
Vervang de voorbeeldteksten en reflectie door jouw eigen werk.
Je kunt een weekpagina kopiëren om extra weken toe te voegen.

AFBEELDINGEN TOEVOEGEN
Maak een map 'images' aan in de hoofdmap.
Zet je afbeelding daarin, bijvoorbeeld images/week1-screenshot.png.
Voeg op een weekpagina op de gewenste plek toe:
<img src="images/week1-screenshot.png" alt="Screenshot van mijn project" class="content-image">
Je kunt voor .content-image deze CSS toevoegen aan css/style.css:
.content-image { width: 100%; height: auto; border-radius: 8px; margin: 16px 0; }

2. TESTEN OP JE COMPUTER
Dubbelklik op index.html om de website in je browser te openen.
Controleer of de weekkaarten werken en of de vormgeving goed wordt weergegeven.
Een internetverbinding is nodig voor de externe Google Fonts; zonder internet gebruikt de site een standaardlettertype.

3. ONLINE ZETTEN MET GITHUB PAGES
A. Ga naar https://github.com en log in.
B. Klik rechtsboven op '+' en kies 'New repository'.
C. Geef de repository de naam: devlog
D. Kies 'Public' en klik op 'Create repository'.
E. Upload ALLE bestanden en mappen uit deze projectmap. Upload dus index.html, de vier weekpagina's, css, js en README.txt. Upload niet alleen de zip.
F. Ga in je repository naar Settings > Pages.
G. Bij 'Build and deployment' kies je:
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
H. Klik op Save.
I. Wacht een paar minuten. GitHub toont op de Pages-pagina de website-link.
   Die is meestal: https://JOUWGEBRUIKERSNAAM.github.io/devlog/

LET OP
- De repository moet Public zijn voor de eenvoudigste gratis GitHub Pages-configuratie.
- index.html moet direct in de hoofdmap staan, niet in een extra map.
- Na een wijziging upload je de aangepaste bestanden opnieuw naar GitHub.
- De voorbeeldteksten zijn placeholders. Vervang ze door je eigen echte devlog-inhoud.
- GitHub Pages host statische websites. Deze website gebruikt HTML, CSS en een klein beetje JavaScript; er is geen backend nodig.
