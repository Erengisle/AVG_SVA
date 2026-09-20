# Grammatikövningar för SVA

Interaktiva övningssidor i svensk grammatik för gymnasiet, byggda för genomgång via projektor och för elevernas egen träning. Varje övning är en enda HTML-fil utan installation, konto eller server.

## Länkar

| Övning | Länk | Innehåll |
| --- | --- | --- |
| Ordföljd på tavlan | https://erengisle.github.io/AVG_Sva/ | Huvudsatsordföljd, satsschema, att-bisatser, frågebisatser |
| Relativa bisatser | https://erengisle.github.io/AVG_Sva/relativa-bisatser/ | som, där, då, vilket, varav, vars – genomgång, diagnos och 16 uppgifter |

Varje mapp i repot blir en egen adress. Nya övningar läggs i en egen mapp med filnamnet `index.html` och förs in i tabellen ovan.

---

## Ordföljd på tavlan

Mapp: `/` (repots rot)

| Flik | Innehåll |
| --- | --- |
| Satsschema | Genomgång av satsschemat för huvudsatser. Välj vilket led som ska stå först och se hur leden flyttar sig mellan kolumnerna. Härifrån når man också en adverböversikt. |
| Rätt ordföljd | Bygg huvudsatser av lösa ord, med angivet startord eller fri ordföljd. |
| Ändra ordföljden | Flytta om leden i färdiga meningar. |
| Trälarna | Samma sak, men meningarna bildar tillsammans en sammanhängande text som går att läsa i sin helhet. |
| Muntlig övning | Eleven säger meningen högt, sedan animeras ordföljdsbytet. |
| Att-bisatser | Bygg om huvudsatser till att-bisatser och placera dem i rätt mening. |
| Börja med att-bisatsen | Animerad flytt av bisatsen till fundamentet. |
| Frågebisatser | Frågor görs om till frågebisatser, med färgmarkerade led. |

Övningarna bygger på *Avancera Gram* (s. 6–13).

## Relativa bisatser

Mapp: `/relativa-bisatser/`

| Flik | Innehåll |
| --- | --- |
| Inledare | Områdets inledning: vad en relativ bisats är och varför den behövs, plus kort för som, vilken/vilket/vilka, vilket, vars, där, då och varav. |
| Genomgång | Sju exempel där två meningar animeras ihop till en. Det ord som ersätts stryks, inledaren glider in först och orden flyttar sig till bisatsordföljd. |
| Vad kan du redan? | Tio meningar där eleven väljer inledare och får förklaringen direkt. |
| Övningen (16) | Bokens uppgifter i tre steg: välj inledare, bygg bisatsen, lägg ordet som ersätts åt sidan. |

Övningarna bygger på *Avancera Gram*, "En övning som inte är så lätt" (s. 15–17). Genomgången utgår från *Form i Fokus B*, avsnittet om relativa pronomen.

---

## Gemensamma funktioner

- **Ordbrickor** som kan dras eller klickas, med stöd för mus, pekskärm och tangentbord.
- **Satsschema** (ordföljdsövningen) som kan visas medan eleven bygger meningen.
- **Facitkontroll** som godtar flera möjliga lösningar och ger ledtrådar i stället för rätt svar.
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

## Så används sidorna

**På tavlan:** öppna sidan, tryck F för helskärm och låt klassen föreslå lösningar innan facit visas.

**Som elevuppgift:** dela länken, till exempel i Classroom. Eleverna behöver inget konto.

## Lagring och personuppgifter

All träning sparas lokalt i elevens egen webbläsare (`localStorage`). Ingenting skickas till någon server, och läraren ser inga resultat automatiskt. Eleven kan visa sin sammanfattning vid ett enskilt samtal, och kan själv nollställa sin historik i samma ruta. Byter eleven dator eller webbläsare börjar historiken om.

## Teknik

- En fristående HTML-fil per övning, med inbyggd CSS och JavaScript.
- Externa resurser: typsnittet Atkinson Hyperlegible (Google Fonts) och SortableJS (cdnjs) för dra-och-släpp. Blockeras de går sidorna ändå att använda genom att klicka på orden.
- Inget byggsteg. Filerna kan redigeras direkt och laddas upp igen.

## Lägga till en ny övning

1. **Add file → Upload files** och ladda upp HTML-filen i repots rot.
2. Klicka på filen, tryck på pennan och ändra namnet till `mappnamn/index.html`.
3. **Commit changes**. Adressen blir `https://erengisle.github.io/AVG_Sva/mappnamn/`.
4. Lägg in adressen i tabellen **Länkar** högst upp.

## Uppdatera en övning

Ladda upp den nya filen över den gamla i rätt mapp och commita. Länken är oförändrad. Be eleverna ladda om sidan, eller trycka Ctrl+F5, så att de får den nya versionen.

## Upphovsrätt

Övningsmeningarna kommer från *Avancera Gram* och *Form i Fokus* (Fasth–Kannermark) och används i undervisningen. Genomgångar, förklaringar och exempelmeningar på sidorna är egen text. Kontrollera att spridningen ryms inom skolans kopieringsavtal innan länkarna sprids utanför den egna undervisningsgruppen.
