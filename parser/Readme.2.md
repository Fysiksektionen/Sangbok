## Att fixa
* Idiotsäkra parsningen av fetstilt och kursiv text, samt gör något liknande för `\mcode{...}`.

## Förändringar
För att underlätta parsing, är det bra om saker är standardiserade. Denna branch har därför ändrat:
* Alla titlar, så att bokstäver efteråt hamnar _efter_ dollartecknena, och att `\Large` är en för-modifier, utan måsvingar.
* Bytt namn Jesus lever till Ny-18 (Ny-17 var dubblett.).
* Textregistrets sida 2, samt namnregistrets sida 2 och 4 har nu samma marginal som resten av sidorna i registret.
* Fler ändringar kommer, och det återstår att testa så att resultatet blir likvärdigt.

## Ändringar per kapitel
### Mindre layout-ändringar
* Alfa - Auld lang syne har försumbart ändrat marginalavstånd
* Beta - har en radbrytnings-bugg på första sidan, som är fixad på ett rätt fult sätt.
* Delta - Supreglerna på första sidan radbryts på fel ställen (fyllehundar, middagstupplur, ordinarie)
* Zeta - På sista sidan radbryts "sittningar" på fel ställe.
* Iota - ODE till en husvagn har radbrytning i friktion, till skillnad från innan.
* My - Ändrad så att den följer marginalstandarden (när matematikhatarvisan insattes, hamnade marginalerna ur synk).
* Ny - Radavståndet något ändrat på sidan 16 och 18. Mariginalen är justerad på sista sidan.
* Sigma - Ändrad så att den följer marginalstandarden.

### Innehållsändringar
* Alfa - Hugo Alvén ändrad till Hugo Alfvén.
    * Internationalen - 
        * "slå oss bi" -> "stå oss bi"
        * "han" -> "hen"
        * Fixad typo i "lättingen"
    * Gud är ickebinär
* Beta
    * Härjavisan "då värdig" -> "så tuff" (tre stavelser på två toner är lite so-so...)
* Delta
    * 2a - "förtära" -> "dricka" (passar bättre med antalet stavelser)
    * 3a - "bordspartner" -> "bordsvän" (passar bättre med antalet stavelser)
    * 7b har nu ett mellanslag efter indexet.
    * 14e har en punkt efter indexet.
    * Måsen lyfter "nu", inte "ny".
    * Mesen är full som en kaja "trots" fröna, inte "trot".
    * Mera Skåne har fått "beklagd" utbytt mot "bleklagd".
    * Livet är härligt har fått melodin ändrad till "Polyushko-polye" från "Röda kavalleriet".
    * Vodka, vodka - "Från våran stat" -> "vill jag dricka" (mer grammatiskt korrekt), "kamrat" -> "männ'ska" (kamrat är betonat på fel stavelse)
    * 11d - "längst" -> "längs", "ju bättre" -> "blir bättre"
    * 11f - jätte plask -> jätteplask
    * 13a - "ock" -> "och"
    * 13c - "bröder" -> "vänner", "näsan är röder" -> "näsan den ränner"
    * 15a - delvis könsneutraliserad. Bör ev. neutraliseras ytterligare.
* Gamma
    * 5 - "Gudagott är ölen på fat." -> "Öl är gudagott att dricka." (Passar bättre med betoningarna)
    * 7 - nertill -> ner till
* Epsilon - 9 "enn" -> "en"
* Theta - 11b har nu kursiv källreferens.
* Zeta
    * 3 "fårä" -> "får"
    * 7 "nån förnäm" -> "fin", "det kanske" -> "om det"
* Eta 1 - Vattenfysikalen Shakespeare var 1990 (enl. deras hemsida).
* Lambda
    * 4 - "när när" -> "när den"
    * 9 skrevs av A. de la Halle, inte Hale
* Kappa
    * 8 - "azur skiftande" -> "azurskiftande"
    * 10 - "den" -> "en"
* My
    * 2 - "Osquristina" -> "Osquarulda" (vet inte vilket som är bättre, men har en känsla av att det sistnämnda är vanligare när den väl sjungs)
    * 7 - "jag" -> "hen", etc.
* Ny
    * Hallen luta - "alldles" -> "alld'les"
    * Älska dig själv - "dig" -> "dej" (en måste vara konsekvent)
    * Lumberjack song - Mounties är nu fetstilt (standardisering)
* Omikron - "bröder" -> "fränder"

<!--TODO: Find mänska -> männ'ska, etc.-->

## Parser
Dvs. skillnader mellan den digitala versionen och den fysiska just nu.
* Alfa
    * I övrigt skiljer sig enbart punktuationer och versaliseringar mellan de två versionerna.
    * 1 har fler verser i den digitala.
* Beta
    * 1, 7 - saknar citationstecken
    * 8 - Olle är inte längre ickebinär, precis som i den fysiska upplagan (good or bad, let me know)
* Delta
    * Vodka, vodka - extra verser läses inte in.
    * Inre dialog - försångare/alla läses inte in.

## Ändringar av de digitala texterna
(Någon bör ta ställning till dessa. Mindre, uppenbara, genusändringar har utelämnats.)
* Alfa
    * Internationalen "systrabandet" -> "brodersbandet" (finns det ingen könsneutral variant?)
* Beta
    * Härjavisan "håriga bröst" -> "stolta bröst"
* Gamma
    * 5 - könsneutraliserad efter den fysiska upplagan. Dock sker en del betoningsfel, så ev. bör val av "vännen", "kamrat", etc. ses över.
* Iota - ODE till en husvagn har nu symboler istället för text. Detta kan påverka generatorn.
* Delta
    * 2e - Plask omges nu av ett bindestreck (–) istället för 3.
* Epsilon 3 - könsneutral.
### Dialogändringar
Dvs. texter där vem som sjunger noterats med bokstäver i den digitala, vilket ändrats till fetstilt.
* Delta 9d, 11g

## Oklarheter:
* Theta-6 Dom som är nyktra har en oklar radbrytning mitt i harmynta.