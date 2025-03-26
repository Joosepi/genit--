# Süsteemi testplant


mis on süsteemi testplant? 
See on oluline osa tarkvaraarenduses ja -testimises, kuna see aitab tagada süsteemi funktsionaalsuse ja usaldusväärsuse. Testplanti koostamine tähendab kõigi testimisprotsesside ja testide haldamist, et kontrollida süsteemi kõiki komponente ja nende vastavust määratud nõuetele.

### 1. **Testimise eesmärgi määratlus**
   - **Funktsionaalne testimine:** Kontrollige, kas süsteem täidab kõik oma nõuded ja funktsioonid õigesti.
   - **Jõudluse testimine:** Hinnake süsteemi kiirus, skaleeritavus ja ressursikasutus.
   - **Turvaproovide testimine:** Testige süsteemi vastupanuvõimet turvarikkumistele.
   - **Ühilduvuse testimine:** Kontrollige süsteemi ühilduvust erinevate seadmete, brauserite, operatsioonisüsteemide ja platvormidega.
   - **Regressioonitestimine:** Veenduge, et süsteemi muudatused ei riku olemasolevat funktsionaalsust.

### 2. **Testimise ulatuse määratlus**
   Määrake, millised süsteemi osad vajavad testimist:
   - Kas kõik funktsioonid peavad olema testitud või ainult kriitilised komponendid?
   - Kas tuleb testida ainult koodilõike või ka kasutajaliidest?

### 3. **Testkeskkonna ettevalmistamine**
   Testkeskkond peaks olema sarnane tootmiskeskkonnaga, kuid see võib sisaldada ka erinevaid tööriistu ja süsteeme, mis aitavad testi täpselt teostada:
   - **Riistvara:** Kasutatakse vastavat riistvara, näiteks servereid või tööjaamu.
   - **Tarkvara:** Paigaldage kõik vajalikud tarkvarad ja sõltuvused (näiteks andmebaasid, serverid jne).
   - **Andmed:** Kasutage testandmeid, mis simuleerivad reaalse elu olukordi.

### 4. **Testide tüübid**
   - **Üksuste testimine (Unit Testing):** Iga koodikomponendi kontrollimine iseseisvalt.
   - **Integreerimistestimine (Integration Testing):** Erinevate süsteemi osade koostöö kontrollimine.
   - **Süsteemitestimine (System Testing):** Testige kogu süsteemi koos kõigi komponentidega.
   - **Kasutaja aktsepteerimistestimine (UAT):** Kontrollige, kas lõppkasutajad suudavad süsteemi õigesti kasutada.

### 5. **Testimisstrateegia ja plaan**
   - **Testimise metoodika:** Määrake, kas kasutate manuaalset või automaatset testimist.
   - **Testide prioriteedid:** Määrake, millised testid on kõige olulisemad ja millal need tuleb läbi viia.
   - **Ajaraamid:** Koostage ajakava, millal ja kuidas testimine toimub, sh tähtaegade määramine.

### 6. **Testitulemuste analüüs**
   - Testitulemused tuleb dokumenteerida ja analüüsida, et tuvastada vead, puudused või täiendavad parendused.
   - Kasutatakse aruande vormingut (nt. Excel, Jira, TestRail), et hallata testide tulemusi.

### 7. **Vead ja tagasiside**
   Testimise käigus esinevad vead tuleb registreerida ja neid tuleb parandada vastavalt prioriteetidele.
   - Looge tagasiside süsteem, mis edastab vigade kohta aruanded arendajatele ja testijatele.
   - Korrake teste pärast vea parandamist, et tagada lahenduste korrektne rakendamine.

### 8. **Automatiseerimine**
   Automatiseerimine aitab säästa aega ja tagada, et teste saab pidevalt käivitada:
   - Kasutage testimisraamistikke nagu Selenium (veebirakenduste jaoks), JUnit või TestNG (Java jaoks) jne.
   - Automatiseerige funktsionaalsuse ja regressioonitestid.

### UI testimise raamistikud
Mis on UI testimise raamistikud? See on tööriistad, mis automatiseerivad ja haldavad kasutajaliidese testimist, kontrollides elementide (nuppude, väljade jne) õiget käitumist erinevates stsenaariumides. Need raamistikud on olulised, kuna kasutajaliides on see osa rakendusest, millega lõppkasutajad otseselt suhtlevad.

Siin on mõned levinud UI testimise raamistikud:

- Selenium
- Cypress 
- TestCafe 
- Appium 
- Playwright 
- Robot Framework 
- Katalon Studio 
- SikuliX 
