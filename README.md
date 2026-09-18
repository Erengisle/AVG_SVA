[README.md](https://github.com/user-attachments/files/32375167/README.md)
# Ordföljd på tavlan

En interaktiv övningssida i svensk ordföljd för gymnasiet, byggd för genomgång via projektor och för elevernas egen träning. Sidan är en enda HTML-fil utan installation, konto eller server.

**Öppna sidan:** https://erengisle.github.io/ordfoljd/

---

## Innehåll

| Flik | Innehåll |
| --- | --- |
| Satsschema | Genomgång av satsschemat för huvudsatser. Välj vilket led som ska stå först och se hur leden flyttar sig mellan kolumnerna. |
| Rätt ordföljd | Bygg huvudsatser av lösa ord, med angivet startord eller fri ordföljd. |
| Ändra ordföljden | Flytta om leden i färdiga meningar. |
| Trälarna | Samma sak, men meningarna bildar tillsammans en sammanhängande text som går att läsa i sin helhet. |
| Muntlig övning | Eleven säger meningen högt, sedan animeras ordföljdsbytet. |
| Att-bisatser | Bygg om huvudsatser till att-bisatser och placera dem i rätt mening. |
| Börja med att-bisatsen | Animerad flytt av bisatsen till fundamentet. |
| Frågebisatser | Frågor görs om till frågebisatser, med färgmarkerade led. |

Övningarna bygger på *Avancera Gram* (s. 6–13). Meningarna är bokens; allt annat innehåll på sidan är eget material.

## Funktioner

- **Ordbrickor** som kan dras eller klickas, med stöd för mus, pekskärm och tangentbord.
- **Satsschema** som kan visas i övningarna och som uppdateras medan eleven bygger meningen. Om ordföljden i schemat inte stämmer med meningen på raden får eleven en varning om verbets och subjektets plats.
- **Adverböversikt** som öppnas från satsschemat: satsadverb, tids-, rums-, sätts- och gradadverb, bildning och komparation.
- **Facitkontroll** som godtar flera möjliga ordföljder och ger ledtrådar i stället för rätt svar.
- **Min sammanfattning** (knapp uppe till höger): eleven ser vad hen har tränat på, vilka regler som behöver mer träning och sina egna felaktiga meningar bredvid den rätta versionen. Inga poäng och inga betyg visas, och inget skickas någonstans.
- **Rensa övningen** och **Rensa allt** för att snabbt tömma tavlan mellan grupper.
- **Helskärm** och **ljust/mörkt tema** för projektor.

### Tangentbord

| Tangent | Funktion |
| --- | --- |
| ← → | Föregående/nästa uppgift |
| Mellanslag | Visa i de animerade övningarna |
| F | Helskärm |
| Esc | Stäng en ruta |

## Så används sidan

**På tavlan:** öppna sidan, tryck F för helskärm och låt klassen föreslå ordföljder. "Visa verbets plats" markerar det finita verbet och visar om det står på plats 2.

**Som elevuppgift:** dela länken, till exempel i Classroom. Eleverna behöver inget konto.

## Lagring och personuppgifter

All träning sparas lokalt i elevens egen webbläsare (`localStorage`). Ingenting skickas till någon server, och läraren ser inga resultat automatiskt. Eleven kan visa sin sammanfattning vid ett enskilt samtal, och kan själv nollställa sin historik i samma ruta. Byter eleven dator eller webbläsare börjar historiken om.

## Teknik

- En fristående HTML-fil med inbyggd CSS och JavaScript.
- Externa resurser: typsnittet Atkinson Hyperlegible (Google Fonts) och SortableJS (cdnjs) för dra-och-släpp. Blockeras de går sidan ändå att använda genom att klicka på orden.
- Inget byggsteg. Filen kan redigeras direkt och laddas upp igen.

## Uppdatera sidan

Ladda upp den nya HTML-filen över den gamla i repot och commita. Länken är oförändrad. Be eleverna ladda om sidan så att de får den nya versionen.

## Upphovsrätt

Övningsmeningarna kommer från *Avancera Gram* (Fasth–Kannermark) och används i undervisningen. Adverböversikten och alla förklaringar på sidan är egen text. Kontrollera att spridningen ryms inom skolans kopieringsavtal innan länken sprids utanför den egna undervisningsgruppen.
